---
layout: work
title: "Deep Active Learning for Regression Using ε-weighted Hybrid Query Strategy"
authors: "<strong>Harsh Vardhan</strong>, Janos Sztipanovits"
venue: "ReALML Workshop, International Conference on Machine Learning (ICML 2022), Baltimore"
permalink: /projects/sdcps/deep-al-regression/
project_name: "DARPA SDCPS"
project_url: /projects/sdcps/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2206.13298"
---

## Overview

Presented at the ICML 2022 ReALML (Responsible AI and Machine Learning) workshop. Introduces an ε-weighted hybrid query strategy for deep active learning in regression tasks, combining uncertainty-based and diversity-based sampling for improved data efficiency.

## Approach

The hybrid query strategy balances:
- **Uncertainty sampling** — selecting points where the model is least confident
- **Diversity sampling** — ensuring coverage of the input space
- **ε-weighting** — adaptive balancing between the two strategies based on training progress

<!--
Add figures:
![Query strategy comparison](/images/dal-query-comparison.png)
-->
