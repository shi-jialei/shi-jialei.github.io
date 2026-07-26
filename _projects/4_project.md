---
layout: page
title: Design, Benchmarking and Tools for Soft Robotics
description: Developing experimental platforms, fabrication methodologies, modelling frameworks and software tools for systematic soft robot development and evaluation.
img: assets/img/soft-robot-tools.jpg
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

More details are available in the paper


## Fabrication and Design Methodologies

The behaviour of a soft robot is strongly influenced by its geometry, material properties, chamber configuration and fabrication process. My research develops systematic design and fabrication methodologies that connect these parameters to measurable robot performance.

For fibre-reinforced soft continuum robots, I developed fabrication approaches for manipulators with different diameters and lengths. Individual pneumatic chambers are densely wrapped with inextensible fibres to suppress radial expansion while allowing longitudinal elongation. This architecture enables large bending motions while preserving a central working channel for instruments, sensors or other appendages.

The fabrication framework was demonstrated using eight manipulators with different dimensions. These robots provided an extensive experimental basis for investigating how robot size, cross-sectional geometry, silicone properties and chamber pressurisation influence kinematics and force-generation capability.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/4H1Kp1k9GBM" allowfullscreen></iframe>
</div>

I have also investigated the design of localised steering mechanisms for soft everting robots. A nonlinear finite-element model was developed to analyse a pneumatic steering manipulator operating inside an everting fabric. The model captures the interaction between the silicone manipulator and the surrounding fabric and supports evaluation of key design parameters before physical fabrication.

The combined simulation and experimental study investigated the influence of manipulator length, silicone material, fabric thickness and fabric stretchability on steering performance. This approach provides practical guidance for selecting geometries and materials while reducing the number of physical prototypes required during development.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/iOySVLSlTZo" allowfullscreen></iframe>
</div>


## Software and GUI Toolboxes

To make soft robot modelling and evaluation more accessible, I develop graphical user interfaces and software toolboxes that integrate robot design, analytical modelling, simulation and experimental analysis.

The characterisation platform includes a MATLAB graphical user interface for commanding pneumatic pressures, monitoring system status, recording sensor measurements and visualising experimental data. The interface allows users to operate the platform without directly modifying low-level control code and supports rapid implementation of characterisation experiments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/characterisation-platform-gui.jpg"
           title="Graphical user interface for the soft robot characterisation platform"
           class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>

<div class="caption">
    MATLAB graphical user interface for pressure control, sensor acquisition and experimental visualisation.
</div>

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com//embed/Tlcw4VkH7jc" allowfullscreen></iframe>
</div>

Building upon this platform, I developed a model-based evaluation toolbox for fibre-reinforced soft continuum robots. The toolbox incorporates analytical models for forward kinematics and tip-force generation and allows users to define robot geometry, material behaviour, chamber dimensions and actuation pressures through an interactive interface.

The modelling framework considers several important sources of nonlinear behaviour, including:

- large longitudinal deformation;
- cross-sectional changes caused by elongation;
- stiffness changes in pressurised chambers;
- linear and nonlinear hyperelastic material models;
- variations in robot diameter, length and chamber geometry.

The toolbox enables researchers to predict robot motion and force-generation capability before fabrication. Design parameters can therefore be evaluated computationally and updated iteratively before being transferred to the physical evaluation platform.
