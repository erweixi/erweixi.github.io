---
title: "Accelerating Catalyst Screening for Lithium-Sulfur Batteries via Knowledge Distillation of Large Language Models"
collection: publications
category: Current Research
permalink: /publication/2026-llm-catalyst-screening
excerpt: >
    To address the critical bottlenecks of inconsistent evaluation protocols and positive reporting bias in Lithium-Sulfur (Li-S) battery research, I developed a hierarchical, fully automated AI framework that democratizes high-throughput catalyst screening. I engineered an end-to-end pipeline that autonomously standardizes unstructured data from raw scientific PDFs to construct a bias-mitigated training corpus, bypassing the limitations of traditional structure-dependent machine learning. By employing a "Teacher-Student" knowledge distillation strategy, I compressed deep domain reasoning into a lightweight 8B parameter model, enabling a novel "Text-to-Score" paradigm where users can obtain multi-dimensional performance evaluations directly from chemical formulas. This approach not only reduces computational overhead to allow deployment on consumer-grade GPUs but also establishes a versatile, scalable methodology transferable to broader fields such as electrolyte screening, drug discovery and so on.
date: 2026-01-12
venue: 'Research Project'
---
## Project Overview: Automated & Hierarchical LLM Framework for Cost-Effective Catalyst Screening

This project bridges the gap between unstructured scientific literature and quantitative material discovery by engineering an end-to-end, fully automated AI pipeline.

### Core Workflow
1.  **Solving the "Data Standardization" Bottleneck**: 
    Addressed the challenge of inconsistent evaluation protocols in Li-S battery research by deploying DeepSeek as an automated information extractor. This module parses thousands of raw PDFs, structuring complex chemical data into a standardized, bias-mitigated dataset without human intervention.
2.  **Hierarchical "Teacher-Student" Distillation**: 
    Overcame the prohibitive inference costs of large models by implementing a **two-stage fine-tuning strategy**. A domain-expert **Qwen-30B (Teacher)** model, fine-tuned on the standardized corpus, distills its deep reasoning capabilities into a lightweight **8B (Student)** model. This architecture enables rapid, high-throughput screening on **consumer-grade GPUs**.
3.  **"Text-to-Score" Discovery Paradigm**: 
    Innovated a screening method that bypasses the limitations of traditional structure-dependent Machine Learning. The system accepts simple chemical formulas as input and outputs multi-dimensional performance scores, allowing for the instant identification of promising candidates from vast material spaces.


### Key Highlight: Domain Transferability
While currently applied to **Lithium-Sulfur (Li-S) battery catalysts**, the most significant advantage of this workflow is its **universality**. The pipeline's architecture—comprising literature extraction, model distillation, and physics-based validation—can be seamlessly migrated to other fields, such as hydrogen evolution catalysts, CO2 reduction materials, or drug discovery, by simply updating the initial literature dataset and the specific validation tool.