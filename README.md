# ROS2 and TurtleBot Robotics Simutation
This document serves as a comprehensive guide, compiling essential tasks and key learnings from the ROS2 workshop focused on simulating and controlling TurtleBot robots. It provides a practical overview of robotics simulation using ROS2, helping users understand and implement fundamental concepts effectively.
# Basic Linux Terminal Commands
```ls``` Lists the contents of the current directory, including files and subdirectories.

```cd```: Changes the current directory to the specified one.

```mkdir```: Creates a new directory.

 ```touch```:Used to create a new file
 
 ```ctrl```+```shift```+```O```:Opens a new terminal tab(multiple windows)

```rm```: Deletes a file from the specified directory.

```rmdir```: Removes an empty directory.

```cp```: Copies files or directories to a specified location.

```mv```: Moves or renames files and directories.

```pwd```: Displays the current working directory.


```clear```: Clears the terminal screen.
# Intorduction to ROS2
  * Topics covered are basic ROS2 architecture and commands
    - ```ros2 topic```
    - ```ros2 node```
# Creating a package in ROS2
* Created a ROS2 package using the colcon build tool ```sudo apt install``` &```colcon-build```
  * Added a Python script within the created package
  * Drew a circle using the package in VS code
<p align="center"><img src="./img">
# Launching Gazebo Simulation and controling the bot
  * Used ```ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py``` to launch a gazebo simulation with obstacles and a bot
<p align="center"> <img src="./img ROS/rosobjects.png">
  
  * Used ```ros2 run turtlebot3_teleop teleop_keyboard``` to use the keyboard WASD to move the 
   bot

# Using the Rviz to map the Gazebo environment

  *  Used ```ros2 launch turtlebot3_navigation2 navigation2.launch,py use sim_time:=True```
     to open Rviz and move the bot around using ```teleop``` to map the environment
<p align="center"> <img src="./img ROS/git1.jpg"> 

 unfinished map

<p align="center"> <img src="./img ROS/git2.jpg">

finished map

# Using Rviz to make the bot autonomously navigate the mapped area
 - starting location
<p align="center"> <img src="./img ROS/git3.jpg">
 - placing the destination
<p align="center"> <img src="./img ROS/gitloc.jpg">
 -  bot arrives at destination
<p align="center"> <img src="./img ROS/git4.jpg">

# Synopsis
* At the end of the workshop participants were able to
 - Efficiently navigate and handle file operations in the Linux terminal
 - Efficiently manage packages in ROS2
 - Control bots in ROS2 and VS code
 - Efficiently simulate bots using gazebo
 - Map environments using RViz
 - Automate bots in simulation using ROS2

  

