---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /proj/
  - /project/
  - /project.html
---

The projects below are selected to show the full tactile robotics stack I work on: sensor design, force-controlled data collection, real-time learning, and deployment-oriented evaluation.

<section class="zxs-project-detail" id="hytouch">
  <img src="{{ '/images/research/hytouch-overview.png' | relative_url }}" alt="HyTouch overview">
  <div>
    <p class="zxs-kicker">Multimodal Tactile Sensor Hardware</p>
    <h2>HyTouch: A Bio-inspired Hybrid Multimodal Tactile Sensor</h2>
    <p>HyTouch integrates a high-resolution visual-tactile layer with a high-frequency distributed force-tactile layer. The project targets the tactile trilemma: robots need fine contact geometry, fast dynamic response, and spatially distributed force feedback in one fingertip.</p>
    <ul>
      <li>Designed a co-located and decoupled visual-tactile plus force-tactile architecture inspired by human skin receptors.</li>
      <li>Built optical and signal-processing pipelines to reduce inter-modality interference, including image stitching and calibration.</li>
      <li>Validated the prototype on high-speed cable following and tool-mediated material classification.</li>
    </ul>
    <p class="zxs-tags">300 Hz tracking / 24 cm/s cable following / 99.25% hybrid classification</p>
    <p><a class="btn" href="{{ '/files/hytouch-tactile-sensor.pdf' | relative_url }}">PDF</a></p>
  </div>
</section>

<section class="zxs-project-detail" id="gelxela">
  <img src="{{ '/images/research/gelxela-overview.png' | relative_url }}" alt="GelXelaCrossAttn overview">
  <div>
    <p class="zxs-kicker">Real-Time Tactile Prediction</p>
    <h2>GelXelaCrossAttn: Physics-Informed Cross-Modal Force-Vision Attention</h2>
    <p>This work addresses a multi-rate sensing gap: GelSight provides dense tactile images at around 18 Hz, while XELA force arrays provide force readings at 100 Hz. The model uses current tactile images and fast force dynamics to predict the next tactile image before the camera catches up.</p>
    <ul>
      <li>Introduced a lightweight cross-attention model where image patches query force tokens derived from XELA taxel readings.</li>
      <li>Added a physics-informed prediction head that separates dense gel deformation from illumination residuals.</li>
      <li>Benchmarked CNN, STN, UNet, CVAE, copy-previous, and attention variants under a shared real-time latency budget.</li>
    </ul>
    <p class="zxs-tags">2.98 ms latency / 36.67 dB PSNR / 0.941 SSIM / 0.83M parameters</p>
    <p><a class="btn" href="{{ '/files/gelxela-cross-attention.pdf' | relative_url }}">PDF</a></p>
  </div>
</section>

<section class="zxs-project-detail" id="material-moe">
  <img src="{{ '/images/research/material-moe-overview.png' | relative_url }}" alt="Tactile material identification overview">
  <div>
    <p class="zxs-kicker">Robust Tactile Deployment</p>
    <h2>Robust Sheet-Material Identification via Dual-Press Thickness Estimation and Tactile MoE</h2>
    <p>This project tackles the offline-to-live gap in tactile material classification. Instead of relying only on image appearance, the system first estimates material thickness through a force-controlled dual-press protocol, then routes each sample to a specialized tactile classifier.</p>
    <ul>
      <li>Implemented compliance-compensated thickness estimation using matched force waypoints from reference and test presses.</li>
      <li>Built a thickness-routed Mixture-of-Experts with EfficientNet-B0 experts for thin, medium, and thick material bands.</li>
      <li>Developed live robot acquisition and inference tooling, including a Streamlit operator interface.</li>
    </ul>
    <p class="zxs-tags">0.019 mm thickness MAE / 86.9% Top-1 / 94.9% coverage / Material I recovered from 0% to 96.4%</p>
    <p><a class="btn" href="{{ '/files/tactile-material-moe.pdf' | relative_url }}">PDF</a></p>
  </div>
</section>

<h2>Earlier Robotics and Learning Work</h2>

- **Tensegrity snake-like robot:** modeled a cable-driven tensegrity snake robot and studied inverse kinematics based on the serpenoid curve.
- **Deep reinforcement learning for double inverted pendulum control:** studied DDPG and TD3 for stabilization, swing-up, and rotating control tasks.
- **Legged robot learning:** explored reinforcement learning, privileged training, and locomotion policy design during earlier robotics research.
