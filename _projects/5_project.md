---
layout: page
title: Sensing, Haptics and Adaptive Interaction
description: Multimodal sensing, state and force estimation, haptics, and adaptive control for safe physical interaction
img: assets/img/wearing_haptics.jpg
importance: 2
category: work
related_publications: false
---

Safe physical interaction requires robotic systems to understand both their own state and their interaction with the surrounding environment. My research investigates **sensing, estimation and adaptive control strategies** that enable compliant robotic systems to perceive deformation, contact and interaction forces, and to modify their physical behaviour accordingly.

This work spans **multimodal shape and force sensing, model- and vision-based state estimation, contact-force control, adaptive compliance regulation and wearable haptics**, with particular relevance to biomedical robotics and physical human–robot interaction.

---

## Multimodal Sensing and State Estimation

Compliant robots are challenging to instrument because conventional rigid sensors can alter their mechanical behaviour or can be difficult to integrate within confined geometries. My research therefore investigates both **compliant sensing technologies and indirect state-estimation approaches** for measuring robot configuration and physical interaction.

This work includes:

- ionic hydrogel sensing for three-dimensional shape reconstruction of soft robotic endoscopes;
- pneumatic sensing for interaction-force measurement in robotic colonoscopy;
- vision-based force estimation for soft continuum robots;
- multimodal sensing and imaging within integrated robotic endoscopy systems.

Together, these approaches provide complementary information about **robot shape, configuration, contact and interaction forces**, enabling more informed control of compliant biomechatronic systems.

---

## Adaptive Compliance Regulation

Soft robots possess intrinsic compliance, but their passive mechanical behaviour cannot always satisfy the requirements of different tasks. My research investigates **active compliance regulation**, allowing the apparent mechanical response of a soft robot to be selectively stiffened or softened according to the interaction task.

Building on physics-based models of robot stiffness and compliance, the control framework modifies the robot response while maintaining its underlying compliant structure. This enables the same robotic system to exhibit increased stiffness when resisting external loads and increased softness when safe interaction or obstacle accommodation is required.

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
       loading="eager"
       path="assets/img/compliance-control.jpg"
       title="Active compliance regulation"
       class="img-fluid rounded z-depth-1" %}
   </div>
</div>

<div class="caption">
Model-based active regulation of the interaction compliance of soft continuum robots.
</div>

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/jIMxLOcQLWo"
       title="Adaptive compliance regulation"
       allowfullscreen>
   </iframe>
</div>

This work extends conventional trajectory control towards **task-dependent physical adaptation**, providing a route for compliant robots to modify how they respond to contact with their surroundings.

---

## Force-Sensor-Free Contact Force Control

Safe biomedical interaction often requires direct regulation of the forces applied to surrounding anatomy. However, integrating dedicated force sensors into small and compliant robotic systems can be difficult.

Building on my configuration-dependent compliance models, I developed a model-based approach for controlling contact forces **without direct force-sensing feedback**. The method uses the robot's compliance matrix to determine the deformation required to generate a desired Cartesian force, while an inverse-kinematics model calculates the corresponding pneumatic actuation.

The framework enables:

- contact-force regulation along three Cartesian axes;
- force control across different robot configurations;
- operation without dedicated force sensors;
- model-based control without extensive training datasets.

The method was experimentally validated using single- and two-segment pneumatic soft continuum robots, achieving mean static force-control errors below **5% of the desired peak forces**.

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/mEdugyrnJYg"
       title="Model-based contact force control for soft continuum robots"
       allowfullscreen>
   </iframe>
</div>

This work connects **mechanical modelling with physical interaction control**, allowing the robot's compliant behaviour to be exploited for regulating contact forces without dedicated force sensing.

---

## Vision-Based State Estimation and Control

In addition to embedded and model-based sensing, I have investigated how external vision can provide information about the configuration and interaction state of compliant robots.

In collaborative work led by Dr Elijah Almanzor, I contributed to a deep visual inverse-kinematics framework for controlling the complete shape of soft continuum robots. Camera feedback was used to estimate robot configuration and support closed-loop shape control without requiring embedded position sensors.

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/NlafrbcFjZg"
       title="Vision-based shape control of soft continuum robots"
       allowfullscreen>
   </iframe>
</div>

Related work has also investigated **vision-based interaction-force estimation**, demonstrating how visual deformation information can be used to infer forces acting on soft continuum robots.

These approaches complement embedded sensing by providing non-contact information about robot state and physical interaction.

---

## Wearable Haptics and Tactile Interaction

Soft haptic technologies can provide controlled mechanical stimulation while remaining compliant with the human body. At University College London, I contributed to the development of a **bio-inspired wearable fingertip device** for reproducing and quantitatively assessing tactile sensations.

Working as a Research Assistant, I further developed the system electronics and control interface and, together with Dr Wenlong Gaozhang, designed a fully portable hardware platform to improve the technology readiness of the device.

The system provides a platform for **quantitative assessment of fingertip sensory function** and has potential applications in restoring tactile feedback during robot-assisted intervention.

The project was led by Dr Sara-Adela Abad Guaman and Prof. Helge A. Wurdemann at UCL and received substantial media attention, including coverage by the *Financial Times*, *The Standard* and *The Independent*.

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
       loading="eager"
       path="assets/img/finger-tip.jpeg"
       title="Wearable haptic fingertip device"
       class="img-fluid rounded z-depth-1" %}
   </div>
</div>

<div class="caption">
Portable wearable fingertip device for tactile stimulation and quantitative assessment of sensory function.
</div>

---

## Variable-Stiffness Collaborative Robots

The principles of adaptive physical interaction also extend beyond pneumatically driven soft continuum robots.

In collaborative work led by Dr Wenlong Gaozhang from the University of Essex, together with researchers from King's College London, Queen Mary University of London and UCL, we developed a modular collaborative robot incorporating **variable-stiffness bending joints, rotational joints and modular links**.

Inspired by antagonistic actuation, the system can adapt both its configuration and mechanical stiffness, enabling different levels of flexibility and contact compliance for healthcare and industrial manipulation tasks.

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/-4tjd3aDn9I"
       title="Modular variable-stiffness robot"
       allowfullscreen>
   </iframe>
</div>

---

## Related Publications

1. **D. Zhou** and **J. Shi**,  
   **A Hybrid Position–Compliance Control Method for Stiffening and Softening in Soft Continuum Robots**,  
   *IEEE/ASME Transactions on Mechatronics*, 2026.  
   [[PDF](/assets/pdf/Zhou_T-Mech_2026.pdf)]

2. **J. Shi**, S.-A. Abad, J. S. Dai and H. A. Wurdemann,  
   **Compliance Model-Based Contact Force Control for Soft Continuum Robots**,  
   *Soft Robotics*, 2026.  
   [[PDF](/assets/pdf/Shi_SoRo_2025.pdf)]

3. **J. Shi**, S.-A. Abad, G. Shi, W. Gaozhang, J. S. Dai and H. A. Wurdemann,  
   **Model-Based Static Compliance Analysis and Control for Pneumatic-Driven Soft Robots**,  
   *IEEE/ASME Transactions on Mechatronics*, 2025.  
   [[PDF](/assets/pdf/Shi_T-Mech_2025.pdf)]

4. X. Chen, **J. Shi**, H. A. Wurdemann and G. T. Thuruthel,  
   **Vision-Based Tip Force Estimation on a Soft Continuum Robot**,  
   *IEEE International Conference on Robotics and Automation (ICRA)*, 2024.

5. E. Almanzor, F. Ye, **J. Shi**, G. T. Thuruthel, H. A. Wurdemann and F. Iida,  
   **Static Shape Control of Soft Continuum Robots Using Deep Visual Inverse Kinematic Models**,  
   *IEEE Transactions on Robotics*, 2023.  
   [[PDF](/assets/pdf/Almanzor_TRO_2023.pdf)]

6. K. Borvorntanajanya, **J. Shi**, J. F. Ahmed, E. Franco and F. Rodriguez y Baena,  
   **A Pneumatic Force Sensor for Enhanced Force Feedback in Robotic Colonoscopy**,  
   *IEEE Transactions on Medical Robotics and Bionics*, 2025.

7. S. Chen, **J. Shi**, L. Tian, F. Rodriguez y Baena, J. Kim and D. Dini,  
   **Ionic Hydrogel Sensors for Low-Latency High-Accuracy 3D Reconstruction of Soft Robotic Endoscope**,  
   *Cell Reports Physical Science*, 2026.

8. W. Gaozhang, Y. Li, **J. Shi**, Y. Wang, A. Stilli, K. Althoefer and H. A. Wurdemann,  
   **A Modular Variable Stiffness Co-bot System Achieving Tasks Flexibility and Contact Compliance**,  
   *Advanced Science*, 2026.  
   [[PDF](/assets/pdf/Wenlong_as_2026.pdf)]
