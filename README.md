# Jose Sanchez Gonzalez

I build ML systems and robot perception, with reproducible evaluations.
Seeking **machine learning / AI and robotics engineering roles**.
M.S. Artificial Intelligence and B.S. Computer Science, Oregon State University.

[Portfolio](https://jose-sanchez-portfolio-com.vercel.app) · [Résumé](https://jose-sanchez-portfolio-com.vercel.app/resume.pdf) · [LinkedIn](https://linkedin.com/in/jose-j-sanchez-gonzalez-84a800257/) · [Email](mailto:josejsanchez20172@gmail.com)

[![A simulated pruning arm approaches a branch, performs a gated surrogate release, and returns home](https://raw.githubusercontent.com/joses2017smjh/isaac-sim-pruning-workflow/develop/docs/demo/isaac_two_trees_vision_sequence.gif)](https://jose-sanchez-portfolio-com.vercel.app/projects/isaac-pruning-workflow/)

*One controlled Isaac Sim episode. Classical RGB-D tracking, simulator depth and rigid-piece release; this is not a learned pruning policy or a wood-fracture model.*

## Featured work

| Project | What I built | Evidence and limits |
|---|---|---|
| [SPUR metric depth](https://github.com/joses2017smjh/spur-depth-service) | Synthetic depth models, FastAPI inference and split ONNX export. | Encoder parity max difference 1.53e-5; V100 fp16 model p50 156 ms per six-view group. Field accuracy remains unverified. |
| [Humanoid Robustness Ladder](https://github.com/joses2017smjh/bhl-robustness-ladder) | Isaac Lab curricula, ONNX/MuJoCo evaluation and seeded failure controls. | Known-route Isaac task: 380/384 first episodes with sensor noise on; a 20 ms IMU delay halves it, and a delay-randomized fine-tune restores 32/32. Frozen-gait MuJoCo inspection: 3/3. No hardware-transfer claim. |
| [LeHome garment folding](https://github.com/joses2017smjh/IsaacSimFolding) | SmolVLA fine-tuning in Isaac Sim on Slurm: restartable driver, simulator-validated recovery search, preregistered matched evaluation. | Found and fixed an optimizer defect that froze ~88% of trainable parameters in every earlier fine-tune. Best candidate vs baseline, measured side by side: H10 8/16 vs 5/16 (p = 0.24), H50 7/16 vs 7/16 — no improvement under the preregistered rule; the gain is pose-specific. 27 settled folds recorded with hashes. |
| [Vision-guided pruning](https://github.com/joses2017smjh/isaac-sim-pruning-workflow) | RGB-D control, dual-ToF release checks, an independent recording grader and a ROS 2 software-in-the-loop node. | One selected episode passes 17/17 checks; a pre-registered 40-trial sweep on new spur targets passed 0/40, published. ROS 2 node matches the Python controller 199/199. Frozen depth model loses 6–8× at evening on 8/8 rendered trees (shading, not exposure; no test-time curve fixes it) and floors at 0.6–0.9 m below 0.4 m range; one metric range fixes UFO daylight (0.19→0.06 m), not Envy. Known target, classical tracking, rigid-piece release. |
| [MetaNaviT](https://github.com/joses2017smjh/MetaNavT) | Retrieval and data APIs in a six-person team; solo follow-up: hybrid retrieval benchmark served over Postgres. | BEIR SciFact, 300 queries: reranked hybrid +0.075 nDCG@10 over BM25 (95% CI 0.053 to 0.101); our BM25 matches Anserini within 0.002. LLM-judge gate not yet evaluable. |

## Technical focus

Python, PyTorch, OpenCV, Isaac Sim / Isaac Lab, MuJoCo, ONNX Runtime,
FastAPI and Slurm. I connect model outputs to measurable behavior, document
failure cases, and keep demos linked to the code and evaluation that support them.

The [portfolio](https://jose-sanchez-portfolio-com.vercel.app/#projects) provides
short visual case studies; the repositories contain setup, architecture,
results and current limitations.

