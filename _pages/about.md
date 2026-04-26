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
<div style="display: flex; gap: 2em; align-items: flex-start;">
  <div style="flex: 0 0 55%;">
    <p>I led the development of a continuous locomotion system for a bipedal robot, with the goal of enabling it to walk forward smoothly across varying terrain without stopping.
      The system relied on depth data from onboard cameras, which was transformed into a height map using a grid-based representation.
      This height map was then passed to an A* footstep planner to compute the robot’s next three steps based on the current understanding of the environment.</p>

    <p>To ensure adaptability, the robot replanned its steps after every single footstep
      As the robot advanced, the updated camera perspective provided a more accurate view of the terrain ahead, allowing for better-informed planning.
      The system retained only the immediate next step from the previous plan, discarding the rest to prioritize the most up-to-date and optimal choices.
      This planning logic was encapsulated within a custom state machine, allowing the robot to continuously walk forward across complex environments with improved robustness and autonomy.</p>

    <p>This system was thoroughly tested across a range of challenging terrains, including flat ground, uneven surfaces, and rough terrain modeled using cinder blocks.
      The robot was also tested on stairs to evaluate its ability to adapt to steep and irregular steps.
      These tests demonstrated the system’s effectiveness in maintaining stable, continuous locomotion under diverse and unpredictable conditions.</p>
  </div>
  <div style="flex: 0 0 42%;">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
      <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/X6-OMfI5n9Y?autoplay=1&mute=1&loop=1&playlist=X6-OMfI5n9Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>
</div>

<hr>


<h2>Debugging Robot Hardware</h2>



<hr>


<h2>Video Capture Algorithm</h2>
