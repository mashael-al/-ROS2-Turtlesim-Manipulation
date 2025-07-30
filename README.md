 ROS2 Turtlesim Manipulation

This project demonstrates basic manipulation of the turtlesim package in ROS2.  

This project was completed successfully as part of the training program.
The task covered basic ROS2 service calls, topics, and node operations with 
---

Requirements
- ROS2 Humble (or any ROS2 version with turtlesim )
- Terminal access (via The Construct or local installation)


 Steps Summary
1. Run Turtlesim Node 
  " ros2 run turtlesim turtlesim_node "

2. Control Turtle Manually
" ros2 run turtlesim turtle_teleop_key " 

3. Spawn a New Turtle
" ros2 service call /spawn turtlesim/srv/Spawn "{x: 5.0, y: 5.0, theta: 0.0, name: 'turtle2'}"

4. Change Pen Color
" ros2 service call /turtle1/set_pen turtlesim/srv/SetPen "{r: 255, g: 0, b: 0, width: 3, off: 0}"

5. Teleport Turtle
" ros2 service call /turtle1/teleport_absolute turtlesim/srv/TeleportAbsolute "{x: 2.0, y: 2.0, theta: 0.0}"

- To access the project : https://app.theconstruct.ai/Desktop

  
