## turtlebot2_kobuki
Kobuki Packages information with Nvidia-TX2 and Rplidar

### Prerequisites :


    Ubuntu 18.04
    ROS Melodic (Tested)


#### Method of using the repository

First clone the repository by opening a new terminal


`git clone https://github.com/WeGo-Robotics/turtlebot2_kobuki.git`

`cd turtlebot2_kobuki`

Install the depedencies:

`rosdep install --from-paths src --ignore-src -r -y`

`catkin_make`

`source devel/setup.bash`

#### Example of running a navigation launch file.

 ##### `roslaunch kobuki_navigation kobuki_navigation.launch`
 
 
 ##### References:
     https://github.com/yujinrobot/kobuki
     https://github.com/turtlebot/turtlebot_apps/tree/indigo/turtlebot_navigation
     http://wiki.ros.org/hector_mapping
     http://wiki.ros.org/rplidar
 
