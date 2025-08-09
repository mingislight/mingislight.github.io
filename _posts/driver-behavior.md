---
layout: post
title: "Driver Safety with Computer Vision and Deep Learning: How AI Detects Distraction and Fatigue"
date: 2024-02-14
author: Ming Chu
tags: [Computer Vision, Machine Learning, Autonomous Vehicles, Research]
image: /assets/img/driver-behavior-classification.png
description: "First-author research using CNN and BiLSTM deep learning models to detect distracted and drowsy driving in real time, improving road safety and supporting autonomous vehicle technology."
keywords: "driver safety, driver distraction, computer vision, deep learning, CNN, LSTM, BiLSTM, autonomous vehicles, driver monitoring system, vision transformer"
---

![Driver Behavior Classification Overview](/assets/img/driver-behavior-classification.png)

## Why This Matters

Driver distraction is one of the leading causes of accidents.  
In those moments, **seconds decide lives**.

Our goal was simple: build an AI system that spots distraction or fatigue in real time so drivers can be alerted before it’s too late.

---

## From Research to Stage

This work began as my graduate research and became the focus of my **3-Minute Thesis presentation**.  
In three minutes, I shared how computer vision and deep learning can detect driver distraction and drowsiness.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
  <iframe 
    src="https://www.youtube.com/embed/ezQxikFTFGs?si=tt_SugehJRr1L_GW" 
    title="3MT Presentation" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  </iframe>
</div>

---

## Published in the Journal of Big Data

The research was later published in the [Journal of Big Data (Springer Open)](https://link.springer.com/article/10.1186/s40537-024-00890-0):

**"Comprehensive Study of Driver Behavior Monitoring Systems Using Computer Vision and Machine Learning Techniques"**

The system reached **99.1% accuracy** in detecting distraction and fatigue — a strong step toward safer roads.

---

## How It Works

We combined three AI models:

- **CNN (Convolutional Neural Networks)** — Spot visual details like eye position and head angle.  
- **BiLSTM (Bidirectional Long Short-Term Memory)** — Track behavior changes over time in both directions.  
- **ANN (Artificial Neural Networks)** — Classify the driver’s state as alert, distracted, or drowsy.

This detects subtle signs like a quick gaze shift, drooping eyelids, or hands leaving the wheel.

---

## The Real-World Goal

If built into vehicles, this system could:

- Reduce accidents caused by human error.  
- Improve **Advanced Driver Assistance Systems (ADAS)**.  
- Add a safety layer for semi-autonomous and autonomous driving.

---

## Looking Ahead

The next step is using **Vision Transformers (ViT)** trained on **large, real-world driving datasets**.

This will mean:

- Better accuracy in complex environments.  
- Improved adaptability to different weather and regions.  
- Stronger safety when combined with data from radar, LiDAR, and driver biometrics.

---

## What I Learned

This project strengthened my skills in:

- Designing and tuning deep learning models.  
- Explaining complex ideas clearly.  
- Building technology that serves people.

It confirmed one truth for me: **technology is worth building only if it protects and serves people**.

---

## Read the Full Paper

[**Comprehensive Study of Driver Behavior Monitoring Systems Using Computer Vision and Machine Learning Techniques**](https://link.springer.com/article/10.1186/s40537-024-00890-0)

---

[← Back to Blog](/blog)
