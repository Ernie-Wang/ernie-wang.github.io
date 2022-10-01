---
layout: page
title: John
description: A humanoid robot at your service.
img: assets/img/john/john_cover.jpg
importance: 1
category: research
---

John is a humanoid robot we designed to serve elders in daily needs, such as grabbing the pill jar. 
In addition, we integrated a rehabilitation device that encourages the elders to work out for additional rewards.

---

My main contribution to this project is co-designing the system onboard the robot, allowing me to implement what I have learned in System Engineering.

For a robot to walk with its feet, there barely have space for its computer, not to mention a display for information. Our solution is to mount 2 Nvidia Xavier NX onto the robots, which control the upper body and the legs separately to reduce the workload on each computation device. 
My solution to the hardware setting is applying the Robot Operating System ([ROS](https://www.ros.org)). We built a communication layer above the upper body and lower body subsystem for the two subsystems to publish their current status to the ROS cloud and receive commands. For the users or developers, we can extract data from the ROS cloud to monitor the robot and control it when needed.

Another contribution is that I constructed the robot's upper body control subsystem. An essential function of the upper body is to grab the target object user requires. In order to control the manipulator, I applied the VMP control, my master's thesis, as the control base. More information are detailed in [project/VMP](/projects/VMP/).


<style>
.video-container { position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;}
.video-container iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }
</style>
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/PGb2CXPzCUk?t=150" title="A22-143 第二十二屆旺宏金矽獎" frameborder="1" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="caption">
    Demonstration video of our robots in action. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/john/front.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/john/op1.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/john/op3.jpg" title="example image" class="img-fluid rounded z-depth-2" %}
    </div>
</div>
<div class="caption">
    Gallery of our robot.
</div>