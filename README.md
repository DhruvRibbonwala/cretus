# Introduction to Robotic Visualisation and Simulation

## Overview
This repository contains a ROS package `cretus` that contains necessary files to visualise and model a robot in RViz. One can also tinker with `ros_control` as dictated in further steps.

## Installation

1. Fire up the terminal in your rosject and type the following command to navigate to the required folder  
 ```bash
 cd catkin_ws/src
 ```
2. Then clone this repository by giving the following command  
 ```bash
 git clone https://github.com/DhruvRibbonwala/cretus.git
 ```
3. Then navigate back to the workspace directory by  
 ```bash
 cd ..
 ```
4. Then build the package by giving the following commands  
 ```bash
 catkin_make
 ```
5. Source the workspace to reflect these changes. Feel free to write this command every now and then
 ```bash
 source ~/catkin_ws/devel/setup.bash
 ```
 ## Launching
 In order to launch RViz to visualize `cretus` type the following code in the terminal
 ```bash
 roslaunch cretus bringup.launch
 ```
 To visualize the example `cretus2` that we have already created before hand, type
 ```bash
 roslaunch cretus bringup2.launch
 ```
 To simulate `cretus` in gazebo and move the robot, type
 ```bash
 roslaunch cretus cretus_gazebo.launch
 ```
 
## References
[URDF tutorials](https://wiki.ros.org/urdf/Tutorials)
