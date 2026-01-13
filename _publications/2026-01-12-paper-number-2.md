---
title: "A Generalizable LLM-Driven Framework for High-Throughput Material Discovery: A Case Study in Li-S Battery Catalysts"
collection: publications
category: Current Research
permalink: /research/generalizable-llm-distillation-framework
excerpt: >
  We propose a universal, domain-agnostic workflow for accelerating scientific discovery using Large Language Models. 
  The framework employs a hierarchical knowledge distillation strategy: a fine-tuned 30B "Teacher" model captures deep domain insights, which are then distilled into a lightweight 4B "Student" model for efficient, multi-dimensional scoring. 
  While demonstrated on Lithium-Sulfur battery catalyst screening, this automated pipeline is designed for cross-domain transferability, enabling rapid material evaluation and screening across diverse scientific fields with high computational efficiency.
date: 2026-01-12
---

## Methodological Framework & Transferability

The core value of this research lies in its **methodological robustness** and **cross-domain adaptability**. Instead of a one-off screening tool, we have developed a reusable pipeline that can be redeployed to other material science or chemical engineering domains.

### 1. Hierarchical Knowledge Distillation
By distilling a heavy-weight model (30B) into a light-weight agent (4B), we solve the conflict between "deep reasoning" and "high-throughput speed." This strategy ensures that complex chemical intuition can be applied at scale.

### 2. Universal Applicability (Transferability)
* **Domain Agnostic:** The distillation and scoring logic can be migrated to hydrogen evolution catalysts, CO2 reduction, or drug discovery by simply swapping the fine-tuning dataset.
* **Multi-Dimensional Scoring:** The framework is not limited to a single metric; it can be configured to score any material property (stability, activity, cost) based on the "Teacher" model's instructions.

### 3. Efficiency & Scalability
The distilled 4B model allows for the screening of massive candidate spaces that are traditionally inaccessible via DFT or larger LLMs, providing a scalable solution for various R&D bottlenecks.