# ENPM690-AutonomousRobot
ENPM690 HW#3


Instructions to run the program:
 
1. Create a Catkin Workspace
  mkdir -p ~/catkin_ws/src

2. Initialize the Workspace
  cd ~/catkin_ws/src
  catkin_init_workspace

3. Extract the submission folder content into the src directory

4. Build the packages and source the setup file
  cd ~/catkin_ws
  catkin_make

5. Execute the launch files
    cd ~/catkin_ws
    
  Open two terminals(T1 and T2) and run the following commands:
  
    T1: source ~/catkin_ws/devel/setup.bash
    T1: roslaunch my_robot world.launch
    T2: source ~/catkin_ws/devel/setup.bash
    T2: roslaunch ball_chaser ball_chaser.launch

6. Drag the white ball in view cone of the robot (in Gazebo)

Note: - ROS needs to be installed on the system to run this project.
        Please ignore the empty folders(ball_chaser and my_robot) on this repository. Will update it later.
