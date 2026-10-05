---
# Sequence ID (lowest number (0) appears first on the page)
sequence_id: 0

# Season (pages for the appropriate season will automagically pool all speakers that gave a talk in the season)
season: winter2021

# Name of the speaker
name: Steven Waslander

# Link to the speaker's webpage
webpage: http://trailab.utias.utoronto.ca/

# Primary affiliation of the speaker
affil: University of Toronto
# Position at the primary affiliation
position: Associate professor
# Link to the speaker's primary affiliation
affil_link: https://www.utoronto.ca/

# # Secondary affiliation of the speaker
# affil2: NVIDIA
# # Position at the secondary affiliation
# position2: Senior research scientist
# # Link to the speaker's secondary affiliation
# affil2_link: https://www.nvidia.com/en-us/research/

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: waslander.jpg

# Talk title
title: Probabilistic Object Detection for Autonomous Driving

# Date of the talk
talkdate: 15 January 2021

# Time of the talk
talktime: 1600 hrs ET

# Link to the talk
talklink: https://www.youtube.com/embed/z3mXvchZ048

# Talk abstract (from the YouTube description)
abstract: |-
  Modern object detection has relentlessly pursued perfection on a single metric: mean average precision, with impressive gains in performance across datasets and sensor types over that last few years.   I will discuss our multiple contributions in this domain, particularly in 3D object detection with monocular, stereo and LIDAR/camera fusion.  Our work has regularly topped the Kitti Vision Benchmark, and emphasizes the value of attention focused on object shape to enhance localization and extent estimation. Despite the strong progress in this domain, current network outputs are primarily deterministic, providing little visibility beyond class confidence as to the probability a detection is accurate.  This makes current object detectors a black box for downstream processes such as tracking and prediction, and can lead to over confidence in low-quality detection.  To help address this challenge, I will discuss our recent work on probabilistic object detectors (PODs) on two fronts.  First, I will describe efforts to place the evaluation of PODs on a secure footing, by introducing proper scoring rules with both local and global extent that can determine whether a predictive distribution is both well calibrated and discriminative.  Then, I will discuss our work BayesOD,  a novel probabilistic object detector that exhibits strong output distribution prediction capabilities and outperforms existing PODs in terms of calibration and sharpness.
---

<!-- Whatever you write below will be disregarded -->
