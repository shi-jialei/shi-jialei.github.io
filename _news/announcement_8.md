---
layout: post
title: Work on model-based force control of soft continumm robots is accepted by Journal of Soft Robotics (SoRo)!
date: 2025-11-18 16:11:00-0400
inline: false
related_posts: false
---

This work advances the model-based, (quasi-)static force control techniques for pneumatic-driven soft continuum robots. {Specifically, our approach builds on a compliance model. To achieve the force control, we can obtain the compliance matrix under a certain robot configuration determined using the Cosserat rod model. Using this compliance matrix and the desired force, we calculate the target deflection, which in turn defines the new robot configuration. The actuation pressure required to achieve this configuration is then obtained by solving the inverse kinematics of the Cosserat rod model, which we implement using a shooting method.} The effectiveness of the proposed method is experimentally validated using one- and two-segment soft robots, demonstrating satisfactory force control accuracy. For example, mean force errors are below 5% of the desired peak forces.

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    <img class="img-fluid rounded z-depth-1" src="/assets/img/architecture_SoRo.jpg" alt="Overview of force control architecture" data-zoomable>
  </div>
</div>


And check out the [Supplementary Video](https://www.youtube.com/watch?v=-TFpsLYlU_c&t=2s):
<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/-TFpsLYlU_c" allowfullscreen></iframe>
</div>
