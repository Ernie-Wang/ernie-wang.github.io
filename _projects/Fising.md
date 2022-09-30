---
layout: page
title: Fising
description: A somatosensory music instrument
img: assets/img/fising/fising_cover.jpg
importance: 1
category: side-project
---

We designed and constructed this somatosensory music instrument with students from industrial design. 
The concept of the instrument is to find a way for the performers to express body language while performing music. As a result, we use an IMU to detect the user's hand's posture and decide the sound to play. 

Due to the ergonomic design, our device looks just like a fish. Since it also sings, we named it "Fising". Within Fising, we have a mute button on the belly, allowing the user to wave around, making unexpected sounds, and a volume slider to adjust the volume. In addition, we considered the possibility of performing as a group; therefore, some players may switch to chord mode by pressing the button on the top of the fish.

My contributions to this project are building the hardware components within the instrument and programming the system. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fising/operate.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fising/whole.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fising/semi.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left is a demonstration of the usage of our device. The middle is what our device looks like, and the hardware embedded inside the device is on the right.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fising/demo1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The overall system. We created an App that connects the Fising via Bluetooth to receive instructions from the user. We also have a database for users to choose their preferred instruments, such as the sound of a piano or a drum.
</div>
