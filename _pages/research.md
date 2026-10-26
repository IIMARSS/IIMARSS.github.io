---
layout: page
title: Research
permalink: /research/
description: Deep learning algorithms for spectral-spatial representation, hyperspectral image understanding, and reconstruction.
nav: true
nav_order: 1
---

My research focuses on the design of deep learning methods for hyperspectral image understanding and reconstruction. I study how neural networks represent high-dimensional spectral-spatial data, how spectral information is modeled and propagated, and how useful representations can be learned efficiently. My work spans image classification, hyperspectral unmixing, and super-resolution.

## Spectral-Spatial Representation Learning

I develop neural architectures that combine spectral dependencies with spatial context. My work explores 3D convolutions, spectral attention, multi-scale feature fusion, and retention-based modeling for hyperspectral image classification. I am interested in how architectural choices influence the information captured by a model and its ability to distinguish spectrally similar classes.

**Related work:** Spatial-Spectral Pyramid Network; Enhanced Spectral Fusion 3D CNN; HSRNet (accepted conference paper).

## Recurrent Modeling for Spectral Analysis and Reconstruction

I investigate recurrent representations for hyperspectral unmixing and super-resolution. My ongoing work includes recurrent endmember representation learning and spectral state propagation, with a focus on how spectral information is retained and refined during inference. These studies examine the role of recurrent modeling in spectral analysis and image reconstruction.

**Related manuscripts:** ERRNet: Recurrent Endmember Representation Learning for Hyperspectral Unmixing; Recurrent Spectral State Propagation for Hyperspectral Image Super-Resolution. Both manuscripts are under review.

## Knowledge Distillation and Efficient Neural Networks

I study how useful representations can be transferred from larger models to compact networks through knowledge distillation. My interests include the design of lightweight architectures and the relationship between predictive performance, representation quality, and computational cost. I also examine model robustness under changing imaging conditions.

**Related work:** FCRN (knowledge distillation); SpecRetNet (manuscript under review).

The [Publications]({{ '/publications/' | relative_url }}) page lists published work, accepted papers, and manuscripts under review separately. Details of my research experience and contributions are available on the [Projects]({{ '/projects/' | relative_url }}) page.
