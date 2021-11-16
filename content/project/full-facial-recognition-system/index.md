---
title: Full Facial Recognition System
date: 2021-11-02T19:22:36.721Z
summary: I had to implement and design a low-cost full facial recognition
  system. I used YOLOV5 and SphereFace to do the face detection and recognition.
  I also implemented a face alignment and other parts of the system using
  Python/Pytorch, and OpenCV.
draft: false
featured: false
tags:
  - Python
  - Pytorch
  - Deep Learning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Most of the Deep learning methods are not practical for real-world applications because they are too large and computationally expensive. One of the most popular applications that suffer from this problem is Face Recognition. I deployed a Full Facial Recognition system that consumes negligible power and memory compared to other big DNNs. that first detects people’s faces in the picture. After properly aligning the faces, I used a face recognition model to recognize the identity of the faces. YOLOV5 was used for face detection and SphereFace for face recognition. I implemented the project using Pytorch and OpenCV frameworks.