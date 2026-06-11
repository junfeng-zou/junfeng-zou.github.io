---
title: "Deep Reinforcement Learning-Based Locomotion Control for a Humanoid Robot"
excerpt: "A PPO-based locomotion control project for the open-source XBot-L humanoid robot in Isaac Gym."
collection: portfolio
date: 2024-12-01
order: 3
---

This project trains PPO-based locomotion policies for the open-source XBot-L humanoid robot, aiming to achieve stable walking across flat and complex terrains.

<div class="project-meta">
  <span><strong>Type</strong> Undergraduate Thesis, Northwestern Polytechnical University</span>
  <span><strong>Period</strong> Dec 2024 - Jun 2025</span>
  <span><strong>Keywords</strong> Humanoid Locomotion, Reinforcement Learning, PPO, Isaac Gym, Sim-to-Real</span>
</div>

<div class="project-video-grid">
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/humanoid_locomotion_vx06_rough.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/humanoid_locomotion_vy_neg03.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/humanoid_locomotion_angv03.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
</div>

<div class="project-section-grid">
  <section>
    <h3>Problem</h3>
    <p>Humanoid locomotion requires coordinated whole-body control under contact-rich dynamics, where hand-designed controllers can be difficult to tune across terrain variations and external disturbances.</p>
  </section>
  <section>
    <h3>Approach</h3>
    <p>The project formulates legged locomotion as a reinforcement learning problem and trains Actor-Critic PPO policies in a GPU-parallel Isaac Gym simulation environment.</p>
  </section>
</div>

<div class="project-result-row">
  <div>
    <strong>12-DoF</strong>
    <span>Leg control policy for XBot-L</span>
  </div>
  <div>
    <strong>Terrain set</strong>
    <span>Flat, rough, sloped, and stair terrains</span>
  </div>
  <div>
    <strong>Robustness</strong>
    <span>Domain randomization, noise, and random disturbances</span>
  </div>
</div>

**My Contributions**

* Built a GPU-parallel reinforcement learning environment in Isaac Gym and implemented an Actor-Critic PPO training pipeline for 12-DoF leg control.
* Designed multi-objective reward functions for velocity tracking, posture stability, gait phase regulation, and joint motion.
* Incorporated privileged observations, domain randomization, action noise, and random disturbances into policy training.
* Compared locomotion policies across flat, rough, sloped, and stair terrains using base trajectories, velocity tracking, and walking stability.
