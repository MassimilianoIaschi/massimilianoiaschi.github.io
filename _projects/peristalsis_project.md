---
layout: page
title: Using Peristaltic Waves to...
description: ...enhance multilegged robotics locomotion in complex environments
img: assets/img/my_paper.gif
importance: 2
category: Past Projects
related_publications: false
---

Between 2023 and 2024 we performed **multiple biological experiments on centipedes in confined environments**. Among various interesting behaviors, we discovered that centipedes often make use of an earthworm-like motion called **peristalsis when their legs are not enough to propel** them forward or when they are unable to use them.

<br>

These observations, together with the fact that other legged elongate animals that are great obstacle-climbers such as caterpillars use this mode of locomotion too, convinced us of the importance of peristalsis in multilegged robotics. Therefore we decided to **design a multilegged robot capable of** not only using **a vertical body wave** to propel itself forward, but also **a peristaltic wave**.

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/final_soil.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/final_burrow.gif' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Biological experiments of: on the left the centipede using peristaltic motion to navigate through tunnels excavated by the animal itself, on the right the centipede using peristaltic motion to excavate a similar tunnel through soil.
</div>

<br>

The robot is an **hybrid (in between rigid and soft) cord-driven robot**, whose each joint presented two indipendent DoFs. A rotational DoF in the sagittal plane that composed the vertical wave, actuated by introducing a differential in the upper and lower cord lengths, and a **linear DoF for periodic compression and extension**, actuated by simultaneously compressing or relaxing the upper and lower cords. The two DoFs were made independent of each other by using two extension springs which provided enough resistance to keep the joint in place during a rotation but not during a compression. Finally, spring-steel belts were used to restore the module to the extended state after the contraction, as the cords can only provide stress in the tensile direction rather than in compression. In addition such belts also provided compliance to the robot body, which significantly helped in complex substrate interaction.

<br>

<div class="row justify-content-center text-center">
    <div class="col-sm-6 d-flex justify-content-center align-items-center mt-3 mt-md-0">
        <img src="{{ '/assets/img/max_icra.png' | relative_url }}"
             alt="example image"
             class="img-fluid rounded"
             style="object-fit: contain; height: 300px; display: block; margin: auto;">
    </div>
</div>
<div class="caption">
    Design of one module of the robot.
</div>

<br>

Experimental results showed that while the benefit of peristalsis on flat-ground locomotion is marginal, the **inclusion of a properly-phased peristaltic wave substantially improves the locomotion performance on rugose terrains**. It does so, by manipulating the trajectory of the robot head, substantially reducing its forward translation **during obstacle collision, which in turn reduces jamming probability**.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="{{ '/assets/img/max_icra.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

</div>

<div class="caption">
    The video above is the SI video of our ICRA paper.
</div>


