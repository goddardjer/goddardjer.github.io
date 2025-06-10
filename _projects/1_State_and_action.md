---
layout: post
title: Evaluaing Transferability of Manipulation Policies
description: Evaluating state and action space combinations to transfer RL policies to different hands
---

Title : Evaluating the Effect of State and Action Selection on In-Hand Manipulation Performance for Transferability
=========

Authors : Nigel Swenson, **Jeremiah Goddard**, Xiaoli Fern, Ravi Balasubramanian, Cindy Grimm

<div style="text-align: center;">
  <img src="{{ '/assets/Alt_methods_figure_v7.PNG' | relative_url }}" alt="Transfer Image" style="max-width: 1200px; width: 50%; height: auto;" />
</div>

Abstract : 
----------
Reinforcement learning (RL) has demonstrated success across multiple robotic grasping and manipulation tasks. However, for RL to be widely applicable, policies must be able to transfer across the sim-to-real gap, and transfer to hand geometries that they are not trained on. Methods such as domain randomization and domain adaptation only partially help with bridging these gaps. In this letter, we explore the impact of state and action space selection on transferability across both the sim-to-real gap and across different hand geometries. Using two exemplar manipulation tasks we demonstrate that state and action space selection significantly affect the overall performance of a policy and its robustness to both types of transfer. We also show that, for both types of transfer, a reduced state space that avoids hand specific information is preferable, even when it provides less information than a full state space.

**DOI** : [10.1109/LRA.2025.3558699](https://doi.org/10.1109/LRA.2025.3558699)

