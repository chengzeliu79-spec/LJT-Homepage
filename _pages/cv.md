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
* Ph.D. in Computer Science (2024–Present), Hong Kong University of Science and Technology, HKUST NLP Group (supervised by Prof. Junxian He)
* B.Eng. (2020–2024), Shanghai Jiao Tong University (graduated June 2024)

Work experience
======
* Research Intern, MINIMAX (February 2025 – Present)
* Research Intern, Tencent WXG (June 2024 – September 2024)
  * Supervisor: Zifei Shan
* Research Intern, Shanghai AI Lab (June 2023 – December 2023)
  * Supervisor: Prof. Yu Cheng

Skills
======
* Natural language processing and machine learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models (VLMs)
* LLM truthfulness and interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
