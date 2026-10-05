---
# Sequence ID (lowest number (0) appears first on the page)
sequence_id: 4

# Season (pages for the appropriate season will automagically pool all speakers that gave a talk in the season)
season: winter2026

# Name of the speaker
name: Makram Chahine

# Link to the speaker's webpage
webpage: https://makramchahine.github.io/

# Primary affiliation of the speaker
affil: MIT
# Position at the primary affiliation
position: PhD Student
# Link to the speaker's primary affiliation
affil_link: https://www.mit.edu/

# Secondary affiliation of the speaker
affil2:
# Position at the secondary affiliation
position2:
# Link to the speaker's secondary affiliation
affil2_link:

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: makram.jpg

# Talk title
title: "From Internet to Edge and Back"

# Date of the talk
talkdate: 19 February 2026

# Time of the talk
talktime: 11:00 hrs ET

# Link to the talk
talklink: https://www.youtube.com/embed/az9KQJmm8bc?si=SKV5qqvDYipD4ZGi

# Talk abstract (from the YouTube description)
abstract: |-
  Modern Robotics faces a central dilemma: unprecedented access to internet-scale models for digital perception and reasoning, contrasted with uncompromising constraints of the physical world. The challenge lies in bridging these high-level capabilities with real-time edge compute, limited connectivity, and safety-critical demands, all while operating on demonstration datasets that are orders of magnitude smaller than the trillions of tokens fueling frontier foundation models. This talk explores both ends of the efficiency spectrum: first, through decentralized algorithms that leverage foundation models to enable high-stakes swarm wildlife monitoring, and second, through in-training architectural compression techniques to make large models viable on the edge. First, we go from internet to edge: bringing state-of-the-art vision models onto a swarm of drones for autonomous sperm whale monitoring as part of Project CETI. We present a fully decentralized pipeline covering scouting, detection, motion planning, multi-agent registration, goal assignment, and individual monitoring execution.Next, we go from edge back to training: asking whether large models can be reduced during training itself. We introduce CompreSSM, a control-theoretic framework that leverages Hankel singular values and balanced truncation to progressively compress State Space Models while they learn, with gains on both training and inference computational costs.Together, the two works trace a full loop: digital intelligence deployed on physical robots, and physical resource constraints feeding back to reshape how we train models in the first place.
---

<!-- Whatever you write below will be disregarded -->
