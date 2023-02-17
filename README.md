teleop_tools
============

A set of generic teleoperation tools for any robot.

This contains the following teleoperation tools:

* `joy_teleop`, a generic joystick interface for topics and actions
* `key_teleop`, a lightweight console keyboard teleoperation utility
* `mouse_teleop`, a pointing device (e.g. mouse, touchpad) teleoperation utility

```bash
ros2 run joy joy_node
ros2 run joy_teleop joy_teleop --ros-args --params-file src/teleop_tools/joy_teleop/config/joy_teleop_example.yaml
```
