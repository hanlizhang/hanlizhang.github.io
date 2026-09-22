---
layout: page
title: Drag-Aware Trajectory Generation for Quadrotor Systems
description: Learned drag-aware trajectory planning with Crazyflie sim-to-real validation.
img: assets/img/quad_lcd_demo.jpg
importance: 1
category: work
github: https://github.com/hanlizhang/AeroWrenchPlanner
related_publications: 
---

Trained a 3-layer MLP on 200,000 simulated trajectories to learn a drag-aware tracking-cost model, then integrated it into trajectory optimization with an SE(3) controller. The system achieved 83% lower tracking error and a 49% lower crash rate in simulation, with successful Crazyflie hardware flights.

[Video](/assets/video/quad_lcd_demo_web.mp4) · [Repository](https://github.com/hanlizhang/AeroWrenchPlanner) ·
[Paper](https://arxiv.org/abs/2505.10228)
