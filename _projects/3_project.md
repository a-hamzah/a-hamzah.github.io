---
layout: page
title: Human Following Cargo Robot
description: The cargo trolly follows a human (a worker)
img: assets/img/project3/1.jpg
importance: 3
category: work
giscus_comments: false
---

This robot is a human following robot. The node `dolly_follow` uses the lidar data to detect the human in its range. It keeps a certain distance from a human. Once that distance increases, the robot starts moving towards the human. It also keeps a check on direction in which a human is moving.
It is a simulated project that uses ROS and Gazebo. The demo video is available on youtube.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project3/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project3/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project3/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row mt-4">
  <div class="col-12"> <!-- full width column -->
    <div class="ratio ratio-16x9"> <!-- responsive video -->
      <iframe 
        src="https://www.youtube.com/embed/1g2Ui9Cd5o0?si=9fw2O3JDpLLCHH6N"
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
