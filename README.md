# imageimu2rosbag
A simplified version of [kitti2bag](https://github.com/tomas789/kitti2bag)

### Dependencies
ROS


### Build
```
mkdir -p catkin_ws/src
cd catkin_ws
source /opt/ros/kinetic/setup.bash
catkin_make
cd src
git clone git@github.com:AbnerCSZ/imageimu2rosbag.git
cd ..
catkin_make
source devel/setup.bash
```

### Usage
```
roscore
rosrun torosbag torosbag 
```
