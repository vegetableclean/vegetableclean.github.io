---
layout: page
title: Franka Pick-and-Place
description: ROS 2 and MoveIt 2 workflow for a Franka robotic arm, covering Docker-based setup, simulation, and real-robot deployment.
img: assets/img/project-franka-pickplace.gif
importance: 2
category: work
related_publications: false
---

This project was developed in collaboration with Dr. Azimi's lab at the University of Arizona as a simple Franka robotic-arm demo workflow using ROS 2, MoveIt 2, RViz, and a Docker-based development environment.

The project includes pick-and-place simulation as well as a basic real-robot workflow for Franka-based experiments.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-franka-pickplace.gif" title="Franka pick-and-place demo" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Franka robotic-arm pick-and-place demo.
</div>

<div class="row">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/franka-pick-cup.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/franka-sim-to-real.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
</div>
<div class="caption">
  Additional Franka demos: pick-cup execution and sim-to-real workflow.
</div>

Highlights:
- ROS 2 and MoveIt 2 workflow for simulation and real robot
- Docker-based robotics environment for reproducibility
- Planning-scene integration and object attachment logic
- Designed for extension toward perception-guided manipulation
