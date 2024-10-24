---
layout: page
title: Motion Planning and Control for Multi-UAV Cooperative Transportation
description: Bachelor Thesis
img: assets/img/project_2_1.jpg
importance: 1
category: Research

---

__Apr, 2020 - Sep, 2022__

__Aims:__ Design motion planning approaches and formation control schemes for multiple UAVs, enabling them to collaborate in transporting payloads via tethers.

__Objects:__ Multi-UAV Cooperative Transportaion System
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_2_2.jpg" title="example image" class="rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Configuration of Multi-UAV Cooperative Transportaion System.
</div>

__Problems:__
* Constraints among UAVs and among UAVs and payload exist, which led to the need to maintain a configuration for transportation.
* Offline algorithms cost long time and have low efficiency, and need to avoid obstacles in dynamic environments


__Contribution:__
* Investigated system dynamics model to reduce planning variables and expand the motion range of each UAV, then proposed a novel path planning algorithm to obtain smooth, collision-avoidance trajectories of UAVs for cooperative transportation.
* Examined reinforcement learning based path planning scheme as a local planner to handle dynamic environmental changes, and proposed an intelligent fault-tolerant control algorithm based on deep deterministic policy gradient algorithm to address the case of actuator failure.

