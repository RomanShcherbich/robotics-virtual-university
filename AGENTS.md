# AGENTS.md

## Cursor Cloud specific instructions

This repository (`robotics-virtual-university`) is a self-learning robotics project using AI agents as teachers and coordinators.

### Project structure

```
sources/           ← Knowledge system (NOT a link list — structured working sources)
  core/            ← Core stack overview (stack.md, ros2.md)
  ros2/            ← ROS2 concepts (nodes, topics, services, actions, launch, tf2)
  simulation/      ← Simulators (gazebo, webots, urdf)
  navigation/      ← Navigation & SLAM (nav2, slam)
  vision/          ← Computer vision (opencv, depth_cameras)
  hardware/        ← Hardware control (ros2_control, sensors)
  advanced/        ← Advanced topics (behavior_trees, moveit, foxglove, mcap)
```

### Source file format

Each source file is a **working tool**, not just a link. It follows the format:
- **Link** — URL to official docs
- **What it is** — brief description
- **When to use** — specific use cases
- **Key sections** — important parts to read
- **Questions** — open questions for learning
- **My notes** — personal conclusions (filled during learning)

### Key principle

Sources are integrated with lessons. Each lesson should reference its sources:
```md
## Sources
- sources/ros2/nodes.md
- sources/core/stack.md
```

### Technology stack (planned)

- Python 3.12
- ROS2, Gazebo, Nav2, ros2_control
- OpenCV for vision
- Foxglove/MCAP for visualization and data recording
- The `.gitignore` covers Django, Flask, Celery, Redis, Jupyter, Streamlit, Marimo patterns

### For future agents

- No runnable application exists yet — this is a knowledge/curriculum project.
- When source code is added, check for `pyproject.toml`, `requirements.txt`, or similar dependency manifests.
- AI agents act as **teachers**: use source files in prompts to teach specific topics.
