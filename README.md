# industrial_robot_motion_interfaces

> [!NOTE]
> This repository started as a design draft for implementing motion primitives on ros2_control. This has by now been merged into [control_msgs](https://github.com/ros-controls/control_msgs).

This ROS 2 interfaces package aims at providing a message interface to represent robot (as in
manipulators) motions as they are traditionally programmed: A series of primitives such as `LIN`,
`PTP`, `CIRC`.
