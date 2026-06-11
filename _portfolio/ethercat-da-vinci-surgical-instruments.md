---
title: "EtherCAT-Based Motor Control System for da Vinci Surgical Instruments"
excerpt: "A ROS 2 and EtherCAT-based low-level actuation framework for Denali XCR drives, MPK motors, and surgical instrument motion control."
collection: portfolio
date: 2025-12-01
order: 2
---

This project builds a real-time low-level actuation framework for da Vinci surgical instrument motion control using ROS 2, EtherCAT, Denali XCR drives, and MPK motors.

<div class="project-meta">
  <span><strong>Type</strong> Engineering Project, IHAR Lab, CUHK-Shenzhen</span>
  <span><strong>Period</strong> Dec 2025 - Jun 2026</span>
  <span><strong>Keywords</strong> Surgical Robotics, EtherCAT, ROS 2, ros2_control, CiA 402, Motor Control</span>
</div>

<div class="project-video-grid project-video-grid--two">
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata" poster="/files/projects/ethercat_drive_poster.jpg">
        <source src="/files/projects/ethercat_drive.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata" poster="/files/projects/ethercat_drive_instrument_poster.jpg">
        <source src="/files/projects/ethercat_drive_instrument.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
</div>

<div class="project-section-grid">
  <section>
    <h3>Problem</h3>
    <p>Surgical instruments require reliable low-level actuation, precise motor command execution, and real-time hardware feedback before higher-level autonomy or teleoperation modules can be safely integrated.</p>
  </section>
  <section>
    <h3>Approach</h3>
    <p>The system uses EtherCAT as the real-time communication layer and ROS 2 as the software integration layer, exposing multi-axis motor control through a modular ros2_control-based framework.</p>
  </section>
</div>

<div class="project-result-row">
  <div>
    <strong>ROS 2 + EtherCAT</strong>
    <span>Integrated multi-axis control framework</span>
  </div>
  <div>
    <strong>CiA 402</strong>
    <span>Drive state control and command execution</span>
  </div>
  <div>
    <strong>Real hardware</strong>
    <span>Debugging, monitoring, and parameter tuning interface</span>
  </div>
</div>

**My Contributions**

* Built a ROS 2, EtherCAT, and ros2_control-based multi-axis motor control framework for Denali XCR drives and MPK motors.
* Implemented CiA 402 drive control, including fault reset, drive enabling, operation-mode switching, and position/velocity command execution.
* Developed a motor debugging and monitoring interface for real-hardware testing, parameter tuning, and diagnosis.
