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
  Research focus: AI-enabled materials design for electrochemical energy storage, with a current emphasis on lithium–sulfur battery catalysts

* **B.Eng. in Materials Science and Engineering**, Hebei University of Technology, Tianjin, China  
  Sep 2020 – Jun 2024

Research Interests
======

AI-enabled materials design for electrochemical energy storage, including literature-data engineering, machine learning for battery materials, large language models for scientific screening, coordination-environment descriptor development, and DFT-based hypothesis verification.


Selected Research Capabilities
======

* **Literature-data engineering for battery materials:** Developed literature-data collection software and processing workflows for heterogeneous battery-material datasets. In the hard-carbon project, I organized precursor, synthesis, structural, and electrochemical variables; performed data cleaning and missing-data imputation; and used machine-learning models and SHAP analysis to examine relationships with initial Coulombic efficiency and capacity-related properties.

* **Machine learning for lithium–sulfur catalyst design:** Process and transform electrochemical cycling data into material-level modelling targets, construct descriptors for metal identity and local coordination environments, evaluate the effects of experimental conditions and repeated structures, and rank candidate catalysts for subsequent computational verification.

* **Automated LLM-assisted catalyst screening:** Developed a fully automated literature-to-screening workflow for lithium–sulfur battery catalysts. The workflow integrates paper-aware information extraction, domain-specific dataset construction, two-stage language-model fine-tuning, multidimensional catalyst evaluation, external consistency assessment, and mechanistic validation.

* **DFT-supported hypothesis evaluation:** Use VASP-based calculations, including structural relaxation, adsorption-energy analysis, density-of-states analysis, and catalyst–polysulfide interaction evaluation, to test the physical plausibility of relationships identified through data-driven analysis.

* **Research leadership and coordination:** Served as a student project lead under faculty supervision. Responsibilities included defining research questions and technical roadmaps, coordinating data, modelling, literature-processing and computational tasks, reviewing intermediate results, maintaining methodological consistency, mentoring junior researchers, and leading manuscript planning and revision.

Ongoing Research
======

<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'ongoing_research' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

Manuscripts Under Revision
======

<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'manuscripts_under_revision' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

Journal Articles
======

<ul>
{% for post in site.publications reversed %}
  {% if post.category == 'journal_articles' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

Talks
======

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>