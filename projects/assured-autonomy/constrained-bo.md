---
layout: work
title: "Constrained Bayesian Optimization for Automatic Underwater Vehicle Hull Design"
authors: "<strong>Harsh Vardhan</strong>, Péter Völgyesi, Will Hedgecock, Janos Sztipanovits"
venue: "CPS-IoT Week Workshops (ACM) 2023, San Antonio"
permalink: /projects/assured-autonomy/constrained-bo/
project_name: "DARPA Assured Autonomy"
project_url: /projects/assured-autonomy/

links:
  - label: "ACM Digital Library"
    url: "https://dl.acm.org/doi/abs/10.1145/3576914.3587530"
  - label: "arXiv"
    url: "https://arxiv.org/abs/2302.14732"
  - label: "Code"
    url: "https://github.com/vardhah/ConstraintBOUUVHullDesign"

key_stats:
  - value: "46%"
    label: "Drag Reduction"
  - value: "67N → 36N"
    label: "At 1.1 m/s"
  - value: "Open Source"
    label: "GitHub"
---

## Overview

Developed an integrated CAD-CFD-AI toolchain for automated UUV hull optimization. The pipeline uses **constrained Bayesian optimization** with FreeCAD for parametric design and OpenFOAM for CFD simulation, respecting physical manufacturing constraints throughout the optimization.

## Key Results

- Drag force optimized from **67N to 36N** at 1.1 m/s (46% reduction)
- Bayesian optimization demonstrated as the most **sample-efficient** method for UUV design
- Constraints on manufacturing feasibility integrated directly into the optimization loop

## Pipeline

1. **FreeCAD** — Parametric hull geometry generation
2. **OpenFOAM** — CFD simulation for drag evaluation
3. **Constrained BO** — Intelligent selection of next design candidates while respecting physical constraints

<!--
Add your figures:
![Hull optimization pipeline](/images/hull-pipeline.png)
![Optimization convergence](/images/hull-convergence.png)
![Optimal hull geometry](/images/hull-optimal.png)
-->
