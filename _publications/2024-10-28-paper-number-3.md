---
title: "Advanced hard carbon materials for practical applications of sodium-ion batteries developed by combined experimental, computational, and data analysis approaches"
collection: publications
category: manuscripts
permalink: /publication/2024-10-28-advanced-hard-carbon-sib-data-ml
excerpt: 'This paper focuses on the hard carbon anode of sodium-ion batteries and emphasizes the "data statistics + machine learning" data-driven approach: by mining literature data to construct a database of "precursor - preparation parameters - microstructure - electrochemical performance", and using microstructure parameters (such as Vtotal, La, Lc, SSA, d002, ID/IG), preparation parameters (precursor type, carbonization temperature) and test conditions as input features, with ICE, reversible capacity and reversible platform capacity as prediction targets. This paper uses Mice Forest based on random forest to interpolate missing data to improve data integrity; for different targets, it trains random forest models and uses Bayesian optimization to tune parameters, and evaluates generalization ability with 5-fold cross-validation; then uses SHAP to explain model contributions, quantifying the influence of carbonization temperature and key microstructure parameters on ICE/ capacity/platform capacity, thereby converting "black box prediction" into interpretable rules that can be used for the controllable design and parameter selection of hard carbon microstructure.'
date: 2024-10-28
venue: "Progress in Materials Science"
slidesurl:
paperurl: "https://doi.org/10.1016/j.pmatsci.2024.101401"
bibtexurl:
citation: 'Sun, Z.; Liu, H.; Li, W.; Zhang, N.; Zhu, S.; Chen, B.; He, F.; Zhao, N.; He, C. (2025). "Advanced hard carbon materials for practical applications of sodium-ion batteries developed by combined experimental, computational, and data analysis approaches." <i>Progress in Materials Science</i>. 149, 101401.'
---

In this work, we propose a comprehensive framework that integrates experimental, computational, and data-driven approaches to address the structural complexity of hard carbon (HC) anodes for sodium-ion batteries.
Our study establishes a robust "Data Statistics + Machine Learning" pipeline. By mining extensive literature data, we constructed a multi-dimensional database and utilized Mice Forest to handle missing values, ensuring data integrity. We then trained Random Forest models—optimized via Bayesian search—to predict critical performance metrics like Initial Coulombic Efficiency (ICE) and reversible capacity based on microstructural features.
The true strength of this work lies in its guidance for material design. By implementing SHAP (SHapley Additive exPlanations), we successfully decoded the "black box" of machine learning, quantifying exactly how preparation parameters and microstructures dictate electrochemical performance. This transforms empirical "trial-and-error" into interpretable design rules, allowing for the precise tuning of precursors and carbonization temperatures to reach target properties.
Ultimately, this workflow is not limited to hard carbon; it represents a highly transferable paradigm for the accelerated development and controllable design of various advanced energy materials.