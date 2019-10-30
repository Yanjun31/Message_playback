## This is the package for the Lab 5 of EECS 473.

**Use the display.launch to view the robot with an IMU sensor in Rviz. The argument use_imu determines whether to use the XACRO file from the previous laboratory or the new XACRO file that adds the base_link and imu. The argument external_clock determines whether Rviz will use an external (simulated) clock or current clock. The argument use_decay determines whether Rviz will show decaying laser signals or not.**

**View the robot with imu sensors in external clock mode:**  
roslaunch my_robot display.launch use_imu:=true external_clcok:=true  

**View the robot with imu sensors in current clock mode:**  
roslaunch my_robot display.launch use_imu:=true external_clcok:=false  

**View the robot with imu sensors in external clock mode. Set the decay property of laser signals to 10:**  
roslaunch my_robot display.launch use_imu:=true external_clcok:=true use_decay:=true  

  
**Use the display_w_map.launch to view the robot in Rviz with the map. The arguments of this launch file are basically the same with display.launch.**

**View the robot in external clock mode with the map of the fifth floor:**   
roslaunch my_robot display_w_map.launch external_clcok:=true  

**View the robot in current clock mode  with the map of the fifth floor:**  
roslaunch my_robot display_w_map.launch external_clcok:=false  

**View the robot in external clock mode with the map of the fifth floor. Set the decay property of laser signals to 10:**  
roslaunch my_robot display_w_map.launch external_clcok:=true use_decay:=true

