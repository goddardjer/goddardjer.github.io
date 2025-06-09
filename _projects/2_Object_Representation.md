---
layout: post
title: Object Representation for RL
description: Modifing the presentation of shape and pose information to find allow beter generalization
---

Title : An Analysis of The Effects of Object Representation on Shape Generalization
=========

Authors : **Jeremiah Goddard**, Nigel Swenson, Xiaoli Fern, Ravi Balasubramanian, Cindy Grimm

<div style="text-align: center;">
  <img src="{{ '/assets/Sim_Real.png' | relative_url }}" alt="Object Rep Image" style="max-width: 600px; width: 75%; height: auto;" />
</div>

Abstract : 
----------
Robotic in-hand manipulation tasks are difficult control problems which are often solved using reinforcement learning (RL). How to present the shape and pose information of objects to the policy is still an open question. In this work we analyze how the presentation of shape and pose information affects the ability of a RL policy to learn and generalize to unseen shapes. We use a sliding task to show that some methods may perform better in simulation but, policies that contain the same information perform similarly in the real world. We also show that there is no benefit in performance when a state space contains repeat information in different formats.


