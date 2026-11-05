---
# Sequence ID (lowest number (0) appears first on the page)
sequence_id: 4

# Season (pages for the appropriate season will automagically pool all speakers that gave a talk in the season)
season: fall2026

# Name of the speaker
name: "Kensuke Nakamura"

# Link to the speaker's webpage
webpage: https://kensukenk.github.io/

# Primary affiliation of the speaker
affil: "CMU"
# Position at the primary affiliation
position: "Ph.D. student"
# Link to the speaker's primary affiliation
affil_link: https://cmu-intentlab.github.io

# Secondary affiliation of the speaker
affil2: 
# Position at the secondary affiliation
position2: 
# Link to the speaker's secondary affiliation
affil2_link: 

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: kensuke_nakamura.jpg

# Talk title
title: "Safety in a Learned World: When and how can world models help keep robots safe?"

# Date of the talk
talkdate: 5 November 2026

# Time of the talk
talktime: 11:00 hrs ET

# Link to the talk
talklink: https://www.youtube.com/embed/0Wsk-VZum_I

# Talk abstract
abstract: |-
  As robot policies operating from high-dimensional visual observations become increasingly capable, they will encounter safety constraints—such as avoiding spills, breakage, or overheating—that are difficult to express using conventional state and dynamics models. This talk explores when and how learned world models can help bridge that gap. I will begin by introducing latent safety filtering, a framework that performs safety analysis within a learned world model to enable robots to respond safely to these hard-to-model constraints.
  
  The remainder of the talk will examine the challenges that arise when both the dynamics and state representation are learned from data. First, learned autoregressive dynamics suffer from compounding error, so safety learning should not require globally accurate, long-horizon imagination. I will show how broad state coverage in offline data enables training with short local rollouts where the WM is reliable, while coverage of task-policy actions ensures that the learned safety critic remains accurate where it is queried at deployment. This process amortizes expensive world-model-based safety reasoning into a state-action value function, allowing the safety filter to efficiently evaluate thousands of candidate actions online and smoothly steer modern generative policies toward safe and successful task execution. I will then reveal potential issues that arise when learning state representations from observation data. Using temperature-based safety constraints as a testbed, I will quantify when safety-relevant quantities can be estimated from observations. I will show how insufficient information at deployment can produce myopic strategies that avoid observing failure rather than avoiding failure itself, and present experimental evidence that multimodal representation learning can improve the resulting safety behavior.
  
  Overall, although all world models are wrong, this talk argues appropriately understanding their limits reveals strategies that allow them to still be useful for safety.
---

<!-- Whatever you write below will be disregarded -->
