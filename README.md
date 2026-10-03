# Jose Sanchez Gonzalez

I build robot perception, control, and simulation—from metric-depth inference to VR teleoperation on a self-built humanoid.

Seeking **robotics software, AI/ML, and computer vision engineering** roles. M.S. Artificial Intelligence and B.S. Computer Science, Oregon State University.

[Portfolio](https://jose-sanchez-portfolio-com.vercel.app) · [Résumé](https://jose-sanchez-portfolio-com.vercel.app/resume.pdf) · [LinkedIn](https://linkedin.com/in/jose-j-sanchez-gonzalez-84a800257/) · [Email](mailto:josejsanchez20172@gmail.com)

[![Berkeley Humanoid Lite physical arm teleoperation demonstration](https://media.githubusercontent.com/media/joses2017smjh/quest-vr-teleop/main/docs/demo/quest-vr-teleop.gif)](https://jose-sanchez-portfolio-com.vercel.app/projects/berkeley-humanoid-vr/)

*Quest 2 arm control with simulation and physical-hardware backends. The case study includes the demonstration and calibration evidence.*

## Featured work

- **[Berkeley Humanoid VR](https://github.com/joses2017smjh/quest-vr-teleop)** — WebXR controller poses → inverse kinematics → SocketCAN arm commands, with gravity feedforward and grip-based motion gating. Ten arm joints have recorded calibration checks; hardware integration is separate from learned locomotion studies.
- **[Vision-guided pruning](https://github.com/joses2017smjh/isaac-sim-pruning-workflow)** — RGB-D control, dual-ToF/contact release gates, and independent recording checks in Isaac Sim. Recent low-sun controls separate shadow-induced tracking loss from actual occlusion; population failures remain published.
- **[SPUR metric depth](https://github.com/joses2017smjh/spur-depth-service)** — FastAPI inference, six-view RGB+D refinement, split ONNX export, and calibrated reconstruction. Five stored synthetic best-validation scores: **0.0445 ± 0.0057 m** trunk RMSE; real-orchard accuracy is unverified.
- **[Humanoid Robustness Ladder](https://github.com/joses2017smjh/bhl-robustness-ladder)** — Isaac Lab training and MuJoCo evaluation with matched controls. Studies cover randomization, lidar-mapped navigation, and gait-clock ablations; results are simulation-to-simulation.
- **[Bimanual garment folding](https://github.com/joses2017smjh/IsaacSimFolding)** — VLA integration, cloth simulation, source-pinned paired evaluations, and checkpoint-promotion gates. The latest fine-tune improved short-horizon outcomes but failed the long-horizon gate; the baseline was retained.

## Technical focus

Python, C++, PyTorch, OpenCV, Isaac Sim / Isaac Lab, MuJoCo, ROS 2, SocketCAN, ONNX Runtime, FastAPI, Docker, and Slurm.

For software and retrieval roles: **[MetaNaviT](https://github.com/joses2017smjh/MetaNavT)** combines lexical/dense retrieval, source tracing, and reviewable file operations with benchmarked reranking.

The [portfolio](https://jose-sanchez-portfolio-com.vercel.app/#projects) provides
short visual case studies; the repositories contain setup, architecture,
results and current limitations.
