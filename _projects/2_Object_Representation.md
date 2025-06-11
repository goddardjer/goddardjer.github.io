---
layout: post
title: Object Representation for RL
description: Modifing the presentation of shape and pose information to find allow beter generalization
---

Title : An Analysis of The Effects of Object Representation on Shape Generalization
=========

Authors : **Jeremiah Goddard**, Nigel Swenson, Xiaoli Fern, Ravi Balasubramanian, Cindy Grimm

<div style="text-align: center;">
  <img src="{{ '/assets/Sim_Real.png' | relative_url }}" alt="Object Rep Image" style="max-width: 1200px; width: 90%; height: auto;" />
</div>

Abstract : 
----------
Robotic in-hand manipulation tasks are difficult control problems which are often solved using reinforcement learning (RL). How to present the shape and pose information of objects to the policy is still an open question. In this work we analyze how the presentation of shape and pose information affects the ability of a RL policy to learn and generalize to unseen shapes. We use a sliding task to show that some methods may perform better in simulation but, policies that contain the same information perform similarly in the real world. We also show that there is no benefit in performance when a state space contains repeat information in different formats.

<div style="text-align: center;">
  <video width="600" autoplay muted loop playsinline>
    <source src="{{ '/assets/Thesis_Vid.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>


[**Repository**](https://github.com/OSUrobotics/mojo-grasp)
