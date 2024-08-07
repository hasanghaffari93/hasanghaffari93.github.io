---
layout: page
title: AI-Powered Sorting Machine
description: Jarfabin Co
img: assets/img/jarfabin/3.png
importance: 2
category: work
related_publications: false
---


##### **Role in Company**
**Computer Vision Researcher and Developer**

- Designed deep and multi-view Convolutional Neural Networks (CNN) to classify pistachio nut
- Trained multi-class classification models on 250k of 4-view pistachio nuts
- Deployed model optimization techniques including hyperparameter tuning and post-training quantization to reduce inference time on edge devices
- On-device model inference on Raspberry Pi and Jetson Nano Developer Kit in real-time
- Designed GUI for the training pipeline, including dataset selection, preprocessing, augmentation, multiple training, fine-tuning, and result visualization
- Designed a protocol design of data collection and multi-stage accurate labelling


<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/jarfabin/3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An overview of the 1st vesion of sorting machine
</div>




##### **Product Description**

Utilizing advanced AI and machine vision technology, this fully automated machine is designed to classify pistachios into different classes. The Sorting Machine integrates mechanical, electronic, software, AI, and industrial design to deliver precise sorting with high capacity. Here's how it works:



1. Pistachios are loaded into a large hopper.
2. A conveyor belt transports the pistachios into the machine.
3. Using a complex mechanical mechanism, the pistachios are arranged in a single file.
4. The pistachios are then released at high speed in free fall, passing through a dark box.
5. During this brief moment, four cameras capture images of each pistachio from different views.
6. The images are processed by an AI model that classifies the pistachios.
7. Based on the classification, high-pressure air directs the pistachios into their designated boxes.




<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/jarfabin/1.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    How it works?
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/jarfabin/2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sample 4-view pistachio nuts for different classes
</div>


