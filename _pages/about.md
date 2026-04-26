---
layout: archive
title: "Experience"
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<p>The following sections outline my various work experiences, including key projects and areas of responsibility.</p>

<hr>

<h2>Perceptive Locomotion over Uneven Terrain</h2>
<div style="display: flex; gap: 0.5em; align-items: flex-start;">
  <div style="flex: 0 0 55%;">
    <p>The robot uses onboard depth cameras to build a grid-based height map of its surroundings. This representation is passed into an A* footstep planner, which generates the next three steps based on the current terrain.</p>

    <p>After every step, the robot replans using updated sensor data. Rather than committing to a full sequence, it keeps only the immediate next step and discards the rest. This allows the system to stay responsive to new obstacles and terrain changes as they come into view.</p>

    <p>All planning and execution logic is managed by a custom state machine, enabling smooth, continuous motion in dynamic environments.</p>
  </div>
  <div style="flex: 0 0 50%;">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
      <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/X6-OMfI5n9Y?autoplay=1&mute=1&loop=1&playlist=X6-OMfI5n9Y&controls=0&modestbranding=1&rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>
    </div>
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; margin-top: 0.5em;">
      <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/E2m-DYu7yw4?autoplay=1&mute=1&loop=1&playlist=E2m-DYu7yw4&controls=0&modestbranding=1&rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>
    </div>
  </div>
</div>

<hr>


<h2>Debugging Robot Hardware</h2>



<hr>


<h2>Video Capture Algorithm</h2>
