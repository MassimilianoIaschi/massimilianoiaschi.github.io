---
layout: page
title: Using Tactile Sensing to...
description: ...enhance  vertical obstacle negotiation for multilegged robots
img: assets/img/juntao_paper.gif
importance: 1
category: Past Projects
related_publications: false
---

Most robotics efforts nowadays go towards the development of complex algorithms for enhancing locomotion on complex terrains, relying on the so-called computational intelligence. However, such algorithms while currently successfully revolutionizing the paradigms of robotics locomotion, are highly dependent on **vision capabilities, which are often not available in cluttered, dark, narrow environments like search-and-rescue environments are**.
At the CRAB Lab, while recognizing the extreme value of computational intelligence in robotics, we focus on studying the physics of locomotion, and as a direct consequence, on **providing simpler morphological alternatives to successfully perform similar tasks even just using open-loop control systems or at least simple feedback controllers and algorithms**.

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/riproviamo.jpg' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/outdoor.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Left picture shows the robot locomoting through cluttered environments, both artificial and natural, displaying the system's climbing and unjamming capabilities. On the right a timelapse of the robot locomoting through a cluttered pipe, displaying the system's ability to locomote through narrow environments.
</div>

<br>

By definition, centipedes are long and narrow. The first feature, combined with their **spatial redundancy (multiple legs)** allows for great stability on every terrain without necessary complex computational intelligence. The second feature allows them to **reach environments that most other legged robot cannot**.
In this paper, we build on this already advantageous mechanical intelligence through the addition of **low-bandwidth tactile sensing**, a compliant antenna plus binary foot contacts, and a **simple feedback controller** that is able to estimate the geometry of an obstacle, modulate just two vertical joints to “raise, hook, and drag” the body over it and successfully climb it.
Results show how our **new controller allows the robot to climb up to 5 times its own height**.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="{{ '/assets/img/juntao_rss_video.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<div class="caption">
    The video above is the SI video of our latest RSS submission
</div>

<br>

The work presented above rapresents only the first step of a larger series. Future work, in collaboration with the PhD student Juntao He, will involve the design of improved tactile sensing mechanisms, the creation of a learning-based controller, and SLAM applications.

