# Prompt: Create ROS2 Node

## When to use
When you need to generate a new ROS2 node as a starting point.

## Template

```
Use sources/ros2/nodes.md and sources/ros2/{relevant_concept}.md

Create a ROS2 Python node that:
- {requirement_1}
- {requirement_2}
- {requirement_3}

Include:
- Proper imports
- Node class with __init__
- Main function with rclpy.init/shutdown
- Comments explaining key parts

ROS2 distro: Jazzy
Style: clean, minimal, well-commented
```

## Example

```
Use sources/ros2/nodes.md and sources/ros2/topics.md

Create a ROS2 Python node that:
- Publishes to /cmd_vel (geometry_msgs/Twist)
- Sends a forward velocity of 0.5 m/s
- Publishes at 10 Hz

Include:
- Proper imports
- Node class with __init__
- Main function with rclpy.init/shutdown
- Comments explaining key parts

ROS2 distro: Jazzy
Style: clean, minimal, well-commented
```
