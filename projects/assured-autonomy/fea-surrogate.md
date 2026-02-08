---
layout: work
title: "Deep Learning-based FEA Surrogate for Sub-sea Pressure Vessel"
authors: "<strong>Harsh Vardhan</strong>, Janos Sztipanovits"
venue: "IEEE International Conference on Computer, Software, and Modeling, Rome, 2022"
permalink: /projects/assured-autonomy/fea-surrogate/
project_name: "DARPA Assured Autonomy"
project_url: /projects/assured-autonomy/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2206.03322"
  - label: "IEEE Xplore"
    url: "https://ieeexplore.ieee.org/document/9982714"
  - label: "Code"
    url: "https://github.com/vardhah/FEAsurrogate"
---

## Overview

Created deep learning surrogates for finite element analysis (FEA) of sub-sea pressure vessels. The DNN model approximates full FEA simulation results at a fraction of the computational cost, enabling rapid structural design evaluation for underwater autonomous systems.

## Approach

- Train a deep neural network on FEA simulation data (stress, displacement fields)
- Use the surrogate as a fast evaluator during design optimization loops
- Validated on sub-sea pressure vessel geometries relevant to UUV design

<!--
Add figures:
![FEA vs DNN comparison](/images/fea-comparison.png)
![Stress field prediction](/images/fea-stress.png)
-->
