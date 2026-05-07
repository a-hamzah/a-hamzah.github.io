---
layout: page
title: Humanoid Robot for Reinforcement Learning
description: Design and development of a humanoid robot for reinforcement learning experiments
img: assets/img/project7/thumbnail.png
importance: 7
category: work
---

This project is about building a humanoid robot from simulation to hardware. The simulation is done in pybullet with a urdf designed in solidworks. Later, the 3d printed humanoid is built using bus servo motors, arduino and a custom servo board. The API provided by the Hiwonder is used to control motors and develop gait sequence.

**Hardware Architecture**

Processing Unit: Arduino with API provided by Hiwonder Servo Board

Motors: Hiwonder HTD-45H High Voltage Serial Bus Servo 45KG Torque with Three Connectors and Data Feedback

Robot: 3D printed humanoid after multiple design iterations in solidworks

**Software & Features**

Gait Generation using API

Joint limit settings

Pybullet environment + URDF creation and testing


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project7/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project7/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project7/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The screenshots are taken from the project.
</div>