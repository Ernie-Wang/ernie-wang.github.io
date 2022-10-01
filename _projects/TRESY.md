---
layout: page
title: TRESY
description: A Tele REhabiliation SYstem
img: assets/img/tresy/cover.jpg
importance: 1
year: 2018
category: side-project
---

We construct this device to help doctors monitor the patient's rehabilitation process remotely. 

For the patient's end, we used 2 cameras to capture the patient's actions from different angles and send them to a remote server. Then, we use the [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) to detect the patient's 2D pose. Afterward, we synchronized these two videos and reconstructed the patient's motion according to the camera angle, which will be displayed on the patient's device.

For the doctor's end, the website we created will visualize the patient's motion, along with the correct rehabilitation posture. In addition, the website also allows the doctor to rotate the figure for a clear view and provides the accuracy of the patient's motion compared to the correct one.

My contributions to the project are designing the website's interface that could interact with the doctor using 3D.js and constructing the server to receive videos from a remote camera with Django. Additionally, I implemented the [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) to identify the posture and reconstruct the motion.

TRESY outperformed the other 150 teams that attended in Arm Design Contest 2018, ranked top 10, and was honorable mentioned by Arm Taiwan.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/hardware.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/display.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Hardware and reconstruct motion on the patient's end.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/left1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/left2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/left3.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    We constructed the motion using OpenPose as pose identification and used two cameras at different angles to reconstruct the motion, as shown on the right.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tresy/web.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The doctor's end displays the patient's motion and the accuracy of it related to the correct rehabilitation motion.
</div>
