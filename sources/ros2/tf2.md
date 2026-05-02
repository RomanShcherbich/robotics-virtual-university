# ROS2 TF2 (Transforms)

## Link
https://docs.ros.org/en/rolling/Tutorials/Intermediate/Tf2/Tf2-Main.html

## What it is
TF2 is the transform library. It tracks coordinate frames over time and lets you transform data between frames (e.g., "where is the object detected by the camera in the robot's base frame?").

## When to use
- Any multi-sensor system
- Navigation (map → odom → base_link)
- Manipulation (base → arm → gripper → object)
- SLAM and localization

## Key sections
- Static transforms
- Dynamic transforms
- Transform listeners
- Transform broadcasters
- Frame tree (view with `ros2 run tf2_tools view_frames`)

## Questions
- What is the standard frame hierarchy for a mobile robot?
- How to publish a static transform?
- How to look up a transform between two frames?

## My notes
(здесь будут выводы по мере обучения)
