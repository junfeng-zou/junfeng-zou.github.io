---
title: "Vision-Guided Robotic Nasal Endoscope Control and Safety Supervision System"
excerpt: "A robot-assisted nasal endoscopy system for stable surgical view control, RCM-constrained visual servoing, and real-time safety supervision."
collection: portfolio
date: 2025-07-01
order: 1
---

This project develops a vision-guided robotic nasal endoscope control system to help surgeons maintain a stable and safe surgical view during long procedures.

<div class="project-meta">
  <span><strong>Type</strong> Research Project, IHAR Lab, CUHK-Shenzhen</span>
  <span><strong>Period</strong> Jul 2025 - Present</span>
  <span><strong>Keywords</strong> Surgical Robotics, Visual Servoing, MPC, RCM Constraint, Endoscopic Vision</span>
</div>

<div class="project-video-grid">
  <figure class="project-video-frame">
    <div class="project-video-crop">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/endoscope_control.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--robot">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/endoscope_robotcontrol.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/maskaware_camera.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
</div>

<div class="project-section-grid">
  <section>
    <h3>Problem</h3>
    <p>During long nasal surgery procedures, surgeons need to maintain a stable endoscopic view while avoiding unsafe instrument motion near delicate anatomy. Manual endoscope handling can increase workload and make consistent view control difficult.</p>
  </section>
  <section>
    <h3>Approach</h3>
    <p>The system combines robotic endoscope manipulation, image-based visual servoing, RCM-constrained MPC, and endoscopic safety perception to support stable and constrained camera motion.</p>
  </section>
</div>

<div class="project-result-row">
  <div>
    <strong>&lt;1.6 mm</strong>
    <span>RCM deviation during control</span>
  </div>
  <div>
    <strong>Real-time</strong>
    <span>Feature tracking and safety-state estimation</span>
  </div>
</div>

**My Contributions**

* Built a Dobot CR5-based robotic nasal endoscopy platform with TCP/IP communication, ServoJ control, camera calibration, and real-time feature tracking.
* Designed and validated a hierarchical MPC controller for image-based visual servoing under RCM constraints.
* Integrated joint and velocity constraints, Kalman filtering, and fault-tolerant feature handling into the control pipeline.
* Developed endoscopic vision modules for instrument segmentation, distance-state estimation, and directional collision-risk assessment.
