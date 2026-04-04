---
layout: page
title: QCar TouchDrive
description: A side project that improves QCar experimentation through mobile teleoperation, telemetry, and support for both physical QCar and QLabs.
img: assets/img/project-qcar-touchdrive.jpg
importance: 1
category: work
related_publications: false
---

QCar TouchDrive is a side project built to support QCar experiments through a simple mobile teleoperation interface. It connects a phone to a QCar host through a lightweight WebSocket interface, making remote driving more practical for demos, testing, and experimental workflows.

The system supports both the physical QCar and the QLabs virtual environment, with live telemetry, adjustable control parameters, and safety functions such as arm/disarm and emergency stop. It also supports secure cross-network access through Tailscale.

<div class="row">
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-qcar-touchdrive.jpg" title="QCar TouchDrive mobile interface" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-qcar-qlab.jpg" title="QCar TouchDrive with QLabs" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-qcar-tailscale.jpg" title="QCar TouchDrive with Tailscale" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  QCar TouchDrive mobile interface, QLabs setup, and secure networking through Tailscale.
</div>

Highlights:
- Phone-based dual-joystick control for steering and throttle
- Works with both physical QCar and QLabs
- Live telemetry, control tuning, and CSV logging
- Secure remote access through Tailscale
