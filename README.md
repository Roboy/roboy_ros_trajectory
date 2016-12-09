# Roboy Trajectory Control 
ROS package for loading and playing back trajectories. 

## install
```
#!bash
git clone --recursive https://github.com/Roboy/roboy_ros_trajectory
cd roboy_ros_trajectory
catkin_make
```
### run 
```
#!bash
source devel/setup.bash
roslaunch roboy_hardware roboy.launch
rosrun roboy_ros_trajectory roboy_ros_trajectory
```
