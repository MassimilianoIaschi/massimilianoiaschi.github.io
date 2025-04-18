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

The main project I worked on when I was part of the PoWeR lab was under the supervision of Amro Alshareef during Spring 2023. With his help, I designed and implemented a PID control system in Simulink for Bump’Em, an open-source bump-emulation platform developed at Stanford University, that we recreated in our lab at Georgia tech to study human balance and gait.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
    <video class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;" autoplay loop muted playsinline>
      <source src="{{ '/assets/img/gdgdg.MP4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<div class="caption">
    Video shows me testing the bump'em platform that me and Amro implemented in the PoWer lab, with increasing force perturbation amplitudes.
</div>

Tethys Robotics is a spin-off project at ETH Zurich's Autonomous Systems Lab, led by Prof. Roland Siegwart, dedicated to developing autonomous underwater vehicles (AUVs) for exploration, environmental monitoring, and search-and-rescue missions. During my Summer 2023 internship at Prof. Siegwart’s lab, I contributed to multiple aspects of the project, while simultaneously taking two Georgia tech courses and ETH course in ROS for master students. Specifically, I designed Python-based algorithms for real-time monitoring of the AUV’s pose and surrounding water current, aiding robust navigation and motion planning. Additionally, I conducted research on novel mechanical and soft robotic components for integration into next-generation AUVs. My key mechanical design projects included autonomously developing a retractable leg with an automatic locking mechanism, enhancing on-land comfortable handling and safe underwater deployment, and exploring the integration of a soft robotic tail inspired by prior collaborative research between Tethys and Prof. Robert Katzschmann.


<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/ciaociao.jpg' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/pesce_finto.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Picture on the left shows me testing the robot in a lake near Zurich city centre with Andrej, the mapping lead of Tethys. Video on the right shows the bio-inspired robot designed to mimic real fish locomotion developed by Prof. Robert Katzschmann and Prof. Daniel Rus, by using hydraulic actuation coupled with an elastomer-made soft body. While I was not able to prototype the bio-inspired tail while at ETH, I explored more the use of soft robotics and pneumatic actuation the semester after, while at Georgia Tech.
</div>

The Flexybot project is the result of a collaboration between my mentor Baxi Chong and former MIT PhD student di Luo, with the aim of introducing a novel contact planning framework for multi-legged robots by mapping the planning problem to spin models (Potts and Ising), enabling the discovery of globally optimal gait sequences for complex locomotion behaviors. This was my very first project in the lab, and my roles were limited to the mechanical design and prototyping of the hexapod used for the experiments, some simple control design, as well as robot testing and high-level analyses. Despite the basic role, it was the first project that allowed me to understand important topics in multilegged locomotion such as temporal and spatial frequencies, body and leg amplitudes...

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/flexi.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Flexybot, a simple hexapod robot. A paper based on the experiments we did Fall 2023 should be submitted within the next months, in which I will have a role in the physics modeling too.
</div>

I spent my first summer at Georgia Tech at Domenico Prattichizzo's lab at Siena University. My objective was to set up both hardware and software to validate the following hypothesis: Increasing the temperature between the contact surface and the fingertip allows the user to feel a broadening of that contact surface, due to the temperature dependence of the viscoelasticity and the moisture level of human skin. My role was therefore to first design and assemble a custom hardware setup to generate and evaluate the thermal illusions, integrating sensors and actuators for precise thermal modulation, and then to develop a closed-loop temperature control system using LabVIEW, enabling real-time modulation of the contact surface temperature to elicit specific haptic perceptions.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/peltier.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>

<div class="caption">
    A figure showing the experimental setup used for a successive paper of the lab, using both a similar hadware and a similar control system to the one developed by myself during summer 2022.
</div>

<br>
