---
layout: work
title: "Anvil: An Integration of AI, Sampling Techniques, and a Combined CAD-CFD Tool"
authors: "<strong>Harsh Vardhan</strong>, Umesh Timalsina, Michael Sandborn, David Hyde, Péter Völgyesi, Janos Sztipanovits"
venue: "DESTION@CPSIoTWeek 2024"
permalink: /projects/uuv-design/anvil/
project_name: "UUV Design Optimization"
project_url: /projects/uuv-design/

links:
  - label: "arXiv"
    url: "https://arxiv.org/abs/2407.02519"
  - label: "IEEE"
    url: "https://doi.org/10.1109/DESTION62938.2024.00009"
---

## Overview

Anvil is an end-to-end toolchain that integrates AI-driven optimization with sampling techniques and a combined CAD-CFD workflow. It provides a unified framework for engineering design optimization, automating the loop between parametric geometry generation, physics simulation, and intelligent design space exploration.

## Architecture

- **CAD Module** — FreeCAD-based parametric geometry generation
- **CFD Module** — OpenFOAM integration for fluid dynamics simulation
- **AI Module** — Bayesian optimization, deep learning surrogates, and active learning for sample-efficient exploration
- **Sampling Module** — Latin hypercube, Sobol sequences, and adaptive sampling strategies

<!--
Add your Anvil architecture diagram:
![Anvil architecture](/images/anvil-architecture.png)
-->
