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
  
Skills
======
* Interdisciplinary Research (AI + Materials): I specialize in bridging the gap between advanced AI techniques and energy material challenges. I have successfully applied Machine Learning to solve critical issues in battery catalyst development, focusing on data imputation for incomplete experimental results and using interpretability techniques to uncover underlying physical mechanisms.
* LLM for Scientific Discovery: Proficient in leveraging Large Language Models to accelerate research. My expertise includes fine-tuning models for domain-specific tasks and developing automated pipelines for scientific data extraction and cleaning from massive literature repositories.
* Leadership: Have extensive experience in leading research teams. I often served as the project leader, responsible for coordinating the work among different personnel and steering the overall progress of the project.

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
  