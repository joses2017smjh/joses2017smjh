# Jose Sanchez Gonzalez

I build robot perception, control, and AI software—from humanoid simulation and physical arm teleoperation to retrieval tools that show their sources.

Seeking **robotics software, embodied AI, computer vision, and AI/software engineering** roles. M.S. Artificial Intelligence and B.S. Computer Science, Oregon State University.

[Portfolio](https://jose-sanchez-portfolio-com.vercel.app/) · [Résumé](https://jose-sanchez-portfolio-com.vercel.app/resume.pdf) · [LinkedIn](https://linkedin.com/in/jose-j-sanchez-gonzalez-84a800257/) · [Email](mailto:josejsanchez20172@gmail.com)

## Humanoid Simulation

[![A simulated humanoid explores a maze with lidar mapping and sensor displays](https://raw.githubusercontent.com/joses2017smjh/bhl-robustness-ladder/main/docs/gifs/random-maze-humanoid-sensors.gif)](https://jose-sanchez-portfolio-com.vercel.app/projects/humanoid-navigation/)

*Learned gait with scripted planning and oracle pose/goal, at 5× playback. A selected simulation rollout; sensor display panels are separate from the control inputs.*

Three areas in [**Humanoid Robustness Ladder**](https://github.com/joses2017smjh/bhl-robustness-ladder):

- **[Locomotion & Control](https://jose-sanchez-portfolio-com.vercel.app/projects/bhl-robustness-ladder/)** — Isaac Lab training, MuJoCo qualification, disturbances, and terrain rollouts. Recent turning and terrain studies retain their exact controller and evaluation scope.
- **[Perception & Navigation](https://github.com/joses2017smjh/bhl-robustness-ladder/blob/main/docs/RANDOM_MAZE.md)** — Online lidar mapping, maze planning, sensor-fault studies, and matched navigation controls.
- **[Language-Guided Manipulation](https://github.com/joses2017smjh/bhl-robustness-ladder/blob/main/docs/WAITER_PROGRAM.md)** — SmolVLA selects a tumbler, loads a tray, and carries it to the instructed table. **76/100** held-out-phrasing successes in simulation, with standing assistance and a small instruction domain.

## RAG & Agents

[![Illustrated MetaNaviT query and source-inspection workflow](https://raw.githubusercontent.com/joses2017smjh/MetaNavT/main/doc/gifs/ask.gif)](https://github.com/joses2017smjh/MetaNavT)

*Illustrated retrieval workflow on demo files. Quantitative retrieval evaluations are documented separately.*

- **[MetaNaviT](https://github.com/joses2017smjh/MetaNavT)** — Hybrid retrieval over research files, source tracing, reviewable file operations, MCP tools, and ranking evaluations. Independent extensions build on an original six-person team project.
- **[Agentic Soccer MCP](https://github.com/joses2017smjh/Agentic-Soccer-Match-Prediction-MCP)** — FastAPI, LangGraph, and MCP tools for soccer analysis. Historical forecasting and agent tests are separate from the synthetic demo interface.

## Computer Vision & VLA

- **[Bimanual Garment Folding](https://github.com/joses2017smjh/IsaacSimFolding)** — Camera-driven policies, cloth simulation, and paired evaluation gates. Later runtime-horizon comparisons remain inconclusive; the baseline is retained.
- **[Vision-Guided Pruning](https://github.com/joses2017smjh/isaac-sim-pruning-workflow)** — RGB-D branch tracking, sensor-gated release, and independent checks of recorded successes and failures in Isaac Sim.
- **[SPUR Metric Depth](https://github.com/joses2017smjh/spur-depth-service)** — PyTorch depth models, RGB-D branch perception, a FastAPI service, and ONNX export. Synthetic depth results are measured; real-orchard accuracy remains unverified.

## Physical robotics

**[Quest VR Teleoperation](https://github.com/joses2017smjh/quest-vr-teleop)** connects WebXR controller poses to inverse kinematics and SocketCAN arm control. Calibration checks cover ten arm joints. [Watch the hardware preview](https://jose-sanchez-portfolio-com.vercel.app/projects/berkeley-humanoid-vr/).

## Technical focus

**Robotics & vision:** Python, C++, PyTorch, OpenCV, Isaac Sim / Isaac Lab, MuJoCo, ROS 2, SocketCAN, ONNX Runtime.

**AI & software:** FastAPI, PostgreSQL / pgvector, hybrid retrieval, RAG, MCP, Docker, and Slurm.

The [portfolio](https://jose-sanchez-portfolio-com.vercel.app/#projects) presents short visual case studies. The repositories contain setup, architecture, dated results, and current limits.
