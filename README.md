# Project-Real-Time-Mask-Detector-YOLOv4

In this repository, we build a program to detect whether a perosn is wearing a mask or not, i.e., a mask detector. 
The situation is as follows: we have a camera that records video of a very busy 
area (for example, the entrance of a shopping center, a school, etc.) and we want 
to detect in real time if someone is not wearing a mask in order to warn him or prevent
him from passing. The "real-time" condition suggests using models that can perform this 
task in one-stage, such as YOLO, SSD or RetinaNet. However, two-stage models can still 
perform well, since the number of classes is not too high. In this project we will use 
YOLOs latest version, YOLOv4, as our detector.

This repository belongs to the post [Real-time object detection
](https://mathchine-learning.blogspot.com/2020/10/real-time-object-detection-yolov4.html) from my blog [Mathchine Learning](https://mathchine-learning.blogspot.com/).
I recommend reading the post before going any further, where all the technical details are.
