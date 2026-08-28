---
layout: page
title: Real-time 3D Vision Motion Capture
description: A real-time motion-capture system developed during my internship.
img: assets/img/12.jpg
importance: 1
category: work
selected: true
---

## Overview

This project was developed during my internship at Noitom in Beijing in July 2026. The system recognizes 2D human keypoints from multiple cameras, reconstructs 3D human pose through triangulation and inverse kinematics (IK), and retargets the resulting motion to different digital avatars. It also supports high-precision hand tracking.

The pipeline was extensively optimized for real-time performance. On a machine equipped with an NVIDIA RTX 4090, it can stably process 8 camera streams, 3 people, and 3 pairs of hands at 30 FPS.

## Highlights

- Designed and integrated the real-time 3D vision motion-capture pipeline.
- Worked on multi-camera data processing, pose estimation, and 3D reconstruction.
- Focused on stable, low-latency output suitable for live demonstrations.

## Demo

GIFs are supported directly. To add a demo animation, put the file at `assets/img/mocap-demo.gif` and uncomment the image below:

<!--
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    <img src="{{ '/assets/img/mocap-demo.gif' | relative_url }}"
         alt="Real-time 3D vision motion-capture demo"
         class="img-fluid rounded z-depth-1" />
  </div>
</div>
<div class="caption">
  Real-time 3D vision motion-capture demo.
</div>
-->

The project details and media will be updated as more results are organized.
