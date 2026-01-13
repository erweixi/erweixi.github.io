---
title: "Accelerating Catalyst Screening for Lithium-Sulfur Batteries via Knowledge Distillation of Large Language Models"
collection: publications
category: Current Research
permalink: /publication/2026-llm-catalyst-screening
excerpt: >
  We developed a hierarchical LLM framework to accelerate the discovery of Lithium-Sulfur (Li-S) battery catalysts. 
  The pipeline begins by fine-tuning a 30B-parameter LLM on extensive scientific literature to internalize deep domain knowledge. 
  Through a knowledge distillation process, this 30B "teacher" model instructs a lightweight 4B "student" model to perform multi-dimensional scoring of catalyst candidates based on chemical activity and stability. 
  Finally, the distilled 4B model is deployed for high-throughput screening across vast material spaces, enabling rapid identification of promising catalysts with significantly reduced computational overhead.
date: 2026-01-12
venue: 'Research Project'
---
## Project Overview: The "LLM + DFT" Closed-Loop System

This project aims to bridge the gap between "unstructured literature knowledge" and "physics-based verification" by building an automated discovery pipeline.

### Core Workflow
1.  **Knowledge Extraction & Model Fine-tuning**: 
    Utilizing **DeepSeek** to extract structured evidence (performance metrics, structural components, experimental conditions) from thousands of papers. This data is used to fine-tune a **Qwen-30B** model, creating a specialist in electrochemical materials.
2.  **Hierarchical Scoring via Knowledge Distillation**: 
    The fine-tuned 30B model (Teacher) establishes a multi-dimensional ranking logic to evaluate materials. This reasoning capability is distilled into a **4B model** (Student), enabling rapid, large-scale screening of candidate materials with high efficiency.
3.  **DFT Validation & Feedback**: 
    Top-ranked candidates undergo **Density Functional Theory (DFT)** calculations to verify their catalytic activity and stability. The computational results are used to refine the LLM's screening strategy, ensuring a reliable and accurate pipeline.



### Key Highlight: Domain Transferability
While currently applied to **Lithium-Sulfur (Li-S) battery catalysts**, the most significant advantage of this workflow is its **universality**. The pipeline's architecture—comprising literature extraction, model distillation, and physics-based validation—can be seamlessly migrated to other fields, such as hydrogen evolution catalysts, CO2 reduction materials, or drug discovery, by simply updating the initial literature dataset and the specific validation tool.