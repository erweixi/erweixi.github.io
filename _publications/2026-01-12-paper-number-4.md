---
title: "A Robust ML Framework for Single-Atom Catalyst Discovery: From Noisy Experimental Data to Material Design Rules"
collection: publications
category: Current Research
permalink: /publication/sac-ml-robust-framework
excerpt: >
  This work establishes a systematic ML pipeline to extract reliable material design rules from noisy, high-dimensional experimental datasets. 
  By distilling 376,000+ dynamic cycling records into robust performance metrics and implementing symmetry-aware "Rotation Augmentation," the framework overcomes the limitations of small-sample laboratory data. 
  The project bridges the gap between raw electrochemical curves and actionable catalyst screening. 
  Crucially, this data-driven strategy is highly transferable and can be readily applied to any conversion-type battery systems (e.g., Li-S, Li-Se, and Na-S) to accelerate the discovery of high-retention catalysts.
date: 2026-01-12
venue: 'Research Project'
---

## Research Overview

This project provides a robust solution for handling the "noisy and small-sample" nature of experimental material data in battery research.

### Core Methodology
1.  **Dynamic Data Distillation**: 
    Automated extraction of key performance indicators (Peak Capacity, Retention@100, and Maintenance Duration) from hundreds of thousands of raw cycling records, ensuring data consistency despite variations in testing conditions.
2.  **Symmetry-Aware ML Modeling**: 
    Implementation of **Rotation Augmentation** to handle the symmetry of coordination environments in Single-Atom Catalysts (SACs), coupled with forward feature selection to identify the most impactful chemical descriptors.
3.  **Explainable AI (XAI) for Design**: 
    Utilizing SHAP analysis to decode the complex relationships between catalyst structure and electrochemical stability, enabling both the screening of existing materials and the generation of new candidates.



### Universal Strategy for Conversion-Type Batteries
While this framework is demonstrated using **Lithium-Sulfur (Li-S)** battery catalysts, its underlying methodology—focusing on robust feature engineering and physics-informed data augmentation—is **domain-agnostic**. The entire pipeline, from curve distillation to SHAP-based rule extraction, serves as a universal template for accelerating catalyst discovery in any **conversion-type battery system**, where handling dynamic degradation and complex coordination chemistry is essential.