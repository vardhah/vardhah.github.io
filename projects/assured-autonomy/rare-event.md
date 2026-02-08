---
layout: work
title: "Rare Event Failure Test Case Generation in Learning-Enabled-Controllers"
authors: "<strong>Harsh Vardhan</strong>, Janos Sztipanovits"
venue: "ACM International Conference on Machine Learning Technologies (ICMLT 2021), South Korea"
permalink: /projects/assured-autonomy/rare-event/
project_name: "DARPA Assured Autonomy"
project_url: /projects/assured-autonomy/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2206.05533"
  - label: "ACM Digital Library"
    url: "https://dl.acm.org/doi/abs/10.1145/3468891.3468897"
---

## Overview

For well-trained ML models deployed in safety-critical autonomous systems, failures are rare but potentially catastrophic. Exhaustive search or random testing is prohibitively expensive. This work addresses the challenge of finding these failure scenarios faster than traditional randomized search.

## Approach

The central idea is to separate the input data space into regions of high failure probability and regions of low/minimal failure probability. This separation is informed by:

- Training data observations
- Data drawn from real-world statistics
- Domain knowledge about the system's operating conditions

By focusing search efforts on high-probability failure regions, we achieve significantly faster discovery of safety-critical edge cases compared to uniform random sampling.

## Relevance to Assured Autonomy

This work directly addresses the DARPA Assured Autonomy program's core challenge: **verifying correctness of learned components** in autonomous systems. By efficiently finding failure modes, we enable designers to retrain and improve models before deployment, contributing to the formal safety assurance pipeline.

<!--
Add your figures here:
![Failure region separation](/images/rare-event-regions.png)
![Search efficiency comparison](/images/rare-event-results.png)
-->
