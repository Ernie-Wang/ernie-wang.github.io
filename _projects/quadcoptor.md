---
layout: page
title: Quadcopter
description: a quadcopter with a somatosensory controller
img: assets/img/quad/copter.jpg
importance: 1
category: side-project
---

My first side-project!   
In this project, I tempt to fly a quadcopter with hand posture.  
My solution is to syncronize the IMU onboard the quadcopter with the one I am holding. That says, when I pitch forward, the quadcopter will mock the posture and start to move forward.   

However, the propulsion each motor provides on my quadcopter is imbalanced, which ends up spinning instead of flying.

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/quad/controller.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/quad/copter&control.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    Left: Somatosensory controller, red button increases the thruster, and the black reduces it. Right: Controller and the quadcopter.
</div>

### Second Chance

During my first summer vacation, I assisted in a quadcopter project led by distinguished prof. [Jeen-Shing Wang](https://researchoutput.ncku.edu.tw/en/persons/jeen-shing-wang) at CILS Lab. Within the project, I was allowed to integrate my somatosensory controller with a commercial quadcopter. Although the integration was a success, the control interface is sensitive, making the quadcopter harder than ever to control, and it crashed on the first flight. However, the disaster made me value the human-robot interface equally to the robot itself, which greatly impacted my design principle later. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/quad/on_plat.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>
