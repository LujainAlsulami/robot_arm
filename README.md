# robot_arm
This repository includes controlling the robot arm using Joint State Publisher, MoveIt, and kinematics.

Controlling the robot arm by joint_state_publisher

Step 1: 
Environment setup and create a workspace.

![Screenshot 2024-07-10 021519](https://github.com/user-attachments/assets/ec1c66b4-85bc-4cde-a3e3-9fb944c36ce1)

![Screenshot 2024-07-10 022338](https://github.com/user-attachments/assets/7b871806-d1b5-495a-a164-0adfb76bccdf)

Step 2:
Open the source directory of the Catkin workspace to clone the robot arm package. 

![Screenshot 2024-07-10 023233](https://github.com/user-attachments/assets/381ee975-a5c7-45a6-abb0-766028a53da9)

Step 3:
Install all the required packages.

![Screenshot 2024-07-10 023421](https://github.com/user-attachments/assets/50e13688-ec2f-401a-9be9-85f38d50c9af)
![Screenshot 2024-07-10 023658](https://github.com/user-attachments/assets/34eec425-3512-4c98-9aa7-e3c38b5e06cc)
![Screenshot 2024-07-10 023809](https://github.com/user-attachments/assets/bbce61f4-6efb-4976-86f1-03f6a706616d)
![Screenshot 2024-07-10 023900](https://github.com/user-attachments/assets/74af67c9-b9a7-4e20-8398-d2f3fb9818c1)


Step 4:

Launch the robotic arm in the RViz program to control it using the Joint State Publisher.

![Screenshot 2024-07-10 030050](https://github.com/user-attachments/assets/183faf6e-566c-4af9-8cad-36258002a6df)


Step 5:
The rqt graph shows the nodes and their connections.

![Screenshot 2024-07-10 030328](https://github.com/user-attachments/assets/92c478f2-74be-46ec-9c89-9db5cc693da4)


Step 6:
Shows the data published on a joint_states topic.

![Screenshot 2024-07-10 030435](https://github.com/user-attachments/assets/9a8d1abe-672d-4e66-85bf-c25ed2b166b5)



Output:
Change the positions of the robot arm's joints and visualize it.

![Screenshot 2024-07-10 030738](https://github.com/user-attachments/assets/1efda3a1-fcab-45d6-a104-a1ab05cbf381)




Controlling the robot arm by Moveit and kinematics

Step 7:
Simulate the robot arm in a Gazebo environment.

![Screenshot 2024-07-10 031139](https://github.com/user-attachments/assets/a3d1bfe5-f4f9-4525-818a-8bee3b4aaf53)

Step 8:
Change the permissions of the joint_states_to_gazebo.py 

![Screenshot 2024-07-10 031804](https://github.com/user-attachments/assets/199d391b-ee46-4e78-b97f-31fccc85e258)



Step 9:
Shows the connected nodes and topics to control the movement of the robot arm.

![Screenshot 2024-07-10 032656](https://github.com/user-attachments/assets/9300c6c4-09d8-458b-8648-292408a0f236)

Step 10:
Used MoveIt to plan the movement of the arm and observe the move in Gazebo.

![Screenshot 2024-07-10 033250](https://github.com/user-attachments/assets/041601de-5484-47c4-bc34-bb83a5360cda)

![Screenshot 2024-07-10 034239](https://github.com/user-attachments/assets/e2802692-d226-4306-8ade-46e11b437dc9)


