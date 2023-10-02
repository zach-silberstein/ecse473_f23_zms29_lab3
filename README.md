# LAB3

### This project interperts the "ROS bagged" data from an aarchitectural survey of the fifth floor of the Glennan building 
### Author: Zach Silberstein

#### Usage:  
To run the project, run the display.launch file by:  
`roslaunch navvis_description display.launch`  
  
The launch file has the following args:
* use_xacro (default false)
* use_gui (default true)
* use_robot_state_publisher (default true)
* use_new_xacro (default true)

  
use_xacro:  
This command does nothing if use_new_xacro is true  
If true, then the updated xacro file of the robot will be used  
If false, then the out dated urdf file of the robot will be used  
  
use_gui:  
If true, the the joint_state_publisher_gu will be launched  
if false, the joint_state_publisher wuill be launched instead

  
use_robot_state_publisher:  
If true, then the use_robot_state_publisher is launched  
If false, then the use_robot_state_publisher is not launched  
  

use_new_xacro:  
This tag should be set to true to see the updates from this lab  
If true, the updated robot with the IMU will be launched along with the most recent configration file  
If false, the version of the robot from the end of the second lab is launched

