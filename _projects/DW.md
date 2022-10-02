---
layout: page
title: Debris Walker
description: A swarm rescue robot system.
img: assets/img/debriswalker/cover.jpg
importance: 1
year: 2020
category: research
---

In 2019, a serious earthquake struck my hometown, and many were buried after buildings collapsed. 
At that time, most rescue robots or life-detecting devices had a limited range. As a result, I intend to develop a system that can self-deploy into debris deep down and still communicate with users outside. 

According to this concept, we developed a multi-robot system, which allows the rescue mission to be processed simultaneously. Each robot is equipped with an RGB-D camera to plot the terrain for rescuers to have a clear view. 
In addition, we developed the robot's communication system based on an ad-hoc network. An ad-hoc network is a type of network that can join in freely, and each node within the network can serve as a relay. That's to say, if the robot's signals are blocked by the debris, other robots around can transmit the information from the deepest robot to the surface console and broaden the searching area. In addition, if no one is around and the signal is getting weak, the robot can release a transmitter carried within it to extend the transmission distance. 
Throughout the search, a robot will transmit its current position and the terrain within the debris through other robots or transmitters, allowing the rescue team to plan a more efficient extracting strategy according to the information. Robots will also detect if there is a victim and mark the position to notify rescuers.

My contributions are designing the robot's control system, motor drive board, and pathfinding algorithm in a complex environment based on rapidly-exploring random trees* ([RRT*](https://core.ac.uk/download/pdf/87654089.pdf)). 

<style>
.video-container { position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;}
.video-container iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }
</style>
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/GoNi4Kgk1a0" title="DEBRIS WALKER" frameborder="1" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="caption">
    Highlights of the tournament. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/debriswalker/node1.jpeg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/debriswalker/node2.jpeg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/debriswalker/node3.jpeg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    The process of releasing a communication node.
</div>

---

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/debriswalker/path.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/debriswalker/board.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The image on the left is the path planning algorithm I developed, where the blue dots are the obstacles detected, the red dots are the sample points, and the white dots are the planned path. The right image is the motor drive board for our robots.
</div>