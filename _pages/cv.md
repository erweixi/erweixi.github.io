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

My research focuses on converting heterogeneous literature, electrochemical cycling data, and atomistic information into testable materials-design hypotheses. Lithium–sulfur catalysts are my primary research system, where I work on catalyst-specific target construction, coordination-environment descriptors, automated literature screening, and DFT-based verification. My previous work on hard-carbon anodes extends this data-engineering approach to sodium-ion batteries.

Selected Methodological Contributions
======

* **Hard-carbon literature-data pipeline:** Developed the literature-data collection software and processing workflow used in a study of hard-carbon anodes for sodium-ion batteries. I standardized precursor, synthesis, structural, and electrochemical variables reported across published studies, addressed incomplete and inconsistent reporting, and applied machine-learning and SHAP analyses to examine relationships among processing conditions, d002, La, Lc, ID/IG, pore characteristics, initial Coulombic efficiency, and capacity-related properties.

* **Target construction and validation for Li–S catalyst modelling:** I transform cycle-level electrochemical records into material-level prediction targets and examine whether the resulting labels genuinely reflect catalyst behaviour. My current workflow evaluates catalyst descriptors together with sulfur loading, electrolyte-to-sulfur ratio, current density, cycling protocol, publication source, and repeated coordination structures, and uses grouped validation and comparative model settings to reduce information leakage and separate catalyst-related signals from testing-condition effects.

* **Coordination-environment descriptor development:** I develop representations that distinguish metal identity, in-plane N/O/S/P coordination, heteroatom substitution, coordination order, axial ligation, and axial–planar electronic imbalance in single-atom catalysts. The objective is to distinguish local structures that conventional composition-based features may treat as equivalent and to evaluate whether the resulting descriptors improve model robustness, candidate ranking, and DFT-based verification.

* **Automated literature-to-catalyst screening:** Developed a fully automated workflow that converts lithium–sulfur battery publications into structured catalyst evaluations. The system combines non-Li–S document gating, paper-aware information extraction, domain corpus and question–answer construction, two-stage LoRA fine-tuning, lightweight-model comparison, four-dimensional catalyst scoring, external consistency assessment, and mechanistic validation.

* **Model-to-mechanism verification:** I treat machine-learning and LLM-derived relationships as hypotheses rather than direct mechanistic evidence. Selected catalyst candidates are evaluated through adsorption configurations and energies, density-of-states analysis, and catalyst–polysulfide interactions to determine whether the predicted ranking is physically plausible.

* **Research leadership and coordination:** Initiated and led the lithium–sulfur catalyst machine-learning project as a student project lead under faculty supervision and coordinated major parts of the LLM-assisted screening project. I defined research questions and technical roadmaps, divided work across data curation, modelling, literature processing, candidate screening, computational verification, and manuscript preparation, reviewed intermediate results and data quality, coordinated junior researchers, and led manuscript planning and revision.

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