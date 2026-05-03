# Learning Environment

## Current Environment

The learning environment for this Robotics Virtual University project is based on:

- Host OS: Windows 11
- Linux environment: WSL2
- WSL GUI support: WSLg
- Linux distribution: Ubuntu 24.04.1 LTS
- GPU: NVIDIA GeForce RTX 4070 Laptop GPU
- OpenGL renderer in WSL: D3D12 via NVIDIA GPU

## Robotics Stack

Installed and verified:

- ROS 2 Jazzy
- Gazebo Harmonic / `gz sim`
- ROS 2 demo nodes

## Verified Checks

### GPU / OpenGL

Command:

```bash
glxinfo | grep "OpenGL renderer"
```

Result:

```text
OpenGL renderer string: D3D12 (NVIDIA GeForce RTX 4070 Laptop GPU)
```

Meaning:

* WSLg uses GPU acceleration through D3D12
* Gazebo GUI can run inside WSL
* This setup is acceptable for learning ROS 2 and Gazebo basics

## ROS 2 Verification

Commands:

```bash
ros2 run demo_nodes_cpp talker
ros2 run demo_nodes_py listener
```

Result:

* `talker` publishes messages
* `listener` receives messages
* ROS 2 pub/sub communication works

## Gazebo Verification

Command:

```bash
gz sim
```

Result:

* Gazebo starts successfully
* Environment editor opens
* Example models can be loaded
* A robot arm model was opened successfully
* Initial loading may take around 2 minutes

## Environment Status

This environment is approved for the beginner and intermediate stages of the course.

Suitable for:

* ROS 2 CLI
* ROS 2 nodes
* topics, services, actions
* Python ROS 2 development
* basic Gazebo simulations
* URDF/xacro experiments
* RViz2
* rosbag2

Potential limitations:

* Gazebo may load slowly
* Complex simulations may lag
* Graphics issues are possible under WSLg
* Isaac Sim may require native Ubuntu later
* GPU-heavy simulation or robotics AI may require a native Linux setup

## Decision

Use this environment for now:

```text
Windows 11 + WSL2 + WSLg + Ubuntu 24.04.1 LTS + ROS 2 Jazzy + Gazebo
```

Do not switch to native Ubuntu yet.

Reconsider native Ubuntu or dual boot later if:

* Gazebo becomes unstable
* simulations become too slow
* Isaac Sim is required
* GPU-intensive robotics workloads are introduced
