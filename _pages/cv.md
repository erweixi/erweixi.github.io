---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* **M.Eng. in Energy and Power Engineering**, Tianjin University, Tianjin, China  
  Sep 2024 – Jun 2027 (expected)  
  Research focus: Machine-learning-assisted design of catalysts for lithium–sulfur batteries

* **B.Eng. in Materials Science and Engineering**, Hebei University of Technology, Tianjin, China  
  Sep 2020 – Jun 2024
  
Technical Skills
======
- **Machine learning for materials design:** Python, pandas, NumPy, scikit-learn, Random Forest, XGBoost, feature engineering, missing-data imputation, cross-validation, hyperparameter optimization, SHAP-based model interpretation, and candidate ranking. Applied these methods to lithium–sulfur battery catalysts and hard-carbon anodes for sodium-ion batteries.
- **Scientific data engineering:** Developed literature-data collection software and reproducible data-processing pipelines for heterogeneous materials datasets, including schema design, data cleaning, variable standardization, duplicate-condition handling, target construction, and data-quality control.
- **Large language models for scientific discovery:** PyTorch, Hugging Face Transformers, LoRA-based fine-tuning, domain-corpus construction, scientific-document processing, automated information extraction, model evaluation, and the development of fully automated, end-to-end literature-driven catalyst-screening workflows.
- **Computational materials science:** VASP-based density functional theory calculations, structural relaxation, adsorption-energy calculations, density-of-states analysis, and atomistic evaluation of catalyst–polysulfide interactions.
- **Research leadership and coordination:** Served as a student project lead under faculty supervision; defined research objectives and technical roadmaps, coordinated task allocation and progress review, maintained methodological and data-quality standards, mentored junior researchers, and led manuscript planning and revision.

Researching Projects
======
  <ul>{% for post in site.publications reversed %}
    {% if post.venue == 'Research Project' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.venue != 'Research Project' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
