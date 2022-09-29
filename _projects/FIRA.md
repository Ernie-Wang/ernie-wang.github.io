---
layout: page
title: AndroSot, FIRA
description: A kid-size humanoid robot soccer tournament, held by Federation of International Robot-Sport Association (FIRA)
img: assets/img/FIRA_proj/cover.jpg
importance: 1
category: research
---

### Overall
AndroSot is a kid-size (robot height > 60 cm) robot soccer tournament requiring each team to compete without interfering with the system.

It is composed of 3 competitions:  
- Challenge 1 - Dribble and Attack  
- Challenge 2 - Free attack  
- 3 vs. 3 soccer game  

Our team is the triple champion in the 24th FIRA, held in Changwon, Korea, in 2019. The following attachments are the video clips we shot during the tournament.

<div class="row">
    <a href="https://www.youtube.com/watch?v=alOSQRSHaXU&list=PLjliv8Nq4H0Yueqa3kKgiZq-aFHjFNfrJ
    " target="_blank">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.html path="assets/img/FIRA_proj/video_cover.png" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </a>
</div>
<div class="caption">
    Highlights of the tournament. Click it to redirect to Youtube. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/challenge1.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/challenge2.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/game.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    Certificates of the AndroSot tournament.
</div>

---

### Contributions

Our system can be separated into three parts, robot players on the field, computer vision from the top, and the strategy for the game. 

My responsibilities are the communication system for robots and the computer, the robot's onboard system, and the robot's actions. 
Through my development, I achieved:
1. Reduced the communication time up to 80% compare to the wifi-based counterparts.
2. Reduced the robot response time and increased robot action stability by designing safe interruptions.
3. Redesign the robot to integrate the communication chip, low battery alarm, and player selection switch to minimize maintenance time.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/system_struct.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/robot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overall system structure on the right, and our robot on the left.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/head1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/head2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/head3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     The central power switch is on the left. Inside the head, we can see the communication chip and the voltage detection device. The player switch is placed on the right, allowing us to change the robot's identity without uploading a new configuration. The front display shows our robot's voltage, enabling us to keep track of the battery usage.
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FIRA_proj/friends.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
