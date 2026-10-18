---
layout: page
title: Biomechatronic Modelling and Control
description: Physics-based modelling and model-based control of compliant and deformable robotic systems
img: assets/img/soft-robot-cover.jpg
importance: 1
category: work
project: soft-continuum-robot
related_publications: false
---

Soft and compliant robotic systems exhibit highly nonlinear and configuration-dependent behaviour, making conventional rigid-body modelling and control methods difficult to apply. My research develops **physics-based and reduced-order modelling frameworks** to understand, predict and control these systems, with particular emphasis on robot kinematics, mechanics, stiffness and compliance.

These models provide a quantitative link between **mechanical design, actuation and robot behaviour**, enabling model-based design, state prediction and control. They form the fundamental mechanics basis for much of my subsequent research in adaptive physical interaction and biomedical robotics.

---

## Kinematics, Mechanics and Stiffness Modelling

Accurate mechanical models are essential for understanding how soft continuum robots deform under actuation and external loading. I developed analytical modelling frameworks for fibre-reinforced pneumatic continuum robots, drawing on **continuum mechanics, Cosserat-rod formulations and Lie-theoretic stiffness analysis**.

The models capture several important nonlinear effects, including:

- large deformation of compliant structures;
- material hyperelasticity;
- cross-sectional deformation during elongation;
- configuration-dependent mechanical stiffness;
- coupling between robot geometry, actuation and structural behaviour.

These frameworks allow the robot configuration and mechanical response to be predicted from design parameters and applied pressure, providing a basis for analysing **kinematics, stiffness, compliance and force-generation capability** without relying solely on empirical characterisation.

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
       loading="eager"
       path="assets/img/fig1_compliance.png"
       title="Configuration-dependent stiffness modelling"
       class="img-fluid rounded z-depth-1" %}
   </div>
</div>

<div class="caption">
Illustration of robot compliance for (a) rigid-linked and (b) soft continuum robots under different robot configurations.
</div>

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
       loading="eager"
       path="assets/img/stiffness_modelling.png"
       title="Configuration-dependent stiffness modelling"
       class="img-fluid rounded z-depth-1" %}
   </div>
</div>

<div class="caption">
Configuration-dependent kinematics and stiffness modelling of soft continuum robots.
</div>

---

## Model-Based Motion Control

Building on the analytical modelling framework, I developed **model-based inverse kinematics methods** that determine the actuation pressures required to achieve a desired robot position and orientation.

Rather than relying on extensive empirical calibration or large training datasets, the controller uses the physical model of the robot to relate desired configuration to pneumatic actuation. This enables real-time trajectory tracking while maintaining an interpretable connection between robot mechanics and control.

<div class="embed-responsive embed-responsive-16by9">
  <iframe
      class="embed-responsive-item"
      src="https://www.youtube.com/embed/Ngrbg2_GYGk"
      title="Model-based inverse kinematics control"
      allowfullscreen>
  </iframe>
</div>

This work established a direct progression from **analytical modelling to closed-loop robot control**, and provided the foundation for my subsequent research in compliance regulation and physical interaction.

---

## Reduced-Order Modelling and Digital Twins

For systems whose geometry and deformation are difficult to capture analytically, I have also investigated **reduced-order finite-element modelling** as an alternative route towards real-time prediction and control.

In collaborative work with researchers at Inria, we developed a reduced finite-element model for pneumatic soft continuum robots and integrated it with position feedback for closed-loop inverse kinematics control. The approach retained the ability of finite-element methods to represent complex deformation while reducing the computational cost required for control.

The method achieved median trajectory-tracking errors below **2 mm** for single- and two-segment soft continuum robots.

<div class="embed-responsive embed-responsive-16by9">
  <iframe
      class="embed-responsive-item"
      src="https://www.youtube.com/embed/MoFYQx4Zbzk"
      title="Reduced finite element modelling and closed-loop control"
      allowfullscreen>
  </iframe>
</div>

This work complements my analytical modelling research by providing a route towards **computationally efficient digital representations of compliant robotic systems**, particularly when robot geometry, material behaviour or environmental interaction becomes too complex for compact analytical descriptions.

---

## Related Publications and Outputs

1. **J. Shi**, W. Gaozhang, S.-A. Abad and H. Wurdemann,  
   **Stiffness Modelling and Control for Soft Material Continuum Robotic Manipulators**,  
   In *Soft Material Robotic Systems: Recent Advances and Future Developments*,  
   Springer, 2026.  
   [[Chapter](https://link.springer.com/chapter/10.1007/978-3-032-22453-8_15)]

2. **J. Shi**, S.-A. Abad, J. S. Dai and H. A. Wurdemann,  
   **Position and Orientation Control for Hyperelastic Multisegment Continuum Robots**,  
   *IEEE/ASME Transactions on Mechatronics*, 2024.  
   [[PDF](/assets/pdf/Shi_T-Mech_2024.pdf)]

3. **J. Shi**, A. Shariati, S.-A. Abad, Y. Liu, J. S. Dai and H. A. Wurdemann,  
   **Stiffness Modelling and Analysis of Soft Fluidic-Driven Robots Using Lie Theory**,  
   *The International Journal of Robotics Research*, 2024.  
   [[PDF](/assets/pdf/Shi_IJRR_2024.pdf)]

4. P. Chaillou\*, **J. Shi\***, A. Kruszewski, I. Fournier, H. A. Wurdemann and C. Duriez,  
   **Reduced Finite Element Modelling and Closed-Loop Control of Pneumatic-Driven Soft Continuum Robots**,  
   *IEEE International Conference on Soft Robotics (RoboSoft)*, 2023.  
   \*Equal contribution.  
   [[PDF](/assets/pdf/Paul_ROS_2023.pdf)]

5. **J. Shi**, H. Jin, W. Gaozhang, G. Shi, S.-A. Abad and H. A. Wurdemann,  
   **A Static Modelling and Evaluation Framework for Soft Continuum Robots with Reinforced Chambers**,  
   *IEEE Transactions on Robotics*, 2025.  
   [[PDF](/assets/pdf/Shi_TRO2_2025.pdf)]

6. **J. Shi**,  
   **Understanding Compliance Properties of Soft Continuum Robots: From Analytical Model to Model-based Control**,  
   *RSS Pioneers*, 2024.  
   [[Link](https://sites.google.com/view/rsspioneers2024/participants)]
