---
title: Blind Data-Free Attack
date: 2021-11-03T19:29:24.578Z
summary: >-
  I developed various methods to do an optimal bit-flip attack on DNN’s
  parameters\

  without using any data. I used Python/Pytorch in this project.
draft: false
featured: false
tags:
  - Python
  - Pytorch
  - Deep Learning
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
Adversarial parameter attacks are well-known bit-flip attacks that try to flip a few bits of DNNs parameters to crush their functionality. However, these attacks are not always performable since the attacker may not have access to data for many applications containing sensitive or proprietary data. For example, medical and  biometric datasets are not available for everyone due to privacy and security concerns.In this project, I deployed several approaches to attack DNN parameters without having access to any training/test data. One of the methods was able to decrease the accuracy of ResNet50 to 12% on the CIFAR100 dataset.