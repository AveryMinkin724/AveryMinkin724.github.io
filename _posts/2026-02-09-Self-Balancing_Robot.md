---
title: "Self Balancing Robot"
layout: post
category: engineering
tags: [embedded, RTOS, control-systems, robotics]
---

## Overview
I designed and built a two-wheel, self-balancing robot using a custom, lightweight RTOS on the Tiva C LaunchPad.



## Technical Highlights
- Custom RTOS (Based on MIROS from Miros Samek's Qunatum Leaps Course)
- MPU6050 IMU with Complementary filter
- PID control loop
- UART/Bluetooth logging and parameter adjustment
- Deterministic task scheduling for control loop
- Motor control via PWM + L298N driver

## Architecture
<img src="/assets/media/sbp_image.jpeg" width="720" alt="Self-Balancing Robot Image">

## Key Challenges
- Real-time scheduling and task prioritization
- Sensor fusion and noise filtering
- Stability tuning of PID parameters

## Demo
<video width="720" controls>
  <source src="/assets/media/sbp_video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>



