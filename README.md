# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles.

### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values with the link lenght wherever necessary.
4. simulate the model for forward kinematics.
5. plot the graph between the link and the joints.
6. update the DH parameters of the link configuration and end effector configuration.

DH PARAMETERS:


6 DOF



![image](https://github.com/KARTHICKRAJM84/Forward-kinematics-using-robot-analyzer/assets/128134963/ae0db789-2d82-4a4c-bbe1-e11dcd6c3103)


4 DOF

![image](https://github.com/KARTHICKRAJM84/Forward-kinematics-using-robot-analyzer/assets/128134963/1f12a954-8454-4a30-8338-15f7c7c29b33)



### SIMULATION 
#### 6 DOF

![image](https://user-images.githubusercontent.com/74660507/170177164-3aff1758-89d2-4378-a358-86da308541c0.png)



#### 4 DOF
 
![WhatsApp Image 2022-05-25 at 9 32 27 AM](https://user-images.githubusercontent.com/74660507/170177239-ee5529fb-85c1-4c7b-a7a1-8fc76135333c.jpeg)




### PLOT 


 
#### 6 DOF

![image](https://user-images.githubusercontent.com/70213227/170174722-a81f96da-e92a-4d68-b0fd-79c50bcf3919.png)


![image](https://user-images.githubusercontent.com/70213227/170174849-142fab7b-61d8-43c1-bae7-41643aeafc85.png)

#### 4 DOF

![image](https://user-images.githubusercontent.com/70213227/170175025-07bb37e4-f842-497f-b014-13bc88d8da6d.png)

![image](https://user-images.githubusercontent.com/70213227/170175000-7e58a8da-dd7e-4143-8d1f-d80911fabb30.png)



EE CONFIGURATION:

6 DOF

![image](https://github.com/KARTHICKRAJM84/Forward-kinematics-using-robot-analyzer/assets/128134963/3f0461f5-c626-40f3-8d11-d0d728479aae)


4 DOF



![image](https://github.com/KARTHICKRAJM84/Forward-kinematics-using-robot-analyzer/assets/128134963/5e8096c2-ecf3-45e8-9eeb-87adebda3703)

### RESULTS : 
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
