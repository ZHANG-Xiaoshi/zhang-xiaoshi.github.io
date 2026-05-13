---
permalink: /
title: "Robotic Tactile Intelligence"
excerpt: "Multimodal tactile sensing, real-time prediction, and dexterous robotic manipulation."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="zxs-hero">
  <p class="zxs-kicker">Robotic Tactile Intelligence</p>
  <h1>Xiaoshi Zhang builds tactile perception systems for robots that need to feel, predict, and act in contact-rich environments.</h1>
  <p class="zxs-lead">My work combines bio-inspired tactile sensor hardware, force-vision fusion, physics-guided learning, and real-time robot control. I am especially interested in dexterous manipulation systems that close the loop between tactile perception and action.</p>
  <div class="zxs-actions">
    <a class="btn btn--primary" href="{{ '/projects/' | relative_url }}">Selected Projects</a>
    <a class="btn" href="{{ '/publications/' | relative_url }}">Work Highlights</a>
    <a class="btn" href="{{ '/cv/' | relative_url }}">CV</a>
  </div>
</section>

<section class="zxs-metrics" aria-label="Research highlights">
  <div><strong>2.98 ms</strong><span>real-time tactile prediction latency</span></div>
  <div><strong>300 Hz</strong><span>force-tactile tracking for cable following</span></div>
  <div><strong>0.019 mm</strong><span>dual-press thickness estimation MAE</span></div>
  <div><strong>99.25%</strong><span>hybrid tactile material classification</span></div>
</section>

<h2 id="research">Research Vision</h2>

I study how robots can use touch as an active, high-bandwidth sense for manipulation. Vision-based tactile sensors capture rich contact geometry but often run too slowly for fast contact transitions; electronic force arrays respond quickly but are spatially sparse. My research direction is to make these modalities work together: sensing hardware that co-locates complementary signals, learning systems that fuse them causally, and controllers that can use tactile feedback in real time.

My current research agenda is organized around three questions:

- **Multimodal tactile sensing:** how can robotic fingertips combine high-resolution visual-tactile images with high-frequency distributed force feedback?
- **Real-time tactile prediction:** how can fast force signals help predict dense future tactile states before the next camera frame arrives?
- **Robust tactile deployment:** how can physically meaningful signals, such as thickness and compliance, make tactile classifiers survive the offline-to-live gap?

<div class="zxs-project-grid">
  <article class="zxs-card">
    <h3>HyTouch: Bio-inspired Hybrid Tactile Sensor</h3>
    <p>A co-located visual-tactile and force-tactile sensor designed to address the tactile trilemma: high spatial resolution, high temporal response, and distributed force sensing.</p>
    <p class="zxs-tags">Sensor hardware / multimodal fusion / robotic manipulation</p>
    <a href="{{ '/projects/#hytouch' | relative_url }}">Read project</a>
  </article>
  <article class="zxs-card">
    <h3>GelXelaCrossAttn: Real-Time Tactile State Prediction</h3>
    <p>A lightweight force-vision cross-attention model that predicts the next GelSight frame from XELA force readings with sub-10 ms inference.</p>
    <p class="zxs-tags">Cross-attention / force-vision fusion / real-time inference</p>
    <a href="{{ '/projects/#gelxela' | relative_url }}">Read project</a>
  </article>
  <article class="zxs-card">
    <h3>Thickness-Routed Tactile Mixture-of-Experts</h3>
    <p>A two-stage force-tactile pipeline for robust sheet-material identification under live deployment domain shift.</p>
    <p class="zxs-tags">GelSight / force control / mixture-of-experts</p>
    <a href="{{ '/projects/#material-moe' | relative_url }}">Read project</a>
  </article>
</div>

<h2>Technical Identity</h2>

I like research problems where the answer cannot live in only one layer of the stack. A useful tactile system needs a sensor that can produce the right signals, a robot procedure that collects clean and repeatable data, a learning model that respects latency and physics, and an evaluation protocol that measures what matters for control rather than only pixel similarity.

That is the technical spirit I want this site to communicate: tactile sensing as a complete robotic intelligence problem, from contact physics to deployable systems.

<h2>News</h2>

- **2026:** Developed a physics-informed force-vision model for real-time tactile frame prediction in cable manipulation.
- **2026:** Built a dual-press tactile material identification pipeline with thickness-routed expert classifiers for manufacturing sheet materials.
- **2026:** Advanced HyTouch, a bio-inspired multimodal tactile sensor for high-resolution and high-frequency robotic perception.
- **2023:** Completed M.Sc. studies in Mechanical Engineering at the National University of Singapore and continued research on tactile-based dexterous manipulation.
