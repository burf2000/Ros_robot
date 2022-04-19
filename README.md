Ros_robot

Run Vex robot c code on Controller 

For ros

source /opt/ros/kinetic/setup.bash

cd ~/catkin_ws/
catkin_make

For Hector Slam run
sudo apt-get install ros-kinetic-hector-slam

Python scripts (e.g vextank.py)
sudo chmod +x vextank.ph
source devel/setup.bash

export ROS_MASTER_URI=http://127.0.0.1:11311 (or ip/host of computer)

go to /src/burf_robot/

roslaunch launch/robot.launch

(different terminal)
roslaunch desktop.launch

