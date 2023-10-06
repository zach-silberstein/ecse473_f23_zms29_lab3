# LAB3

### This project interperts the "ROS bagged" data from an aarchitectural survey of the fifth floor of the Glennan building 
### Author: Zach Silberstein

#### Usage:  
To run the project, run the display.launch file by:  
`roslaunch navvis_description display.launch`  
  
The launch file has the following args:
* use_xacro (default false)
* use_robot_state_publisher (default true)
* use_sim_time (default true)

  
use_xacro:
If true, then the updated xacro file of the robot will be used  
If false, then the out dated urdf file of the robot will be used  

  
use_robot_state_publisher:  
If true, then the use_robot_state_publisher is launched  
If false, then the use_robot_state_publisher is not launched  
  

use_sim_time:  
If true, then the /use_sim_time parameter is set to true