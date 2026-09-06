---
layout: page
title: Endoluminal Soft Robots
description: Soft robotic systems for minimally invasive endoluminal interventions
img: assets/img/medical-robot.jpg
importance: 4
category: work
---

Soft robotics offers a transformative approach to minimally invasive surgery by enabling highly compliant devices that safely navigate confined anatomical environments while reducing tissue trauma. My research focuses on the design, development and experimental validation of soft robotic systems for endoluminal applications, including laparoscopy and gastrointestinal endoscopy. These systems integrate soft actuation, compliant mechanisms and intelligent control to improve surgical dexterity, navigation and patient safety.

---

## Soft Laparoscope

Conventional rigid laparoscopes provide limited dexterity once inserted through a trocar. This project investigates a hand-held soft laparoscope capable of actively bending inside the abdominal cavity while remaining compatible with standard 12 mm trocar ports.

The system employs a pneumatically actuated soft continuum manipulator that is controlled through an intuitive touch interface, allowing surgeons to adjust the viewing direction without repositioning the entire instrument. The compliant design improves manoeuvrability within confined surgical workspaces while maintaining a simple user interface.

More details are available in the
[TMRB paper](/assets/pdf/Shi_TMRB_2024.pdf).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
        loading="eager"
        path="assets/img/laparoscope.jpg"
        title="Soft laparoscope"
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
Hand-held soft laparoscope with a touch-based control interface.
</div>

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item"
        src="https://www.youtube.com/embed/hYeNnAxgLZA"
        allowfullscreen>
    </iframe>
</div>

---

## Self-Propelled Soft Robotic Colonoscope

This project develops a self-propelled soft robotic colonoscope based on the tip-everting locomotion principle. Unlike conventional push-type colonoscopes, the robot advances by everting a compliant fabric tube from its distal tip, substantially reducing friction and interaction forces with the colonic wall.

The robotic platform integrates:

- a 1.6 m tip-everting locomotion mechanism;
- a pneumatically actuated soft steering manipulator capable of more than 180° omni-directional bending;
- teleoperated joystick control;
- autonomous vision-based navigation using a tip-mounted camera.

Comprehensive laboratory evaluations demonstrated reliable navigation through anatomically representative colon phantoms while maintaining average tissue interaction forces below **0.3 N**, significantly lower than those produced by conventional colonoscopy.

This work was supported by the **EPSRC ROBOGAST Programme Grant (EP/X033546/1)** led by Prof. Ferdinando Rodriguez y Baena and partially supported by the Multi-scale Medical Robotics Center at The Chinese University of Hong Kong.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1"
             src="/assets/img/TRO_system.png"
             alt="Soft robotic colonoscope"
             data-zoomable>
    </div>
</div>

<div class="caption">
Overview of the self-propelled soft robotic colonoscope integrating tip-everting locomotion, pneumatic steering and autonomous navigation.
</div>

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item"
        src="https://www.youtube.com/embed/KA3DegGUyeA"
        allowfullscreen>
    </iframe>
</div>


## Related Publications

1. **J. Shi**, G. Shi, Y. Wu and H. A. Wurdemann,  
   **A Multi-Cavity Touch Interface for a Flexible Soft Laparoscopy Device: Design and Evaluation**,  
   *IEEE Transactions on Medical Robotics and Bionics*, 2024.  
   [[PDF](/assets/pdf/Shi_TMRB_2024.pdf)]

2. **J. Shi**, K. Borvorntanajanya, K. Chen, E. Franco, and F. Rodriguez y Baena,  
   **Design, Control, and Evaluation of a Novel Soft Everting Robot for Colonoscopy**,  
   *IEEE Transactions on Robotics*, 2025.  
   [[PDF](/assets/pdf/Shi_TRO_2025.pdf)]

3. J. F. Ahmed, K. Borvorntanajanya, **J. Shi**, E. Franco, A. Darzi,  
   F. Rodriguez y Baena and N. Patel,  
   **Reducing Applied Force in Colonoscopy Using a Novel Soft Robotic Colonoscope: Head-to-Head Study**,  
   *Endoscopy International Open*, 2025.  
   [[Article](https://doi.org/10.1055/a-2641-5827)]
