---
title: "Self Balancing Robot"
layout: post
category: engineering
tags: [embedded, RTOS, control-systems, robotics]
---

## Overview
I designed and implemented a two-wheel self-balancing robot using a custom lightweight RTOS on the Tiva C LaunchPad.

## Technical Highlights
- Custom RTOS (MIROS-based)
- MPU6050 IMU with Kalman filter
- PID control loop
- UART logging and task scheduling
- Motor control via PWM + L298N driver

## Architecture
(you can add diagrams, images, code snippets here)

## Key Challenges
- Real-time scheduling and task prioritization
- Sensor fusion and noise filtering
- Stability tuning of PID parameters

## Demo
(Add video, images, or GitHub link)
🔍 Step 3: Will it automatically show on your Engineering Portfolio page?
This depends on how your portfolio page is coded.

Case A — ✅ Auto-generated posts (best case)
If your engineering page contains something like:

{% for post in site.posts %}
  {% if post.category == "engineering" %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}
✅ Then you’re done.
Your new post will appear automatically.

Case B — ❌ Manual listing (common in portfolios)
If your engineering page looks like this instead:

<li><a href="/2024/11/20/thesis.html">Thesis</a></li>
<li><a href="/2024/10/10/capstone.html">Capstone</a></li>
<li><a href="/2024/09/05/vr-project.html">VR Project</a></li>
❗ Then you must manually add your new post link.

💡 I can check this precisely for your site
If you want, I can:

✅ Inspect your engineering portfolio page code
✅ Tell you EXACTLY whether your site auto-detects posts or not
✅ Tell you exactly what file to edit
✅ Write the perfect self-balancing robot post for your portfolio (resume-grade)

If you want, paste your engineering page file or I’ll pull it from your repo and walk you through it step-by-step.



