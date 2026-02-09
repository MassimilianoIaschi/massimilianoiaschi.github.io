---
layout: page
title: Lizards...
description: ...co-design of robotic lizards at ETH Robotic Systems Lab
img: assets/img/same_gait.gif
importance: 1
category: Current Projects
related_publications: false
---

<br>

<div class="row">
  <div class="col-md-4 mt-3">
    <video class="w-100" controls playsinline preload="metadata">
      <source src="{{ '/assets/img/lowest_plane.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>

  <div class="col-md-4 mt-3">
    <video class="w-100" controls playsinline preload="metadata">
      <source src="{{ '/assets/img/intermediate_plane.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>

  <div class="col-md-4 mt-3">
    <video class="w-100" controls playsinline preload="metadata">
      <source src="{{ '/assets/img/greatest_plane.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>
</div>

<div class="caption">
  Lizard robots with three different morphologies: a low, an intermediate, and a high limb-to-body ratio, each with its own control policy to maximize cost of transport on flat ground.
</div>


<br>


The project is a collaboration between Prof. Marco Hutter and Prof. Baxi Chong (my former mentor at Dan Goldman's lab). The objective of this project is to **explore and optimize the morphological, control, and environmental parameter space in lizard-inspired robots**, using simulation and learning, to **optimize** their speed, acceleration, and energetic cost **across cluttered terrains, slopes, and sand**.
The ultimate objectives are understanding evolutionary trends through a **paleoinspired robotics approach** (e.g. independently evolved limbless body forms), and especially **informing the design of multi-modal robots** that can adapt their morphology and control policies in real time to traverse diverse environments.

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="{{ '/assets/img/bayesian_optimization.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<div class="caption">
    The video shows two sessions of a Tree-structured Parzen Estimator-based Bayesian Optimization for single-sized legged lizards to optimize the parameters of our wave-template controller.
</div>

<br>

Some of the parameters we have been exploring so far include, on the morphological side: **limb-to-body ratio, limb DoFs, body/spinal DoFs, tail-to-body ratio...**, while on the controls side: **spinal undulation amplitude and phasing (wave shape), limb stepping wave amplitude and phasing, tail undulation amplitude and phasing, phasing between body, limbs, and tail, active vs passive tail...** Finally on the environmental side we mainly explored flat terrains and slopes, and we are now just starting to test rugged terrains.


<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="{{ '/assets/img/same_gait_video.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<div class="caption">
    Performance difference of multiple-sized legged lizards using the exact same non-optimized gait.
</div>

<br>