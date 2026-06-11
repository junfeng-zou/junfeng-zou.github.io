---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interests
======

My research focuses on robot planning and control, particularly the integration of model-based control and embodied learning for robust and reliable robotic manipulation, locomotion, and autonomous systems.

Education
======

* **The Chinese University of Hong Kong, Shenzhen**, Shenzhen, China
  * M.Phil. in Computer and Information Engineering, Sep 2025 - expected Jun 2027
  * Supervisor: Prof. Fangxun Zhong
  * Research Group: Intelligent Healthcare & Autonomous Robotics Lab

* **Northwestern Polytechnical University**, Xi'an, China
  * B.E. in Robotics, Sep 2021 - Jun 2025
  * GPA: 3.69/4.10
  * Thesis: Simulation and Analysis of Gait Planning Algorithms for Open-Source Humanoid Robots

Research Experience
======

* **Vision-Guided Robotic Nasal Endoscope Control and Safety Supervision System**, Jul 2025 - Present
  * Research Project, Intelligent Healthcare & Autonomous Robotics Lab, CUHK-Shenzhen
  * Developed a visual servoing system for robotic nasal endoscopy with Dobot CR5, integrating TCP/IP communication, ServoJ control, camera calibration, and real-time feature tracking.
  * Designed and validated a hierarchical MPC controller for IBVS under RCM constraints, achieving a mean image-plane tracking error of approximately 60 pixels while maintaining the RCM deviation below 1.6 mm.
  * Integrated joint and velocity constraints, Kalman filtering, and fault-tolerant feature handling; built endoscopic vision modules for instrument segmentation, distance-state estimation, and directional collision-risk assessment.

* **EtherCAT-Based Motor Control System for da Vinci Surgical Instruments**, Dec 2025 - Jun 2026
  * Engineering Project, Intelligent Healthcare & Autonomous Robotics Lab, CUHK-Shenzhen
  * Built a ROS 2, EtherCAT, and ros2_control-based multi-axis motor control framework for Denali XCR drives and MPK motors.
  * Implemented CiA 402 drive control, including fault reset, drive enabling, operation-mode switching, and position/velocity command execution.
  * Developed a motor debugging and monitoring interface for real-hardware testing, parameter tuning, and diagnosis.

* **Deep Reinforcement Learning-Based Locomotion Control for a Humanoid Robot**, Dec 2024 - Jun 2025
  * Undergraduate Thesis, Northwestern Polytechnical University
  * Built a GPU-parallel reinforcement learning environment in Isaac Gym and implemented an Actor-Critic PPO training pipeline for 12-DoF leg control.
  * Designed multi-objective reward functions for velocity tracking, posture stability, gait phase regulation, and joint motion, incorporating privileged observations, domain randomization, action noise, and random disturbances.
  * Trained and compared locomotion policies on flat, rough, sloped, and stair terrains, evaluating performance through base trajectories, velocity tracking, and walking stability.

* **Humanoid Robot Assembly and EtherCAT-Based Joint Actuation Integration**, Jul 2024 - Jan 2025
  * Visiting Research Project, Adaptive Robotic Controls Lab (ArcLab), The University of Hong Kong
  * Participated in mechanical assembly and electrical integration, including joint actuator installation, motor wiring, and system commissioning.
  * Developed and tested an EtherCAT-based multi-joint motor control system, covering slave configuration, drive enabling, cyclic communication, and synchronized motor operation.

Selected Projects
======

* **LoRA-Fine-Tuned OpenVLA for Robotic Drink Pouring**, Jan 2026 - May 2026
  * Final Project, Course: Robotic Manipulation, CUHK-Shenzhen
  * Built a real-world robotic drink-pouring VLA system based on OpenVLA-7B and LoRA.
  * Designed a vision-language-action supervision pipeline for predicting 7-DoF end-effector delta actions from language instructions and visual observations.
  * Deployed the VLA inference pipeline in a real physical setup, denormalizing predicted 7-D actions and mapping them to robot arm and gripper control for closed-loop execution.

* **Multi-Finger Dexterous Hand Assembly and Interactive Control System**, Jan 2026 - May 2026
  * Final Project, Course: Robotics and Intelligent Systems, CUHK-Shenzhen
  * Built the mechanical and electronic hardware system of a multi-finger dexterous hand, including servo installation, joint tuning, motion-range calibration, and basic pose testing.
  * Developed a control interface based on RP2350, serial communication, and Wi-Fi, converting finger-pose parameters into servo-angle commands for execution.
  * Implemented real-time gesture recognition with MediaPipe and OpenCV to detect rock, paper, and scissors gestures and control DexHand to perform corresponding game poses.

Publications
======

* C. Dong, Y. Bai, **J. Zou**, J. Cheng, Y. An, Z. Zhang, Z. Li, S. Lin, S. Zhao, and N. Li, "Flexible capacitive pressure sensor: material, structure, fabrication and application." *Nondestructive Testing and Evaluation*, 2024.
* Y. An, **J. Zou**, Y. Bai, C. Dong, J. Cheng, and N. Li, "Design and Testing of Flexible Pressure and Temperature Sensing Capacitive Sensors." *2024 IEEE International Instrumentation and Measurement Technology Conference (I2MTC)*, 2024.

Awards and Honors
======

* First Prize, Swarm Robot Task Competition, National Robot Championship, 2022
* First Prize, Semi-Autonomous Robot Soccer Competition, National Robot Championship, 2022
* Second Prize, China Marine Vehicle Design and Construction Contest, 2023
* Second Prize, HUAWEI CUP National Undergraduate IoT Design Contest, 2022

Technical Skills
======

* **Programming:** Python, C/C++, MATLAB, Linux
* **Robotics and Control:** ROS 2, EtherCAT, MPC, visual servoing, robot manipulation
* **Learning and Vision:** PyTorch, Isaac Gym/Sim, reinforcement learning, OpenCV, YOLO

Teaching
======

* **Teaching Assistant**, The Chinese University of Hong Kong, Shenzhen, Spring 2026
  * CSC1006: Artificial Intelligence for Science and Engineering
  * Conducted tutorial sessions, answered students' questions, proctored examinations, and graded exam papers.
