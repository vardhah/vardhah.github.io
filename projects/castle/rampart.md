---
layout: work
title: "RAMPART: Reinforcement Against Malicious Penetration by Adversaries in Realistic Topologies"
authors: "Himanshu Neema, Daniel Balasubramanian, <strong>Harsh Vardhan</strong>, Sandeep Neema"
venue: "CPSIoTWeek 2024"
permalink: /projects/castle/rampart/
project_name: "DARPA CASTLE"
project_url: /projects/castle/

links:
  - label: "Paper"
    url: "https://arxiv.org/abs/2405.xxxxx"
  - label: "DARPA CASTLE"
    url: "https://www.darpa.mil/research/programs/cyber-agents-for-security-testing-and-learning-environments"

key_stats:
  - value: "$6.89M"
    label: "Program Grant"
  - value: "RL"
    label: "Approach"
  - value: "APT"
    label: "Threat Model"

media:
  - source: "Vanderbilt Engineering"
    title: "Vanderbilt Team Leads $6.89 Million DARPA Grant to Train Cyber Agents Against Attacks"
    url: "https://engineering.vanderbilt.edu/2023/12/12/vanderbilt-team-leads-6-89-million-darpa-grant-to-train-cyber-agents-against-attacks/"
  - source: "DARPA — Trilateral"
    title: "DARPA Collaborates with UK and Canadian Partners in First Trilateral Project"
    url: "https://www.darpa.mil/news/2024/first-trilateral-project"
---

## Overview

RAMPART develops reinforcement learning-based AI agents that can autonomously defend computer networks against advanced persistent threats (APTs). The system creates realistic network topologies and trains defender agents through adversarial interaction with attacker agents in a "cyber gym" environment.

<!-- Replace with your architecture diagram -->
![RAMPART Architecture](/images/thumbnails/rampart.png)

## Approach

The RAMPART framework addresses three core challenges:

- **Realistic Environment Generation** — Instantiating network topologies that faithfully represent real-world enterprise and OT networks, including vulnerabilities, configurations, and traffic patterns.
- **Adversarial Training** — Training defender agents against progressively sophisticated attacker agents using multi-agent reinforcement learning.
- **Transferability** — Ensuring trained agents can generalize to unseen network configurations and novel attack strategies.

<!--
## Demo

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
</div>
-->

## Key Contributions

My contributions to RAMPART include the design and implementation of the realistic network environment generator, the integration of reinforcement learning algorithms for the defender agent, and evaluation of the system against standard cyber attack benchmarks.
