---
# Sequence ID (lowest number (0) appears first on the page)
sequence_id: 7

# Season (pages for the appropriate season will automagically pool all speakers that gave a talk in the season)
season: fall2024

# Name of the speaker
name: "Sayantan Auddy"

# Link to the speaker's webpage
webpage: https://sayantanauddy.github.io/

# Primary affiliation of the speaker
affil: "Technical University of Berlin"
# Position at the primary affiliation
position: "Postdoctoral Researcher"
# Link to the speaker's primary affiliation
affil_link: https://www.tu.berlin/

# Secondary affiliation of the speaker
affil2: 
# Position at the secondary affiliation
position2: 
# Link to the speaker's secondary affiliation
affil2_link: 

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: sayantan_auddy.jpg

# Talk title
title: "Continual Learning for Robotic Manipulation"

# Date of the talk
talkdate: 28 November 2024

# Time of the talk
talktime: 11:30 hrs ET

# Link to the talk
talklink: https://www.youtube.com/embed/kNUKh8iLUjc

# Talk abstract
abstract: |-
  Humans continuously acquire new knowledge while retaining and refining what they have already learned. As robotics advances, continual learning is poised to become a critical feature, enabling robots to navigate the ever-changing demands of real-world environments. In this talk, I will discuss my work on continual learning of manipulation skills in real-world scenarios. Based on the nature of the continually learned tasks, my talk is divided into two parts.

  The first part addresses scenarios in which distinct manipulation tasks with different objectives need to be learned, such as opening a box or pouring from a cup. Here I will discuss "Continual Learning from Demonstration" (continual LfD), a method based on hypernetworks and neural ODEs that is used to learn a sequence of manipulation tasks from human demonstrations. This method effectively retains multiple LfD skills without storing or retraining on past demonstrations and requires only a few demonstrations per task. Next, I will discuss an approach to "stable" continual LfD, where we show that non-divergent, stable motion prediction improves continual learning performance and makes it possible to scale to a higher number of learned tasks and remember LfD tasks in high-dimensional spaces.

  The second part of my talk covers scenarios where the robot learns the same basic manipulation task but under varying environmental conditions. I will discuss "Continual Domain Randomization", a method that combines continual learning with domain randomization to achieve sim-to-real transfer. Here, a robot is trained in a sequence of differently randomized simulated environments and utilizes regularization-based continual learning to remember the effect of each environment. This results in a trained agent that can be directly transferred to the physical robot and exhibits robust zero-shot performance.
---

<!-- Whatever you write below will be disregarded -->
