---
layout: page
title: Robot Path Planning & Digital Twins
description: Comparing classical and machine learning approaches to autonomous navigation in simulated environments
img: assets/img/robot_pathfinding.gif
importance: 3
category: research
related_publications: true
---

## Overview

This project investigates the effectiveness of different path planning algorithms for autonomous robots, comparing traditional methods like Hybrid A* and D* Lite with modern reinforcement learning approaches using deep neural networks.

### Research Objectives

1. **Digital Twin Development**: Create accurate virtual representations of physical environments (e.g., Shelby Hall) for testing and validation
2. **Algorithm Comparison**: Evaluate performance metrics including path efficiency, computation time, and robustness
3. **Sim-to-Real Transfer**: Validate simulation results on physical robot platforms

### Path Planning Methods

#### Classical Approaches

- **Hybrid A\***: Combines traditional A\* with continuous space planning
- **D\* Lite**: Incremental heuristic search for dynamic environments

#### Machine Learning Methods

- **Proximal Policy Optimization (PPO)**: Deep reinforcement learning for end-to-end navigation
- **Deep Q-Networks (DQN)**: Value-based learning for discrete action spaces

### Testbed Platforms

- **Simulation**: Unity 3D with ROS integration
- **Hardware**: Clearpath Jackal UGV (Unmanned Ground Vehicle)
- **Sensors**: LiDAR, cameras, IMU, wheel encoders

### Applications

This research has implications for:

- Indoor autonomous navigation
- Warehouse and logistics automation
- Search and rescue robotics
- Smart campus and building systems

### Student Research

- **Miguel Gapud** (Undergraduate Honors Thesis, completed 2025) — "A Comparison of Robot Path Planning Algorithms" comparing Hybrid A*, D* Lite, and PPO in simulation and physical environments
- Published: Gapud, Clark, McDonald, Gong — "Classical vs. End-to-End Learning Approaches to Robot Pathfinding in Digital Twin Environments" at IEEE CARS 2025 ([IEEE Xplore](https://ieeexplore.ieee.org/document/11337622))

### Outcomes

The digital twin of Shelby Hall and the Clearpath Jackal UGV testbed developed during this project continue to support ongoing robotics research in the School of Computing, including security-focused experiments with adversarial navigation attacks.

---

_This work demonstrates the practical application of both classical computer science algorithms and modern AI techniques to real-world robotics challenges._
