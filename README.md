### ECSE 373/473 Laboratory 3 Submission


#### Description

This ROS package builds on a previous package to incorporate a map and movement component to a robot using RVIZ.

#### Dependencies

This ROS package has the dependancy of package https://github.com/cheezofsandwich/ecse373_f23_nat65_Nathan-Trudell_lab2


#### Installing

Downloading the package directly from github should provide all necessary components.

#### Execution of Program

To run this package: roslaunch navvis_robot visual.launch

Roslaunch params:

 use_xacro default set to true, whether or not to use xacro or urdf file for robot model

 use_joint_state_publisher_gui default set to true, whether or not to use joint state gui

 old_launch default set to false, whether or not to use old configuration or new
 
 use_sim_time default set to true, whether or not to use clock while running map simulation
 
 use_robot_state_publisher set totrue, whether or not to use robot state publisher
 
 file 			name of file to use (set to robot.urdf or robot.xacro)
	
  filename 			full path of file to use
  

Purpose of Launch File: Launches the program with prior configuration from lab 2 but enables it to be used in simulations use .bag files and on a map for motion.
 

#### Authors
Nathan Trudell using information created by Dr. Greg Lee for ECSE 373/473 laboratory 3
