---
layout: page
title: Game Theory based Control Method for Multi-Agent Systems
description: Master Thesis
img: assets/img/project_1_1.jpg
importance: 1
category: Research

---

__Aims:__ explore in depth the interactions among agents in a multi-agent system, and then to design controllers by combining data-driven approach, game theory and formation control method, enhancing the capability of multi-agent systems.

__Objects:__ Tethered Space Net Robot (TSNR)
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_1_1.jpg" title="example image" class="rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Configuration of TSNR.
</div>

__Problems:__
* Target is non-cooperation, and there is  a need to plan a capture trajectory.
* The system is underactuated and constrained, satellites impact each other through the net.

__Contribution:__
* Developed a pursuit-evasion game to obtain the trajectory of the multi-agent system in the face of a dynamic target, and designed a robust adaptive control with artificial potential field to minimize tracking errors and maintain specific configurations.
* Proposed a novel formation control scheme that integrates data-driven approaches for modeling agent interactions and cooperative game frameworks for controlling satellites based on their coupled relationship.
* Published one journal article and one conference article by applying the proposed algorithm to tethered space net robot, and wrote a grant proposal by extending the proposed algorithm to satellite cluster.

