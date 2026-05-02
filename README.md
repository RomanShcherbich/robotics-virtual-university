# Robotics Virtual University

Self-learning robotics project with AI agents as teachers and coordinators.

## Goal

Become a **Junior Robotics Simulation Engineer / Robotics Software Engineer**.

## Core Stack

| Tool | Version / Variant |
|---|---|
| Ubuntu | 24.04 |
| ROS 2 | Jazzy |
| Gazebo | Harmonic |
| Webots | Latest |
| Robot descriptions | URDF / xacro / SDF |
| Control | ros2_control |
| Navigation | Nav2 |
| Vision | OpenCV |
| Data recording | rosbag2 / MCAP |
| Hardware | Arduino |

## Rules

1. **Practice first** — every concept is learned through hands-on tasks
2. **Every lesson creates an artifact** — code, config, launch file, or recording
3. **No moving forward without understanding** — must answer questions before next lesson
4. **Use `sources/` as working knowledge** — not a link dump, a structured system
5. **Use `prompts/` as reusable AI workflows** — templates for learning with AI agents

## Project Structure

```
README.md               ← You are here
sources/                ← Knowledge source system
  core/                 ← Core stack overview
  ros2/                 ← ROS2 concepts (nodes, topics, services, actions, launch, tf2)
  simulation/           ← Simulators (Gazebo, Webots, URDF)
  navigation/           ← Nav2, SLAM
  vision/               ← OpenCV, depth cameras
  hardware/             ← ros2_control, sensors
  advanced/             ← Behavior trees, MoveIt, Foxglove, MCAP
prompts/                ← Reusable AI prompt templates
  learn/                ← "Explain X using sources" workflows
  debug/                ← "Help me fix X" workflows
  review/               ← "Review my code/understanding" workflows
  create/               ← "Generate code/config for X" workflows
```

## How It Works

### Sources → Lessons → Artifacts

```
1. source → task (read source, get assignment)
2. task   → code (write implementation)
3. code   → bug  (hit real problems)
4. bug    → source (go back, understand deeper)
```

### AI Integration

Sources are used directly in AI prompts:

```
Use sources/ros2/nodes.md

Explain:
- what is a node
- how topics work
- show example in Python
```

Prompt templates in `prompts/` standardize these interactions.

## License

Apache License 2.0 — see [LICENSE](LICENSE).
