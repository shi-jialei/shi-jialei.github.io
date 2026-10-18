---
layout: page
title: Robotic Platforms, Benchmarking and Translation
description: Experimental platforms, benchmarking methods and enabling tools for reproducible development and translation of robotic technologies
img: assets/img/benchmark_platform.png
importance: 4
category: work
related_publications: false
---

Reproducible development of soft and biomedical robotic systems requires more than individual prototypes. Their nonlinear materials, complex geometries and application-specific designs make systematic characterisation, objective comparison and validation challenging, while conventional robotic test methods are often difficult to apply directly.

My research develops **experimental platforms, benchmarking methods, fabrication approaches and computational tools** that support the robotic-development pipeline from early design and characterisation through to integrated-system validation.

These enabling technologies aim to reduce iterative prototyping, improve experimental reproducibility and provide quantitative evidence that can support the translation of robotic technologies towards practical and clinical applications.

---

## Robotic Characterisation and Control Platforms

I develop modular experimental platforms for the systematic **actuation, characterisation and control validation** of pneumatically driven soft robots. These platforms integrate pneumatic regulation, sensing, force measurement, motion tracking, data acquisition and real-time control within a unified experimental environment.

The first platform was designed to characterise key properties of soft robotic systems, including:

- kinematics and workspace;
- dynamic response;
- stiffness and compliance;
- force-generation capability;
- closed-loop control performance.

The system can be connected to either an NI data-acquisition platform or an Arduino-based control unit, allowing researchers to implement and validate control algorithms using MATLAB and Simulink.

The platform was demonstrated using three representative robotic systems: a variable-stiffness joint, an inflatable elastic membrane and a multi-chamber soft continuum robot. These examples demonstrated that the same experimental infrastructure could support **mechanical characterisation, actuator evaluation and control validation across different robotic designs**.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item"
      src="https://www.youtube.com//embed/nFSgb7o9cuk"
      title="Soft robot characterisation and control platform"
      allowfullscreen>
  </iframe>
</div>

<div class="caption">
Experimental platform for the actuation, characterisation and control validation of pneumatically driven soft robots.
</div>

---

## Application-Specific Benchmarking for Biomedical Robots

As robotic technologies move towards clinical applications, benchmarking must extend from individual actuators and subsystems to **complete robotic devices interacting with anatomically realistic environments**.

My recent work investigates reconfigurable and sensorised benchmarking methods for colonoscope evaluation. The platform is designed to reproduce configurable anatomical geometries while measuring the mechanical interaction between the device and its surroundings.

The system combines:

- reconfigurable anatomical geometry;
- multi-axis force sensing;
- controlled structural displacement;
- programmable mechanical behaviour;
- quantitative measurement of completion time, interaction force and deformation;
- repeatable comparison between different endoscopic technologies.

A particular focus is the development of **active mesenteric simulation**, allowing the surrounding support structure to exhibit programmable mechanical behaviour during device insertion. This provides a route towards more realistic and reproducible evaluation than static anatomical phantoms alone.

The broader aim is to establish benchmarking approaches that enable **objective comparison of conventional and robotic endoscopic systems without requiring device-specific modification**.

---

## Reproducible Fabrication and Design

The mechanical behaviour of a soft robot is strongly influenced by its geometry, material properties, actuation-chamber configuration and fabrication process. My research therefore develops systematic fabrication and design approaches that connect these parameters to measurable robot performance.

For fibre-reinforced soft continuum robots, I developed fabrication methods for manipulators spanning different diameters and lengths. Individual pneumatic chambers are densely wrapped with inextensible fibres to suppress radial expansion while permitting longitudinal elongation.

This architecture enables large bending deformation while preserving a central working channel for instruments, sensors or other components.

The fabrication framework was demonstrated using eight manipulators with different geometries, providing an experimental basis for investigating how:

- robot diameter and length;
- cross-sectional geometry;
- silicone material properties;
- chamber configuration; and
- pneumatic actuation

influence robot kinematics and force-generation capability.

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
          loading="eager"
          path="assets/img/fabrication_pipeline.png"
          title="Fabrication process for soft robots with reinforced chambers"
          class="img-fluid rounded z-depth-1"
       %}
   </div>
</div>

<div class="caption">
Fabrication process for soft robots with reinforced chambers.
</div>

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item"
      src="https://www.youtube.com//embed/yPKFU3UapxQ"
      title="Miniaturised fibre-reinforced soft manipulators"
      allowfullscreen>
  </iframe>
</div>

<div class="caption">
Miniaturised fibre-reinforced soft manipulators.
</div>

I have also investigated the systematic design of localised steering mechanisms for soft everting robots. A nonlinear finite-element model was developed to analyse a pneumatic steering manipulator operating inside an everting fabric, capturing the mechanical interaction between the silicone structure and surrounding fabric.

The combined simulation and experimental study investigated the effects of manipulator length, silicone material, fabric thickness and fabric stretchability on steering performance. This approach enables design parameters to be evaluated computationally before fabrication, reducing the number of physical prototypes required during development.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item"
      src="https://www.youtube.com//embed/iOySVLSlTZo"
      title="Design and characterisation of a localised steerable tip"
      allowfullscreen>
  </iframe>
</div>

---

## Software and Design Toolboxes

To make soft-robot design, modelling and evaluation more accessible, I develop **graphical user interfaces and software toolboxes** that connect robot geometry, material properties and analytical models within interactive design environments.

These tools allow users to explore candidate robot designs and predict their behaviour before fabrication. Once application requirements and dimensional constraints are defined, design parameters and material choices can be varied computationally to evaluate their effect on robot performance.

This provides a route towards reducing reliance on trial-and-error prototyping and supporting more systematic design optimisation.

<div class="row">
   <div class="col-sm mt-3 mt-md-0">
       {% include figure.liquid
          loading="eager"
          path="assets/img/GUI.png"
          title="Graphical user interface for soft robot modelling"
          class="img-fluid rounded z-depth-1"
       %}
   </div>
</div>

<div class="caption">
Graphical user interface integrating robot design parameters with analytical modelling and performance prediction.
</div>

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item"
      src="https://www.youtube.com//embed/Tlcw4VkH7jc"
      title="Soft robot modelling and design toolbox"
      allowfullscreen>
  </iframe>
</div>

The modelling framework incorporates several important sources of nonlinear behaviour, including:

- large longitudinal deformation;
- cross-sectional changes during elongation;
- stiffness variation in pressurised chambers;
- linear and nonlinear hyperelastic material models;
- variations in robot diameter, length and chamber geometry.

Together, these capabilities allow robot design and mechanical behaviour to be explored within a common computational framework.

---

## Translational Engineering and Validation

For biomedical robotic systems, engineering development must ultimately connect with **clinical, regulatory and translational requirements**. My recent work therefore extends experimental validation beyond laboratory performance towards evidence that can support medical-device development.

This includes experience in:

- clinician usability evaluation;
- anatomically realistic benchtop testing;
- ex vivo and in vivo preclinical validation;
- quality-management and design-control activities;
- risk-management and regulatory planning;
- intellectual-property development;
- market and commercialisation assessment.

The aim is not to treat translation as a separate activity after engineering development, but to ensure that **design, benchmarking and validation generate evidence relevant to safety, usability and future clinical evaluation from an early stage**.

This approach connects my work on experimental platforms and quantitative benchmarking with the broader translation of intelligent biomechatronic and biomedical robotic technologies.

---

## Related Publications

- **J. Shi**, W. Gaozhang, H. Jin, G. Shi and H. A. Wurdemann,  
  *Characterisation and Control Platform for Pneumatically Driven Soft Robots: Design and Applications*,  
  IEEE International Conference on Soft Robotics (RoboSoft), 2023.  
  [[PDF](/assets/pdf/Shi_ROS_2023.pdf)]

- **J. Shi**, S.-A. Abad, A. Menciassi, K. Althoefer and H. A. Wurdemann,  
  *Miniaturised Soft Manipulators with Reinforced Actuation Chambers on the Sub-Centimetre Scale*,  
  IEEE International Conference on Soft Robotics (RoboSoft), 2024.  
  [[PDF](/assets/pdf/SHI_ROS_2024.pdf)]

- **J. Shi**, H. Jin, W. Gaozhang, G. Shi, S.-A. Abad and H. A. Wurdemann,  
  *A Static Modelling and Evaluation Framework for Soft Continuum Robots with Reinforced Chambers*,  
  IEEE Transactions on Robotics, 2025.  
  [[PDF](/assets/pdf/Shi_TRO2_2025.pdf)]

- **Y. Lu**, K. Borvorntanajanya, **J. Shi** and F. Rodriguez y Baena,  
  *Finite Element Analysis and Experimental Characterisation of a Localised Steerable Tip for Soft Everting Robots*,  
  IEEE International Conference on Soft Robotics (RoboSoft), 2026.  
  [[PDF](/assets/pdf/Lu_RoboSoft_2026.pdf)]

- W. He and **J. Shi**,  
  *A Reconfigurable Robotic Benchmarking Platform with Active Mesenteric Simulation for Colonoscope Evaluation*,  
  IEEE Robotics and Automation Letters, under review.
