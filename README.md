# ROS2_Wheel_robot

This repository contains the simulation and teleoperation setup for a four-wheeled robot using ROS 2 and Gazebo.



### 1. Clone the Repository

```bash
git clone https://github.com/Bhanuprabhas1234/ROS2_Wheel_robot.git
cd ROS2_Wheel_robot


### 2. Build the Workspace and Source the workspace

colcon build
source install/setup.bash

🧪 Launch Simulation
ros2 launch gazebo_simulation robot_sim.launch.py

🕹️ Teleoperate the Robot

source install/setup.bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard

Use the keyboard to control the robot. Make sure the focus is on this terminal when sending commands.


