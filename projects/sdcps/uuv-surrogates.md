---
layout: work
title: "Sample-Efficient and Surrogate-Based Design Optimization of Underwater Vehicle Hulls"
authors: "<strong>Harsh Vardhan</strong>, David Hyde, Umesh Timalsina, Péter Völgyesi, Janos Sztipanovits"
venue: "Ocean Engineering (Elsevier) 2024"
permalink: /projects/sdcps/uuv-surrogates/
project_name: "DARPA SDCPS"
project_url: /projects/sdcps/

links:
  - label: "Journal (ScienceDirect)"
    url: "https://www.sciencedirect.com/science/article/pii/S0029801824021152"
  - label: "Code"
    url: "https://github.com/vardhah/UUV-design-optimization"

key_stats:
  - value: "100×"
    label: "Speedup vs CFD"
  - value: "1.85%"
    label: "Surrogate MAPE"
  - value: "First"
    label: "BO + DNN for UUV Design"
---

## Overview

Peer-reviewed journal publication demonstrating Bayesian optimization and deep neural network-based surrogate modeling for UUV hull design. This is the **first study** applying both BO and DNN surrogates to underwater vehicle hull optimization.

## Key Results

- DNN surrogate achieves **1.85% mean absolute percentage error** compared to full CFD
- **Two-orders-of-magnitude speedup** over traditional CFD-in-the-loop optimization
- Bayesian optimization shown as the most **sample-efficient** method compared to genetic algorithms, random search, and grid search

## Approach

1. Generate training data via OpenFOAM CFD simulations over a design space
2. Train a DNN surrogate to predict drag force from hull geometry parameters
3. Use the surrogate within a Bayesian optimization loop for rapid convergence
4. Validate optimal designs with full CFD simulation

<!--
Add figures:
![Surrogate accuracy](/images/uuv-surrogate-accuracy.png)
![Optimization comparison](/images/uuv-bo-comparison.png)
-->
