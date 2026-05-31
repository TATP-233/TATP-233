<div align="center">
  <h1>
    <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/>
    Hi, I'm Yufei Jia (贾宇飞)
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" alt="Waving hand">
  </h1>
  <!-- <img src="./assets/tatp.PNG" width="180" alt="Yufei Jia portrait"> -->
  <h3>Embodied AI Systems | High-Performance Simulation & Robot Learning Infrastructure</h3>
  <p>
    PhD Student, Department of Electronic Engineering, Tsinghua University<br>
    Building scalable simulation, sensing, and sim-to-real systems for robot learning.
  </p>
</div>

<p align="center">
  <a href="mailto:jyf23@mails.tsinghua.edu.cn"><img src="./assets/icon/email.png" height="24px" alt="Email"></a>&nbsp;
  <a href="./assets/my_wechat.jpg"><img src="./assets/icon/wechat.png" height="24px" alt="WeChat"></a>&nbsp;
  <a href="https://github.com/TATP-233"><img src="./assets/icon/github.png" height="24px" alt="GitHub"></a>&nbsp;
  <a href="https://scholar.google.com/citations?user=T7lpt7YAAAAJ&hl=en"><img src="./assets/icon/scholar.png" height="24px" alt="Google Scholar"></a>&nbsp;
</p>

---

I design and build high-throughput infrastructure for embodied intelligence: RL training frameworks, photorealistic robot simulators, GPU-accelerated sensor pipelines, real-sim-real evaluation workflows, and whole-body control systems that move research from algorithm prototypes toward deployable robot stacks.

I am a PhD student at Tsinghua University, advised in embodied AI and robot learning. I received my B.E. from the Department of Automation, Tsinghua University in 2023.

## Infrastructure Focus

- **High-throughput robot simulation:** scalable simulators for vision-informed robot learning, high-fidelity environments, and large-scale policy training.
- **Heterogeneous RL training systems:** decoupled CPU simulation, GPU learning, and runtime buffering for cross-platform embodied reinforcement learning.
- **GPU-accelerated perception infrastructure:** fast LiDAR and 3D Gaussian Splatting based sensing pipelines for simulation and evaluation.
- **Sim-to-real system design:** reusable bridges across simulators, robot assets, controllers, ROS2 interfaces, and deployment workflows.
- **Whole-body mobile manipulation:** loco-manipulation systems that combine control, perception, and reinforcement learning under real robot constraints.

## Research

### First / Co-first Author

- [**UniLab**] **UniLab: A Heterogeneous Architecture for Robot RL Beyond GPU-Dominant Paradigms**  
  [Webpage](https://unilabsim.github.io/) / [arXiv](https://arxiv.org/abs/2605.30313) / [Repo](https://github.com/unilabsim/UniLab) ![GitHub stars](https://img.shields.io/github/stars/unilabsim/UniLab?style=social)

- [**RSS 2026**] **GS-Playground: A High-Throughput Photorealistic Simulator for Vision-Informed Robot Learning**  
  [Webpage](https://gsplayground.github.io/) / [arXiv](https://arxiv.org/abs/2604.25459) / [Repo](https://github.com/discoverse-dev/gs_playground) ![GitHub stars](https://img.shields.io/github/stars/discoverse-dev/gs_playground?style=social)

- [**RAL 2026**] **ManiVID-3D: Generalizable View-Invariant Reinforcement Learning for Robotic Manipulation via Disentangled 3D Representations**  
  [Webpage](https://zheng-joe-lee.github.io/manivid3d/) / [arXiv](https://arxiv.org/abs/2509.11125)

- [**IROS 2025 Oral**] **DISCOVERSE: Efficient Robot Simulation in Complex High-Fidelity Environments**  
  [Webpage](https://air-discoverse.github.io/) / [arXiv](https://arxiv.org/abs/2507.21981) / [Repo](https://github.com/discoverse-dev/DISCOVERSE) ![GitHub stars](https://img.shields.io/github/stars/discoverse-dev/DISCOVERSE?style=social)

- **FGGS-LiDAR: Ultra-Fast, GPU-Accelerated Simulation from General 3DGS Models to LiDAR**  
  [arXiv](https://arxiv.org/abs/2509.17390) / [Repo](https://github.com/TATP-233/FGGS-LiDAR)

- **FILIC: Dual-Loop Force-Guided Imitation Learning with Impedance Torque Control for Contact-Rich Manipulation Tasks**  
  [arXiv](https://arxiv.org/abs/2509.17053) / [Repo](https://github.com/TATP-233/FILIC)

- [**IROS 2024 Oral**] **Arm-Constrained Curriculum Learning for Loco-Manipulation of a Wheel-Legged Robot**  
  [Webpage](https://acodedog.github.io/wheel-legged-loco-manipulation/) / [arXiv](https://arxiv.org/abs/2403.16535) / [Repo](https://github.com/aCodeDog/legged-robots-manipulation) ![GitHub stars](https://img.shields.io/github/stars/aCodeDog/legged-robots-manipulation?style=social)

- [**ICRA 2023 Poster**] **Designing the Whole-Body Controller for a Wheel-Legged Mobile Manipulator**  
  [Webpage](https://air.tsinghua.edu.cn/OpenARX6.htm)

### Co-author

- [**RSS 2026**] **HiWET: Hierarchical World-Frame End-Effector Tracking for Long-Horizon Humanoid Loco-Manipulation**  
  [arXiv](https://arxiv.org/abs/2602.06341)

- [**CoRL 2025 Oral**] **Omni-Perception: Omnidirectional Collision Avoidance for Legged Locomotion in Dynamic Environments**  
  [arXiv](https://arxiv.org/abs/2505.19214) / [Repo](https://github.com/aCodeDog/OmniPerception) ![GitHub stars](https://img.shields.io/github/stars/aCodeDog/OmniPerception?style=social)

- [**RAL 2025**] **Imit Diff: Semantics Guided Diffusion Transformer with Dual Resolution Fusion for Imitation Learning**  
  [arXiv](https://arxiv.org/abs/2502.09649)

- **A Real-Sim-Real Loop Framework for Generalizable Robotic Policy Transfer with Differentiable Simulation**  
  [arXiv](https://arxiv.org/abs/2503.10118)

## Open-source Projects

- [**MuJoCo-LiDAR**](https://github.com/discoverse-dev/MuJoCo-LiDAR): A high-performance LiDAR simulation tool for MuJoCo. ![GitHub stars](https://img.shields.io/github/stars/discoverse-dev/MuJoCo-LiDAR?style=social)

- [**urdf2mjcf**](https://github.com/discoverse-dev/urdf2mjcf): One-click generation of simulation-ready MJCF files from URDF. ![GitHub stars](https://img.shields.io/github/stars/discoverse-dev/urdf2mjcf?style=social)

- [**ROBOCON2026-MuJoCo**](https://github.com/discoverse-dev/ROBOCON2026): A MuJoCo simulation environment for ROBOCON 2026 with motion-control strategies, multi-sensor support, and ROS2 interfaces. ![GitHub stars](https://img.shields.io/github/stars/discoverse-dev/ROBOCON2026?style=social)

## Academic Service

- [**ICRA 2025 Sim2Real Challenge (S2R2025)**](http://sim2real.net/track/track?nav=S2R2025)  
  Organizer & Technical Support. A premier ICRA 2025 event focused on high-fidelity simulation and real-world robot deployment.

- [**RoboMaster 2024 University Sim2Real Challenge (RMUS 2024)**](http://sim2real.net/track/track/?nav=RMUS2024)  
  Organizer & Technical Support. Part of ICRA 2024, advancing sim-to-real robotics through autonomous ore-exchange tasks.
