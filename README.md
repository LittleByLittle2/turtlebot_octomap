### 3D Mapping using Octomap on Turtle Bot

Install
-----
1. Install Octomap and Rtabmap  
```
$ sudo apt-get install ros-indigo-octomap ros-indigo-octomap-plugin ros-indigo-rtabmap ros-indigo-rtabmap-ros
```

2. TurtleBot Installation  
```
$ sudo apt-get install ros-indigo-turtlebot ros-indigo-turtlebot-apps ros-indigo-turtlebot-interactions ros-indigo-turtlebot-simulator ros-indigo-kobuki-ftdi ros-indigo-rocon-remocon ros-indigo-rocon-qt-library ros-indigo-ar-track-alvar-msgs
```

3. Set up 
```
$ cd ~/catkin_ws/src
$ wstool init
$ wstool set turtlebot_octomap https://github.com/RyuYamamoto/turtlebot_octomap.git --git
$ wstool update turtlebot_octomap
$ cd ~/catkin_ws
$ catkin_make
```

4. Run
```
$ roslaunch turtlebot_octomap turtlebot_build_map.launch
```
