---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- Ph.D. in Computer Science (2024–Present), Hong Kong University of Science and Technology
- B.Eng., Shanghai Jiao Tong University (2020–2024)

## Work Experience

- Research Intern at MINIMAX (February 2025–Present)
- Research Intern at Tencent WXG (June 2024–September 2024)
- Research Intern at Shanghai AI Lab (June 2023–December 2023)

## Skills

- Natural Language Processing and Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models
- LLM Truthfulness and Interpretability

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
