---
layout: page
permalink: /publications/
title: Publications
description: Research publications and ongoing work in AI, Machine Learning, and Computer Vision.
nav: true
nav_order: 4
---

## Publications & Preprints

### [1] Using Large Language Models to Study Consumer Behavior: Review Algorithm Effects on Restaurant Selection
**U. Abid and B. Lim** &middot; Manuscript in preparation, 2026 &middot; *In progress*

Work with <a href='https://scholarworks.bwise.kr/hanyang/researcher-profile?ep=1216'>Dr. Boram Lim</a> (formerly University of Kansas) on an agent-based simulation framework in which GPT-powered agents make restaurant-choice decisions, enabling controlled experiments on consumer behavior at a scale that is infeasible with human subjects. The study uses a factorial design over review-presentation algorithms (highest-rated vs. most-recent) and restaurant positioning (high-end vs. casual) to isolate their effects on choice, with bias-detection, dynamic review supplementation, and structured behavioral logging of decision traces.

**Keywords:** Large Language Models, Agent-Based Simulation, Consumer Behavior, Experimental Design, Decision Making

---

### [2] Smart Shelf Advertising using Real-Time Product Segmentation and Interaction on Low-Cost Edge Devices
**U. Abid et al.** &middot; Preprint, 2025

A real-time retail system that detects product pick-up events and triggers contextual video advertisements, running end to end on low-cost edge hardware. A custom YOLOv8 segmentation model trained on a self-collected dataset of 3,500+ images reached 97.4% mAP@0.5 with real-time inference on constrained devices, and AprilTag-based tracking plus Arduino-controlled lighting were integrated into a single pipeline validated under varied shelf and lighting conditions.

[Preprint PDF](https://www.researchgate.net/publication/394095306_Smart_Shelf_Advertising_using_Real-Time_Product_Segmentation_and_Interaction_on_Low-Cost_Edge_Devices)

**Keywords:** Computer Vision, Edge Computing, Retail Technology, Object Segmentation, YOLOv8

---

## Research Experience

A fuller account of each project, including my specific contributions, is on the [Experiences]({{ '/experiences/' | relative_url }}) page.

- **LLM Agents for Consumer Behavior Research** &mdash; Co-Author, with Dr. Boram Lim (formerly University of Kansas). *Ongoing, remote.*
- **Smart Shelf Advertising on Low-Cost Edge Devices** &mdash; Co-Author. *2024 &ndash; 2025, Karachi, Pakistan.*
- **Simulation Study on Edge-Cloud Traffic** &mdash; Research Assistant to Engr. Muhammad Rehan Rasheed, Sir Syed University. Built a Java-based discrete simulation of edge-cloud environments to analyze traffic-management strategies and their effect on latency and throughput. *2023.*

---

## Research Interests

- **Natural Language Processing** &mdash; large language models, text understanding, conversational systems
- **Large Language Models and Agentic AI** &mdash; multi-agent systems, tool use, autonomous workflows
- **LLM-based simulation of human behavior** &mdash; using agents as instruments for studying decision-making
- **Computer Vision for edge deployment** &mdash; detection and segmentation under tight compute budgets
- **Efficient training and inference** &mdash; PEFT (LoRA/QLoRA), 4/8-bit quantization, optimized serving
- **Evaluation and reliability of LLM systems** &mdash; evaluation harnesses, LLM-as-judge, bias detection, grounding

I am interested in building intelligent systems that understand language, learn from data, and act reliably in real-world settings. My goal for graduate study is to move from applied engineering toward rigorous research on how large language models can be evaluated, grounded, and used as instruments for studying human decision-making.

---

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography %}

</div>