---
title: "Multi-Finger Dexterous Hand Assembly and Interactive Control System"
excerpt: "A dexterous hand assembly and gesture-interaction system based on DexHand hardware, RP2350 control, MediaPipe, and OpenCV."
collection: portfolio
date: 2026-01-01
order: 6
---

This project builds a multi-finger dexterous hand and an interactive gesture-control system based on the open-source DexHand hardware design.

<div class="project-meta">
  <span><strong>Type</strong> Course Final Project, Robotics and Intelligent Systems, CUHK-Shenzhen</span>
  <span><strong>Period</strong> Jan 2026 - May 2026</span>
  <span><strong>Keywords</strong> Dexterous Hand, Hardware Assembly, RP2350, MediaPipe, OpenCV, Interactive Control</span>
</div>

<div class="project-video-grid project-video-grid--two">
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <video autoplay loop muted playsinline preload="metadata">
        <source src="/files/projects/dexhand.mp4" type="video/mp4">
      </video>
    </div>
  </figure>
  <figure class="project-video-frame">
    <div class="project-video-crop project-video-crop--uncropped">
      <img src="/files/projects/dexhand.png" alt="DexHand hardware assembly">
    </div>
  </figure>
</div>

<div class="project-section-grid">
  <section>
    <h3>Problem</h3>
    <p>Dexterous hand systems require coordinated mechanical assembly, servo calibration, embedded communication, and perception-driven control before they can perform interactive gestures reliably.</p>
  </section>
  <section>
    <h3>Approach</h3>
    <p>The system combines DexHand hardware assembly, RP2350-based servo control, serial/Wi-Fi communication, and real-time hand gesture recognition using MediaPipe and OpenCV.</p>
  </section>
</div>

<div class="project-result-row">
  <div>
    <strong>DexHand</strong>
    <span>Mechanical and electronic hardware assembly</span>
  </div>
  <div>
    <strong>RP2350</strong>
    <span>Finger-pose to servo-angle control interface</span>
  </div>
  <div>
    <strong>Real-time</strong>
    <span>Gesture recognition and interactive pose execution</span>
  </div>
</div>

**My Contributions**

* Built the mechanical and electronic hardware system of a multi-finger dexterous hand, including servo installation, joint tuning, motion-range calibration, and basic pose testing.
* Developed a control interface based on RP2350, serial communication, and Wi-Fi, converting finger-pose parameters into servo-angle commands.
* Implemented real-time gesture recognition with MediaPipe and OpenCV to detect rock, paper, and scissors gestures and control DexHand to perform corresponding game poses.
