---
layout: post
title: "Efficient Convolutional Network Learning — ScatterNet" 
author: hanoch
tags: [deep learning, ai, CNN]
categories: [deep learning, ai, CNN]
image: assets/images/ScatterNet.png
style: fill
color: success
description: ScatterNets incorporates geometric knowledge of images to produce discriminative and invariant features. The same outcome as CNN's first layers hold.
---

Source: [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7244236722761338880)
When I led a DNN project based on few data ~20K examples for biometric ID, based on poor quality modality, 
I was trying to find out ways of incorporating prior knowledge to CNN in order to ease the data scale 
requirements for training. 

Then I’ve found the ScatterNet idea which is a nice trick in terms of using a fixed and known 
structure of Wavelets based complex tree borrowed from the image processing domain.
