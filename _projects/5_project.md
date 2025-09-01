---
layout: page
title: Clover Quadcopter Auto Flight Test in ROS+Gazebo
description: This projects is all about using the autoflight test of Clover Drone.
img: assets/img/project5/1.jpg
importance: 5
category: fun
---

In this experiment, I worked with the Coex Clover platform—an educational quadcopter that runs on ROS and provides both real hardware and simulation support. The goal of the experiment was to test autonomous flight using the Gazebo simulation environment.

**Tools and Setup**

Robot Platform: Coex Clover (ROS-based quadcopter)

Simulation Environment: Gazebo, which provides a 3D physics-based environment for UAV testing.

ROS Packages: Clover simulation stack including flight control and visualization nodes.

Flight Controller (simulated): PX4 autopilot integrated with the ROS–Gazebo simulation.

**Experiment Procedure**

- Simulation Launch
The Clover quadcopter model was launched in Gazebo with its standard simulation world. This provided access to realistic physics, sensors, and flight dynamics.

- Autonomous Flight Test Node
I executed the auto flight test node, which sends pre-programmed waypoints and commands to the quadcopter. The node interacts with the ROS flight stack, simulating real-world autonomous flight missions such as takeoff, waypoint navigation, hovering, and landing.

- ROS–Gazebo Interaction
The quadcopter’s motion and sensor feedback were visualized in Gazebo, while ROS topics and services provided live data exchange between the autopilot, mission planner, and simulation environment.

**Results and Observations**

The quadcopter successfully executed an autonomous flight mission following the commands from the test node.

The simulation validated the interaction between ROS nodes, PX4 flight control, and Gazebo physics.

The experiment demonstrated how Clover can be used as a learning platform for UAV autonomy, mission scripting, and ROS-based control.

The screenshots from the project can be seen below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project5/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project5/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project5/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshots are taken from the project.
</div>

<div class="row mt-4">
  <div class="col-12"> <!-- full width column -->
    <div class="ratio ratio-16x9"> <!-- responsive video -->
      <iframe 
        src="https://www.youtube.com/embed/POXzgDMQpYY?si=UIsLAawKYhBeSQf6"
        title="YouTube video player"
        class="rounded z-depth-1 w-100 h-100"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>
  </div>
</div>
<div class="caption">
  Demo video of the project.
</div>