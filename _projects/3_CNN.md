---
layout: post
title: CNN For Sterioscopic Images
description: Training a CNN to classify areas around SIFTs in steroscopic images and matching the points to calculate fundamental matrix
---

Learning Local Feature Descriptors with CNNs
=========

<div style="text-align: left;">
  <img src="{{ '/assets/matches.png' | relative_url }}" alt="Matching Image" style="max-width: 1200px; width: 100%; height: auto;" />
</div>

In this project, I trained a Convolutional Neural Network (CNN) to learn local feature descriptors using the Photo Tourism dataset ([http://phototour.cs.washington.edu/](http://phototour.cs.washington.edu/)). Once the CNN was trained it could classify local descriptors from many different angles. I then used this CNN to find the fundaental matrix for steroscopic image pairs. The pipeline for doing this involved the following steps:

- Extracted the top 100 most prominent SIFT keypoints from stereoscopic image pairs, excluding duplicates.
- Generated 32x32 grayscale patches around each SIFT keypoint.
- Used the trained CNN to compute local feature descriptors for each patch.
- Matched patches between image pairs by computing the Euclidean distance between descriptors, selecting the top 50 closest pairs.
- Applied the 8-point algorithm with RANSAC to the matched pairs to robustly estimate the fundamental matrix.
- Visualized epipolar geometry by computing epipoles and epipolar lines for each image pair.

This project combined deep learning and classical computer vision techniques to learn and apply local image descriptors for stereo correspondence and geometric reasoning.
