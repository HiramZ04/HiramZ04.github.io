---
layout: page
title: Navi — Assistive Navigation for the Blind
description: Real-time perception-to-voice navigation aid combining YOLO, LiDAR, VLM, and LLM. HackMerced XI (UC Merced).
img: assets/img/navi1.jpeg
importance: 2
category: hackathon
related_publications: false
images:
  - path: assets/img/navi1.jpeg
    title: Presenting Navi at HackMerced XI — Major League Hacking
  - path: assets/img/navi2.jpeg
    title: Navi robot with Gazebo LiDAR simulation running
  - path: assets/img/navi3.jpg
    title: The Navi robot — camera, LiDAR, and onboard compute
  - path: assets/img/navi4.jpeg
    title: Team at UC Merced
---

An assistive-robotics prototype for blind and visually impaired users, combining YOLO object detection, LiDAR ranging, a vision-language model for scene description, and an LLM for voice question-answering. I designed the low-latency inference pipeline end to end. Built at **HackMerced XI** (UC Merced) — Major League Hacking.

{% include figure.liquid loading="eager" path="assets/img/navi1.jpeg" class="img-fluid rounded z-depth-1" zoomable=true %}

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/navi2.jpeg" title="Gazebo simulation" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/navi3.jpg" title="The robot" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/navi4.jpeg" title="Team at UC Merced" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

**Stack:** YOLO, LiDAR, VLMs, LLMs, ROS, Gazebo, real-time inference.

[Live site](https://hack-merced-4iq2.vercel.app/) · [Code on GitHub](https://github.com/HiramZ04/HackMerced)
