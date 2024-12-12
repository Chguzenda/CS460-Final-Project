# CS460-Final-Project
Final robotics project
Trial 1:119/196
Trial 2:126/196
Trial 3:121/196

How to Run:

cd into the project folder (specifically f24_robotics)
colcon build
source install/setup.bash
source /opt/ros/humble/setup.bash
ros2 launch webots_ros2_homework1_python f23_robotics_1_launch.py
ros2 run webots_ros2_homework1_python webots_ros2_homework1_python

The program is a minor modification of my randomWalk from homework 1. It was originally going to have apriltag functionality but when that was cut I scrapped work on it. As I could not run the cartographer and controller at the same time, I manually counted the number of unique squares the robot entered over the course of each 10 minute trial.
