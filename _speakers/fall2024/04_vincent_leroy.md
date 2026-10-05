---
# Sequence ID (lowest number (0) appears first on the page)
sequence_id: 4

# Season (pages for the appropriate season will automagically pool all speakers that gave a talk in the season)
season: fall2024

# Name of the speaker
name: "Vincent Leroy"

# Link to the speaker's webpage
webpage: https://europe.naverlabs.com/people_user_naverlabs/vincent-leroy/

# Primary affiliation of the speaker
affil: "NAVER LABS Europe"
# Position at the primary affiliation
position: "Research Scientist"
# Link to the speaker's primary affiliation
affil_link: https://europe.naverlabs.com/

# Secondary affiliation of the speaker
affil2: 
# Position at the secondary affiliation
position2: 
# Link to the speaker's secondary affiliation
affil2_link: 

# An image of the speaker (square aspect ratio works the best) (place in the `assets/img/speakers` directory)
img: vincent_leroy.jpg

# Talk title
title: "From CroCo to MASt3R: A Paradigm Change in 3D Vision"

# Date of the talk
talkdate: 7 November 2024

# Time of the talk
talktime: 11:30 hrs ET

# Link to the talk
talklink: https://www.youtube.com/embed/OJzj7uCCYaM

# Talk abstract (from the YouTube description)
abstract: |-
  In the rapidly evolving field of 3D vision, a multitude of heterogeneous downstream tasks coexist, such as visual localization, depth estimation, 3d reconstruction, etc. The current paradigm is to develop a dedicated method to solve each task, thereby largely ignoring their potential inter-connections and synergies. Developing unified models able to handle multiple 3D geometric downstream tasks remains a challenge. This presentation introduces three interconnected advancements in this respect: CroCo, DUSt3R and MASt3R. CroCo, a self-supervised pre-training framework, utilizes a pretext task to lay foundations for DUSt3R/MASt3R, a unified foundational model for geometric 3D vision. Cross-view completion, or CroCo in short, first serves to learn robust representations of 3D geometry from pairs of images depicting the same scene from different viewpoints. By masking parts of an image and predicting these given another viewpoint of the scene, CroCo effectively captures priors about spatial relationships and geometric information, setting a strong foundation for downstream 3D vision tasks. Then, building on the robust pre-trained models provided by CroCo, DUSt3R introduces a novel approach for Dense Unconstrained Stereo 3D Reconstruction. This method revolutionizes traditional multi-view stereo reconstruction by regressing pointmaps that encode scene geometry without requiring calibrated or posed cameras. DUSt3R simplifies the complex pipeline of traditional 3D reconstruction methods, significantly reducing computational overhead and enhancing performance across various benchmarks. MASt3R further extends DUSt3R by adding the ability to establish accurate pixel correspondences. The journey from CroCo to MASt3R exemplify a significant paradigm shift in 3D vision technologies. This presentation will delve into the methodologies, innovations, and synergistic integration of these frameworks, demonstrating their impact on the field and potential future directions. The discussion aims to highlight how these advancements unify and streamline the processing of 3D visual data, offering new perspectives and capabilities in robotic navigation, cultural heritage preservation, and beyond.
---

<!-- Whatever you write below will be disregarded -->
