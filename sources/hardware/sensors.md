# Sensors in Robotics

## Links
- Lidar: https://docs.ros.org/en/rolling/p/sensor_msgs/
- IMU: https://docs.ros.org/en/rolling/p/sensor_msgs/
- Camera: https://docs.ros.org/en/rolling/p/sensor_msgs/

## What it is
Sensors provide the robot with information about its environment and its own state. Common sensors include lidar (laser distance), cameras (visual), IMU (orientation/acceleration), encoders (wheel rotation), and GPS.

## When to use
- Lidar: obstacle detection, SLAM, navigation
- Camera: object detection, visual SLAM, inspection
- IMU: orientation tracking, sensor fusion
- Encoders: odometry, wheel speed
- GPS: outdoor localization

## Key ROS2 message types
- sensor_msgs/LaserScan (2D lidar)
- sensor_msgs/PointCloud2 (3D lidar / depth camera)
- sensor_msgs/Image (camera)
- sensor_msgs/Imu (IMU)
- nav_msgs/Odometry (wheel encoders)

## Questions
- How to read lidar data in ROS2?
- How to process camera images?
- How to fuse IMU + odometry?
- What is sensor_msgs and how to use it?

## My notes
(здесь будут выводы по мере обучения)
