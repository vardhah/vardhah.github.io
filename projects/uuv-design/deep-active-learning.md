---
layout: work
title: "Data Efficient Surrogate Modeling for Engineering Design: Ensemble-free Batch Mode Deep Active Learning for Regression"
authors: "<strong>Harsh Vardhan</strong>, Umesh Timalsina, Péter Völgyesi, Janos Sztipanovits"
venue: "arXiv 2022 (submitted to Engineering Applications of Artificial Intelligence)"
permalink: /projects/uuv-design/deep-active-learning/
project_name: "UUV Design Optimization"
project_url: /projects/uuv-design/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2211.10360"
  - label: "Code"
    url: "https://github.com/vardhah/Batch-mode-DeepAL-for-regression"
---

## Overview

Engineering design optimization requires expensive simulations (CFD, FEA). This work develops an **ensemble-free batch mode deep active learning** method for building accurate surrogate models with minimal training data — critical for making AI-driven design practical.

## Key Contributions

- **Ensemble-free** approach — avoids the computational overhead of maintaining model ensembles
- **Batch mode** — selects multiple informative samples per iteration for parallel simulation
- **Regression-focused** — designed for continuous engineering metrics, not just classification
- Demonstrated on UUV hull design and other engineering benchmarks

<!--
Add figures:
![Active learning convergence](/images/deep-al-convergence.png)
![Sample efficiency comparison](/images/deep-al-comparison.png)
-->
