---
layout: page
title: Gripper
description: A tendon gripper with 11 dimension of freedom
img: assets/img/gripper/cover.jpeg
importance: 1
year: 2021
category: side-project
---

It is the gripper I intend to use for my master's thesis before I change my topic to manipulator control. 

I designed it as a bionic hand with five fingers and used strings to mimic tendons. It includes 11 dimensions of freedom, namely a bending and a shifting dimension for each finger and an additional bending dimension for the thumb. I also add a bending sensor in each finger to use a close loop control in each finger. All the motors and the sensors were controlled by an Arduino mounted on the hand. 

I am proud that I managed to reduce the size of the gripper to the size of a male adult's hand and integrated all the hardware pieces in the limited space.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gripper/front.jpeg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gripper/back.jpeg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gripper/hand_with_bottle.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    The left and middle figures show how motors and sensors are installed onto the gripper. The right image proved that our gripper can hold a standard water bottle, around 700g, with friction between them.
</div>