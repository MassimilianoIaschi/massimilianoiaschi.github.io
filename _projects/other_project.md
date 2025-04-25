---
layout: page
title: Other Projects
description: A selection of various projects from my research internships or from my old CRAB lab projects.
img: assets/img/tethys.gif
importance: 2
category: Past Projects
related_publications: false
---

<br>

The main project I worked on when I was part of the **PoWeR lab** was under the supervision of **Amro Alshareef** during Spring 2023. With his help, I **designed and implemented a PID control system** in Simulink for **Bump’Em**, an **open-source bump-emulation platform** developed at Stanford University, that we recreated in our lab at Georgia Tech to study **human balance and gait**.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
    <video class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;" autoplay loop muted playsinline>
      <source src="{{ '/assets/img/gdgdg.MP4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<div class="caption">
    Video shows me testing the bump'em platform that me and Amro implemented in the PoWeR lab, with increasing force perturbation amplitudes.
</div>

**Tethys Robotics** is a spin-off project at **ETH Zurich's Autonomous Systems Lab**, led by **Prof. Roland Siegwart**, dedicated to developing **autonomous underwater vehicles (AUVs)** for exploration, environmental monitoring, and search-and-rescue missions. During my Summer 2023 internship, I contributed to **multiple aspects** of the project, while simultaneously taking two **Georgia Tech courses** and an **ETH course in ROS for master's students**. Specifically, I **designed Python-based algorithms** for **real-time monitoring** of the AUV’s pose and surrounding **water current**, aiding **robust navigation and motion planning**. Additionally, I conducted research on **novel mechanical and soft robotic components** for integration into next-generation AUVs.

My key mechanical design projects included:
- **Autonomously developing a retractable leg with an automatic locking mechanism**, enhancing on-land handling and underwater deployment
- **Exploring the integration of a soft robotic tail**, inspired by collaborative research between **Tethys** and **Prof. Robert Katzschmann**

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/tethys.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/ciaociao.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/pesce_finto.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>

<div class="caption">
    Video on the top left shows Tethys ONE, the first robot launched to the market by Tethys. Top right picture instead shows me testing the robot in a lake near Zurich city centre with Andrej, the mapping lead of Tethys. Video on the bottom shows the bio-inspired robot designed to mimic real fish locomotion, developed by Prof. Robert Katzschmann and Prof. Daniel Rus, using hydraulic actuation and a soft elastomer body. While I did not prototype the tail while at ETH, I further explored soft robotics and pneumatic actuation the following semester at Georgia Tech.
</div>

The **Flexybot project** is the result of a collaboration between my mentor **Baxi Chong** and former MIT PhD student **Di Luo**, aimed at introducing a **novel contact planning framework** for multi-legged robots by mapping the planning problem to **spin models (Potts and Ising)**. This enables the **discovery of globally optimal gait sequences** for complex locomotion. This was my **first project in the lab**, and my contributions included:
- **Mechanical design and prototyping** of the hexapod
- Basic **control design**, **robot testing**, and **high-level analysis**

Despite the introductory role, it helped me grasp key concepts in **multi-legged locomotion** such as **temporal and spatial frequencies**, and **body/leg amplitudes**.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/flexi.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>

<div class="caption">
    Flexybot, a simple hexapod robot. A paper based on our Fall 2023 experiments is planned for submission in the coming months, where I will contribute to the physics modeling.
</div>

I spent my **first summer at Georgia Tech** at **Domenico Prattichizzo's lab** at Siena University. The project focused on validating the hypothesis that **thermal modulation** at the fingertip can create the **illusion of a broader contact surface**, due to the temperature dependence of human skin's viscoelastic and moisture properties.

My contributions included:
- Designing and assembling a **custom hardware setup** for generating thermal illusions
- Developing a **closed-loop temperature control system** in **LabVIEW** to enable real-time modulation and targeted **haptic perception**

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/peltier.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>

<div class="caption">
    A figure showing the experimental setup used in a subsequent paper from the lab, using hardware and control systems similar to those I developed in Summer 2022.
</div>

<br>

