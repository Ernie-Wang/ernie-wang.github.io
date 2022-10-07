---
layout: page
title: VMP
description: My master's research.
img: assets/img/vmp/cover.jpeg
importance: 1
year: 2022
category: research
---

Vortex Motion Policy is a collision-free trajectory planning algorithm that can move the manipulator towards the target without crashing into obstacles or itself. 
It is based on forward and backward reaching inverse kinematic ([FABRIK](https://www.google.com/search?client=safari&rls=en&q=forward+and+backward+repeat+inverse+kinematic&ie=UTF-8&oe=UTF-8)), which is a novel algorithm that allows us to avoid singularity problems that often occurred in traditional Jacobian control. 
In addition, we noticed that to grab an object, the end-effector must move in a specific direction to grab the target instead of knocking it down. As a result, our motion policy can move with a given vector in order to satisfy the grasping task.

This research project is currently under submission. Details will be accessible after the paper is published.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vmp/5dof.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vmp/6dof.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vmp/7dof.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Simulation of VMP, more experiments, and implementation on physical instruments, please refer to the published paper.
</div>