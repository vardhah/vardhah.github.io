---
layout: project
title: "UUV Design Optimization"
eyebrow: "DARPA SDCPS · Engineering Design"
lead: "AI-driven Bayesian optimization, deep learning surrogates, and integrated CAD-CFD toolchains for autonomous design of underwater vehicle hulls and propellers — achieving 100× speedup over traditional methods."
permalink: /projects/uuv-design/

key_stats_title: "Key Results"
key_stats_desc: "First study applying Bayesian optimization and DNN surrogates to UUV hull design."
key_stats:
  - value: "46%"
    label: "Drag Reduction (67N → 36N)"
  - value: "100×"
    label: "Speedup vs Traditional CFD"
  - value: "1.85%"
    label: "Surrogate MAPE"

works:
  - title: "Anvil: An Integration of AI, Sampling Techniques, and a Combined CAD-CFD Tool"
    authors: "<strong>H. Vardhan</strong>, U. Timalsina, M. Sandborn, D. Hyde, P. Völgyesi, J. Sztipanovits"
    venue: "DESTION@CPSIoTWeek 2024"
    url: /projects/uuv-design/anvil/
    thumbnail: /images/thumbnails/anvil.png
    tags: [Toolchain, CAD-CFD, AI]

  - title: "Search for Universal Minimum Drag Resistance Underwater Vehicle Hull Using CFD"
    authors: "<strong>H. Vardhan</strong>, J. Sztipanovits"
    venue: "ICCES 2023 (Springer)"
    url: /projects/uuv-design/min-drag-hull/
    thumbnail: /images/thumbnails/min-drag.png
    tags: [CFD, Hull Design]

  - title: "Data Efficient Surrogate Modeling: Ensemble-free Batch Mode Deep Active Learning"
    authors: "<strong>H. Vardhan</strong>, U. Timalsina, P. Völgyesi, J. Sztipanovits"
    venue: "arXiv 2022 (submitted to EAAI)"
    url: /projects/uuv-design/deep-active-learning/
    thumbnail: /images/thumbnails/deep-al.png
    tags: [Active Learning, Surrogate]

  - title: "Deep Active Learning for Regression Using ε-weighted Hybrid Query Strategy"
    authors: "<strong>H. Vardhan</strong>, J. Sztipanovits"
    venue: "ReALML Workshop, ICML 2022"
    url: /projects/uuv-design/deep-al-regression/
    thumbnail: /images/thumbnails/deep-al-icml.png
    tags: [ICML, Active Learning]
---

My research develops an automated pipeline integrating **FreeCAD** (parametric design), **OpenFOAM** (CFD simulation), and **AI optimization** (Bayesian optimization + deep learning surrogates) to dramatically accelerate the UUV design process. All research code is [open-sourced on GitHub](https://github.com/vardhah).
