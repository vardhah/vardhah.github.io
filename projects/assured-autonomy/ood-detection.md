---
layout: work
title: "Reduced Robust Random Cut Forest for Out-of-Distribution Detection in Machine Learning Models"
authors: "<strong>Harsh Vardhan</strong>, Janos Sztipanovits"
venue: "International Journal of Machine Learning and Computing (IJMLC 2022)"
permalink: /projects/assured-autonomy/ood-detection/
project_name: "DARPA Assured Autonomy"
project_url: /projects/assured-autonomy/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2206.09247"
---

## Overview

When ML-based regressors receive inputs with significantly different statistical properties from their training data, predictions can be erroneous or hazardous. This work introduces a novel **Reduced Robust Random Cut Forest (RRRCF)** data structure for detecting out-of-distribution inputs — critical for safe deployment of autonomous systems.

## Key Contributions

- **Novel RRRCF algorithm** that works on both small and large datasets
- **Runtime OOD detection** for ML regressors — not just classifiers
- Applicable as a **runtime assurance monitor** for learning-enabled controllers in autonomous vehicles

## Relevance to Assured Autonomy

This directly addresses the AA program's need for **runtime monitoring** of learning-enabled components. When a deployed autonomous system encounters conditions outside its training distribution, the RRRCF detector flags the anomaly, triggering fallback safety behaviors.

<!--
Add your figures:
![RRRCF architecture](/images/rrrcf-arch.png)
![Detection results](/images/rrrcf-results.png)
-->
