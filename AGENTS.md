# AGENTS.md

## Cursor Cloud specific instructions

This repository (`robotics-virtual-university`) is a self-learning robotics project. AI agents act as **teachers and coordinators**. The goal is to become a Junior Robotics Simulation Engineer / Robotics Software Engineer.

### Learning rules (must follow)

1. **Practice first** — every concept is learned through hands-on tasks
2. **Every lesson creates an artifact** — code, config, launch file, or recording
3. **No moving forward without understanding** — verify comprehension before next lesson
4. **Use `sources/` as working knowledge** — structured source files, not link dumps
5. **Use `prompts/` as reusable AI workflows** — templates for learning interactions

### Core stack

Ubuntu 24.04, ROS 2 Jazzy, Gazebo Harmonic, Webots, URDF/xacro, SDF, ros2_control, Nav2, OpenCV, rosbag2/MCAP, Arduino.

### Project structure

```
README.md               ← Project overview, goals, rules
sources/                ← Knowledge source system (structured, not just links)
  core/                 ← Core stack overview (stack.md, ros2.md)
  ros2/                 ← ROS2 concepts (nodes, topics, services, actions, launch, tf2)
  simulation/           ← Simulators (gazebo, webots, urdf)
  navigation/           ← Nav2, SLAM
  vision/               ← OpenCV, depth cameras
  hardware/             ← ros2_control, sensors
  advanced/             ← Behavior trees, MoveIt, Foxglove, MCAP
prompts/                ← Reusable AI prompt templates
  learn/                ← Explain/compare/deep-dive workflows
  debug/                ← Fix-error/diagnose workflows
  review/               ← Check-understanding/code-review workflows
  create/               ← Generate ROS2 nodes/launch files
```

### Source file format

Each source file follows: Link → What it is → When to use → Key sections → Questions → My notes.

### For future agents

- No runnable application exists yet — curriculum/knowledge project.
- When source code is added, check for `pyproject.toml`, `requirements.txt`, or similar.
- Each lesson should reference its sources and produce an artifact.
- Use prompt templates from `prompts/` when interacting as a teacher.
