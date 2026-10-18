---
layout: page
title: Biomedical and Minimally Invasive Robotics
description: Compliant robotic systems for diagnosis, endoscopy and minimally invasive intervention
img: assets/img/medical-robot.jpg
importance: 3
category: work
related_publications: false
---

Soft and compliant robotics offers new approaches to minimally invasive intervention by enabling devices that can navigate confined anatomical environments while reducing unwanted interaction forces with tissue. My research develops **integrated biomedical robotic systems** for minimally invasive diagnosis and intervention, including soft laparoscopic instruments and robotic gastrointestinal endoscopy.

These systems combine **compliant mechanical design, soft actuation, sensing, control and system integration** to improve navigation, dexterity and safe interaction with anatomy. A central aim is to translate fundamental advances in modelling, interaction control and sensing into robotic platforms that can be evaluated in clinically relevant environments.

---

## Soft Laparoscopic Robotics

Conventional rigid laparoscopes provide limited dexterity once inserted through a trocar. I developed a hand-held soft laparoscopic system incorporating a pneumatically actuated continuum manipulator that can actively bend within the abdominal cavity while remaining compatible with standard minimally invasive access.

The system is controlled through an intuitive touch interface, allowing the viewing direction to be adjusted without repositioning the complete instrument. The compliant architecture provides additional dexterity within confined surgical workspaces while maintaining a compact and user-oriented design.

This work illustrates how **soft actuation, compliant mechanics and haptic interaction** can be integrated within a minimally invasive robotic device.

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
Hand-held soft laparoscope integrating a compliant continuum manipulator and touch-based control interface.
</div>

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/hYeNnAxgLZA"
       title="Soft laparoscope demonstration"
       allowfullscreen>
   </iframe>
</div>

---

## Self-Propelled Soft Robotic Colonoscopy

Conventional colonoscopy relies on pushing a semi-flexible instrument through the colon, which can generate friction, looping and substantial interaction forces with the bowel wall. My research investigates an alternative **self-propelled robotic approach based on tip eversion**, in which the device advances by progressively everting a compliant tube from its distal end.

This locomotion principle substantially reduces sliding between the robotic structure and the surrounding anatomy, providing a mechanically different route towards lower-force gastrointestinal navigation.

The robotic platform integrates:

- a 1.6 m tip-everting locomotion mechanism;
- a pneumatically actuated soft steering manipulator with more than 180° omni-directional bending;
- teleoperated joystick control;
- vision-based navigation using a tip-mounted camera;
- sensing and control for monitoring and regulating robotic operation.

Laboratory evaluation demonstrated reliable navigation through anatomically representative colon phantoms while maintaining average interaction forces below **0.3 N**, substantially lower than those observed with conventional push-based colonoscopy in comparative experiments.

This work was developed within the **EPSRC ROBOGAST programme**, led by Prof. Ferdinando Rodriguez y Baena, with additional collaboration and experimental support from the Multi-scale Medical Robotics Center at The Chinese University of Hong Kong.

<div class="row mt-3">
   <div class="col-sm mt-3 mt-md-0">
       <img class="img-fluid rounded z-depth-1"
            src="/assets/img/TRO_system.png"
            alt="Soft robotic colonoscope"
            data-zoomable>
   </div>
</div>

<div class="caption">
Overview of the self-propelled soft robotic colonoscope integrating tip-everting locomotion, pneumatic steering, sensing and vision-based navigation.
</div>

### Demonstration

<div class="embed-responsive embed-responsive-16by9">
   <iframe class="embed-responsive-item"
       src="https://www.youtube.com/embed/KA3DegGUyeA"
       title="Soft robotic colonoscope demonstration"
       allowfullscreen>
   </iframe>
</div>

---

## Integrated Steering, Sensing and Navigation

Developing a clinically useful robotic endoscope requires more than locomotion alone. My research therefore considers the colonoscope as an **integrated biomechatronic system**, combining compliant steering, sensing, visual feedback and control within a compact platform.

The distal steering section uses pneumatic actuation to provide local orientation control while remaining mechanically compliant. This capability is combined with visual information from the distal camera and sensing of the robotic system to support both teleoperated and increasingly autonomous navigation strategies.

Related work has investigated:

- localised pneumatic steering mechanisms for everting robots;
- vision-based adaptive steering;
- pneumatic force sensing for interaction monitoring;
- shape reconstruction using compliant sensing technologies;
- real-time detection of abnormal operating conditions.

These developments connect the fundamental work in modelling, sensing and interaction control with the requirements of a complete biomedical robotic system.

---

## Preclinical Validation and Clinical Translation

A major focus of my recent work has been progressing robotic endoscopy beyond laboratory proof-of-concept towards **clinically relevant evaluation and translation**.

The robotic colonoscopy platform has been evaluated progressively through benchtop testing, anatomically representative phantoms, clinician usability assessment and preclinical experiments, including **ex vivo and in vivo porcine validation**.

This translational work has required close collaboration between engineers, clinicians and translational specialists and has included activities spanning:

- clinician evaluation and usability feedback;
- preclinical experimental planning and validation;
- intellectual-property development;
- quality-management and design-control activities;
- risk-management and regulatory planning;
- development of translational funding applications.

These activities provide a pathway for connecting fundamental biomechatronic research with the requirements of **medical-device development and future clinical evaluation**.

---

## Related Publications

1. **J. Shi**, K. Borvorntanajanya, K. Chen, E. Franco and F. Rodriguez y Baena,  
   **Design, Control, and Evaluation of a Novel Soft Everting Robot for Colonoscopy**,  
   *IEEE Transactions on Robotics*, 2025.  
   [[PDF](/assets/pdf/Shi_TRO_2025.pdf)]

2. J. F. Ahmed, K. Borvorntanajanya, **J. Shi**, E. Franco, A. Darzi,  
   F. Rodriguez y Baena and N. Patel,  
   **Reducing Applied Force in Colonoscopy Using a Novel Soft Robotic Colonoscope: A Head-to-Head Study**,  
   *Endoscopy International Open*, 2025.  
   [[Article](https://doi.org/10.1055/a-2641-5827)]

3. **J. Shi**, G. Shi, Y. Wu and H. A. Wurdemann,  
   **A Multi-Cavity Touch Interface for a Flexible Soft Laparoscopy Device: Design and Evaluation**,  
   *IEEE Transactions on Medical Robotics and Bionics*, 2024.  
   [[PDF](/assets/pdf/Shi_TMRB_2024.pdf)]

4. K. Chen, Y. Zhang, **J. Shi**, D. S. Elson and A. Astolfi,  
   **Vision-Based Adaptive Steering Control for Navigation of a Soft Robotic Colonoscope**,  
   *23rd IFAC World Congress*, 2026.

5. K. Borvorntanajanya, **J. Shi**, J. F. Ahmed, E. Franco and F. Rodriguez y Baena,  
   **A Pneumatic Force Sensor for Enhanced Force Feedback in Robotic Colonoscopy**,  
   *IEEE Transactions on Medical Robotics and Bionics*, 2025.

6. Y. Lu, K. Borvorntanajanya, **J. Shi** and F. Rodriguez y Baena,  
   **Finite Element Analysis and Experimental Characterisation of a Localised Steerable Tip for Soft Everting Robots**,  
   *IEEE International Conference on Soft Robotics (RoboSoft)*, 2026.  
   [[PDF](/assets/pdf/Lu_RoboSoft_2026.pdf)]
