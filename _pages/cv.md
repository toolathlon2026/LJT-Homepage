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
* **Ph.D. in Computer Science** (2024–Present)  
  Hong Kong University of Science and Technology (HKUST)  
  Advisor: Prof. Junxian He

* **B.Eng.** (2020–2024)  
  Shanghai Jiao Tong University (SJTU)

Work Experience
======
* **Research Intern** (February 2025 – Present)  
  MINIMAX  
  * Focus on large language models and reasoning

* **Research Intern** (June 2024 – September 2024)  
  Tencent WXG  
  * Advised by Zifei Shan  
  * Worked on vision‑language models and chart understanding

* **Research Intern** (June 2023 – December 2023)  
  Shanghai AI Lab  
  * Advised by Prof. Yu Cheng  
  * Research on truthfulness and interpretability of LLMs

Skills
======
* **Research Areas:** Natural Language Processing, Machine Learning, LLM Reasoning, Reinforcement Learning, Vision‑Language Models, Interpretability
* **Programming Languages:** Python, C++, JavaScript
* **Frameworks & Tools:** PyTorch, TensorFlow, Hugging Face, Git, LaTeX
* **Languages:** Chinese (Native), English (Fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and Leadership
======
* **Reviewer** for conferences: EMNLP, NeurIPS, ICML
* **Mentor** for undergraduate research projects at HKUST