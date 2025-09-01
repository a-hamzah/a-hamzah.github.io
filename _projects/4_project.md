---
layout: page
title: Obstacle Avoidance Using E-Puck in Webots Simulator
description: Implementation of a basic obstacle avoidance algorithm using proximty sensors
img: assets/img/project4/1.png
importance: 4
category: fun
---

The e-puck robot is a small, differential-wheeled mobile robot designed for education and research in robotics. It is equipped with various sensors, including proximity sensors, cameras, and accelerometers, making it suitable for tasks like obstacle avoidance, line following, and swarm robotics. This robot is a complete package for the developers with a lot of sensors and libraries to get into robotics.

In this project, the obstacle avoidance behavior is achieved by reading the IR sensors and adjusting motor speeds accordingly. If an obstacle is detected, the robot turns away from it and continues moving forward once the path is clear. In this project, only four proximity sensors are used ps0, ps1, ps6 and ps7.

The screenshots from the project can be seen below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project4/1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project4/2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project4/3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

