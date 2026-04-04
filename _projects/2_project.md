---
layout: page
title: Franka Pick-and-Place
description: ROS 2 and MoveIt 2 manipulation pipeline for the Franka Panda robot, with Docker-based setup and pick-and-place simulation.
img: assets/img/project-franka-pickplace.gif
importance: 2
category: work
related_publications: false
---

This project implements a pick-and-place workflow for the Franka Panda robot using ROS 2, MoveIt 2, RViz, and a Docker-based development environment. It focuses on reproducible setup, motion planning, scene interaction, and gripper control for robotics experimentation.

The workflow includes adding collision objects, planning grasp and place motions, attaching and detaching the object in the planning scene, and validating the full sequence in simulation.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-franka-pickplace.gif" title="Franka pick-and-place demo" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Pick-and-place simulation with the Franka Panda robot.
</div>

Highlights:
- ROS 2 and MoveIt 2 manipulation workflow
- Docker-based robotics environment for reproducibility
- Planning-scene integration and object attachment logic
- Designed for extension toward perception-guided manipulation
