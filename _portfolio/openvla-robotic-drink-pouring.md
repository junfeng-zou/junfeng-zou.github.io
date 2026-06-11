---
title: "LoRA-Fine-Tuned OpenVLA for Robotic Drink Pouring"
excerpt: "A real-world robotic drink-pouring system based on OpenVLA-7B and LoRA."
collection: portfolio
date: 2026-01-01
order: 5
---

This project explores how a vision-language-action model can be fine-tuned and deployed for real-world robotic drink pouring with closed-loop visual inference.

<div class="project-meta">
  <span><strong>Type</strong> Course Final Project, Robotic Manipulation, CUHK-Shenzhen</span>
  <span><strong>Period</strong> Jan 2026 - May 2026</span>
  <span><strong>Keywords</strong> VLA, OpenVLA, LoRA, Robotic Manipulation, Imitation Learning, Closed-loop Control</span>
</div>

<div class="project-vla-media">
  <figure class="project-video-frame project-vla-video">
    <div class="project-video-crop project-video-crop--uncropped project-video-crop--labeled">
      <span class="project-video-speed-label">6x speed</span>
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/pouring_vla.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <div class="project-vla-images">
    <figure class="project-video-frame">
      <img src="/files/projects/pouring_vla_system.png" alt="Robotic drink pouring system overview">
    </figure>
    <figure class="project-video-frame">
      <img src="/files/projects/pouring_vla_data.png" alt="Vision-language-action data collection and supervision overview">
    </figure>
  </div>
</div>

<div class="project-section-grid">
  <section>
    <h3>Problem</h3>
    <p>Deploying VLA models on physical robots requires connecting language instructions, visual observations, action prediction, and robot control into a closed-loop execution pipeline.</p>
  </section>
  <section>
    <h3>Approach</h3>
    <p>The system fine-tunes OpenVLA-7B with LoRA and maps predicted 7-DoF end-effector delta actions to robot arm and gripper commands for real-world drink-pouring execution.</p>
  </section>
</div>

<div class="project-result-row">
  <div>
    <strong>OpenVLA-7B</strong>
    <span>LoRA fine-tuning for robotic manipulation</span>
  </div>
  <div>
    <strong>7-DoF</strong>
    <span>End-effector delta action prediction</span>
  </div>
  <div>
    <strong>Closed-loop</strong>
    <span>Real-world inference from visual observations</span>
  </div>
</div>

**My Contributions**

* Built a real-world robotic drink-pouring VLA system based on OpenVLA-7B and LoRA.
* Designed a vision-language-action supervision pipeline for predicting 7-DoF end-effector delta actions from language instructions and visual observations.
* Deployed the VLA inference pipeline in a physical setup, denormalizing predicted 7-D actions and mapping them to robot arm and gripper control for closed-loop execution.
