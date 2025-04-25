---
layout: page
title: Using Learning-Based Controllers to...
description: ...enhance multilegged robotics locomotion in complex environments
img: assets/img/cxcxcxc-ezgif.com-video-to-gif-converter.gif
importance: 1
category: Current Projects
related_publications: false
---

While our lab has mostly focused within the realm of mechanical intelligence, in the past couple of years we have started to look more into **the power of computational intelligence**, specifically when applied to **centipede-inspired robotics**. This project I am currently a part of under the supervision of PhD student Juntao He is the result of a collaboration between my professor Daniel Goldman and professor Sehoon Ha. We are currently working to bring to light two papers based on this project within the next months.

A first paper aims to explore how to improve the speed and stability of multi-legged robots locomoting over rough terrain. Building on earlier work that used a linear controller to adjust vertical body motion based on foot-sensor information, we developed a **reinforcement learning-based controller that also adjusts horizontal body undulation, and leg stepping in order to identify their optimal combinations for the specific terrain being explored**. We trained this controller using a MuJoCo-based simulator that we validated against real-world experiments. The new approach led to consistent improvements in speed, typically around **30–60%—in both lab and outdoor tests**.

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/juntaooo.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/juntaoo.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Left picture shows a very high-level scheme of the learning-based controller, right picture shows the performance improvement achieved by using the learning-based controller instead of the linear controller.
</div>

<br>

A second longer-term paper instead will focus on using **short-term memory from tactile sensing, both feet and antennae, to enable effective motion planning in our robot**. Our objective here is to combine all the gaits engineered within the past months for centipede-inspired robots (turning, climbing, self-righting, sidewinding...) with the use of reinforcement learning, ultimately aiming to achieve **robust SLAM performance**.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/sfsf.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/hfhf.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/hghg.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/dndn.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Top-left and bottom-left figures show the robot in simulation locomoting through stereotypical complex environments, respectively a confined environment and an obstacle to climb. Top right figure demonstrates the robot in simulation recognizing a Dead End by taking advantage of short-term memory (foot and antenna sensors)  to estimate its geometric features and consequently escape from it. Bottom right figure shows the environment we will use to test our robot both in simulation and in real-world.
</div>

<br>


