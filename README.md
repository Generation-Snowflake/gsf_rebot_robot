# gsf_rebot_robot
first amr demo of gsf robotics

## Requirements
This software is built on the Robotic Operating System (ROS), which needs to be [installed](http://wiki.ros.org/noetic/Installation)
#### Works on:
- Ros Melodic On Ubuntu 18.04
- Ros Noetice On Ubuntu 20.04

#### Installation
- robot_state_publisher ``sudo apt-get install ros-noetic-robot-state-publisher``


- first run this command to open world ``roslaunch rebot_gazebo rebo.launch`` *Noted if you want a big world for many robot you can use big_fac.world*

- run this command to spawn model ``roslaunch rebot_description spanw.launch``

run this command to see in rviz ``roslaunch rebot_description rviz.launch``

**rebot_new pkg not use now**
