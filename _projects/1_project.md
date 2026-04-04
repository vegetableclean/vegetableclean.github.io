---
layout: page
title: QCar TouchDrive
description: Mobile teleoperation for Quanser QCar with secure cross-network control, telemetry, and support for both physical QCar and QLabs.
img: assets/img/project-qcar-touchdrive.jpg
importance: 1
category: work
related_publications: false
---

QCar TouchDrive is a mobile teleoperation interface for the Quanser QCar platform. It connects a phone to a QCar host through a lightweight WebSocket interface, making remote driving practical for demos, testing, and lab use.

The system supports both the physical QCar and the QLabs virtual environment, with live telemetry, adjustable control parameters, and safety functions such as arm/disarm and emergency stop. It also supports secure cross-network access through Tailscale.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project-qcar-touchdrive.jpg" title="QCar TouchDrive mobile interface" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Mobile interface for QCar TouchDrive.
</div>

Highlights:
- Phone-based dual-joystick control for steering and throttle
- Works with both physical QCar and QLabs
- Live telemetry, control tuning, and CSV logging
- Secure remote access through Tailscale
