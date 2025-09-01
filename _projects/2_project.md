---
layout: page
title: Differential Drive Robot with ROS2 Humble
description: The project uses ROS framework to move to a certain point in a factory world.
img: assets/img/project2/3.jpg
importance: 2
category: work
giscus_comments: false
---

This project features a differential drive mobile robot designed for autonomous navigation in a factory environment. The robot integrates hardware and software components to perform simultaneous localization and mapping (SLAM), path planning, and location marking through a user-friendly graphical interface.

**DEMO VIDEO**: [link](https://youtube.com/shorts/JdMqxrvbp4E?si=1pgK94r7AsijVztX)

**Hardware Architecture**

Processing Unit: Raspberry Pi 4 (RPI4) running ROS2 Humble as the main controller for high-level decision-making, SLAM, and navigation stack.

Microcontroller: Arduino Nano for real-time low-level motor control and sensor interfacing.

Motor Driver: L298N dual H-bridge motor driver to drive the two DC motors of the differential drive system.

Display & GUI: LCD panel powered by a PyQt5 GUI, allowing operators to interact with the robot and mark specific locations in the factory layout.

**Software & Features**

ROS2 Humble Integration: Manages communication between sensors, actuators, and high-level navigation nodes.

SLAM: The robot autonomously builds and updates a map of the factory environment while localizing itself within it.

Path Planning: Given a marked goal, the ROS2 navigation stack computes an optimal collision-free path and commands the robot to reach it.

**GUI Interface (PyQt5):**

Visualizes the current map and robot position.

Allows operators to mark or log the robot’s current location for tracking important factory points.

Provides manual control and monitoring options.

**Use Case in Factory Environment**

The robot can be deployed in an industrial setting for:

Navigating between stations, storage areas, or workbenches.

Automatically reaching marked goals such as material pickup/drop-off points.

Assisting in intralogistics tasks by combining mapping, location marking, and autonomous path planning.

This system demonstrates the integration of affordable hardware with ROS2-based autonomy, providing a scalable solution for smart factory applications.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The screenshots are taken from the project.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Circuit.
</div>

A few more screenshots.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A picture from project.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project2/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A picture from project.
</div>