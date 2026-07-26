---
layout: page
title: Design, Benchmarking and Tools for Soft Robotics
description: Developing experimental platforms, fabrication methods, modelling frameworks and software tools for soft robot development and evaluation.
img: assets/img/platform_cover.png
importance: 4
category: work
---

Soft robots offer unique capabilities through their compliance, adaptability and safe interaction with uncertain environments. However, their highly nonlinear materials, complex geometries and application-specific designs make systematic development and objective comparison challenging. Soft robot development therefore often relies on repeated fabrication, bespoke experimental setups and trial-and-error optimisation.

My research develops tools and resources that support soft robot development pipeline, from fabrication and computational modelling to experimental characterisation and control validation. This work includes benchmarking platforms, reproducible fabrication approaches, analytical and finite-element modelling methods, and graphical user interfaces that allow researchers to explore robot designs before physical prototyping.

Collectively, these contributions aim to reduce development time, improve experimental reproducibility and facilitate the translation of soft robotic technologies into practical applications.


## Benchmarking Platforms

I develop modular experimental platforms for the systematic actuation, characterisation and control of pneumatically driven soft robots. These platforms integrate pneumatic regulation, sensing, force measurement, motion tracking, data acquisition and real-time control within a unified experimental environment.

The first platform was designed to characterise essential properties of soft robotic systems, including kinematics, dynamic responses, stiffness and force-generation capability. It can be connected to either an NI data-acquisition system or an Arduino-based control unit, allowing researchers to implement and validate control algorithms using MATLAB and Simulink.

The platform was demonstrated through three representative soft robotic systems: a variable-stiffness joint, an inflatable elastic membrane and a multi-chamber soft continuum robot. These examples showed that the same infrastructure could support mechanical characterisation, actuator evaluation and control validation across different robot designs.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/nFSgb7o9cuk" allowfullscreen></iframe>
</div>

<div class="caption">
    Experimental latform for the actuation, characterisation and control validation of pneumatically driven soft robots.
</div>


## Fabrication and Design Methodologies

The behaviour of a soft robot is strongly influenced by its geometry, material properties, chamber configuration and fabrication process. My research develops systematic design and fabrication methodologies that connect these parameters to measurable robot performance.

For fibre-reinforced soft continuum robots, I developed fabrication approaches for manipulators with different diameters and lengths. Individual pneumatic chambers are densely wrapped with inextensible fibres to suppress radial expansion while allowing longitudinal elongation. This architecture enables large bending motions while preserving a central working channel for instruments, sensors or other appendages.

The fabrication framework was demonstrated using eight manipulators with different dimensions. These robots provided an extensive experimental basis for investigating how robot size, cross-sectional geometry, silicone properties and chamber pressurisation influence kinematics and force-generation capability.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/fabrication.png"
           title="Fabrication process for soft robots with reinforced chambers"
           class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>

<div class="caption">
    Fabrication process for soft robots with reinforced chambers.
</div>


I have also investigated the design of localised steering mechanisms for soft everting robots. A nonlinear finite-element model was developed to analyse a pneumatic steering manipulator operating inside an everting fabric. The model captures the interaction between the silicone manipulator and the surrounding fabric and supports evaluation of key design parameters before physical fabrication.

The combined simulation and experimental study investigated the influence of manipulator length, silicone material, fabric thickness and fabric stretchability on steering performance. This approach provides practical guidance for selecting geometries and materials while reducing the number of physical prototypes required during development.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/iOySVLSlTZo" allowfullscreen></iframe>
</div>


## Software and GUI Toolboxes

To make soft robot modelling and evaluation more accessible, I develop graphical user interfaces and software toolboxes that integrate robot design, analytical modelling and simulation. Once
design specification and dimension constraints for a specific application are identified, the user can experiment with the GUI to preliminarily determine, e.g., main design parameters and
material selection. This information can be used to expedite the robot design and reduce the prototyping time of robots.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/GUI.png"
           title="Graphical user interface for the soft robot simulation"
           class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>

<div class="caption">
    Graphic user interface with its architecture for achieving analytical analysis of soft robots with densely reinforced chambers.
</div>

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/Tlcw4VkH7jc" allowfullscreen></iframe>
</div>

The modelling framework considers several important sources of nonlinear behaviour, including:

- large longitudinal deformation;
- cross-sectional changes caused by elongation;
- stiffness changes in pressurised chambers;
- linear and nonlinear hyperelastic material models;
- variations in robot diameter, length and chamber geometry.

## Related Publications

- **J. Shi**, W. Gaozhang, H. Jin, G. Shi and H. A. Wurdemann,  
  *Characterisation and Control Platform for Pneumatically Driven Soft Robots: Design and Applications*, 2023.  
  [[PDF](/assets/pdf/Shi_ROS_2023.pdf)]

- **J. Shi**, H. Jin, W. Gaozhang, G. Shi, S.-A. Abad and H. A. Wurdemann,  
  *A Static Modelling and Evaluation Framework for Soft Continuum Robots with Reinforced Chambers*, IEEE Transactions on Robotics, 2025.  
  [[PDF](/assets/pdf/Shi_TRO2_2025.pdf)]

- **Y. Lu**, K. Borvorntanajanya, **J. Shi** and F. Rodriguez y Baena,  
  *Finite Element Analysis and Experimental Characterisation of a Localised Steerable Tip for Soft Everting Robots*, IEEE RoboSoft, 2026.  
  [[PDF](/assets/pdf/Lu_RoboSoft_2026.pdf)]
