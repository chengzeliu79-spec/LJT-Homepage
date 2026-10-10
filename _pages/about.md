---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to the personal website of **Junteng Liu**. I am a first-year PhD candidate at the [HKUST NLP Group](https://hku-tml.github.io/), Hong Kong University of Science and Technology, where I am advised by Professor [Junxian He](https://junxianhe.github.io/). I graduated from Shanghai Jiao Tong University (SJTU) in June 2024 with a B.Eng. degree.

My research focuses on natural language processing and machine learning, with current interests in **LLM Reasoning and Reinforcement Learning**, **Hallucination in Vision-Language Models (VLM)**, and **LLM truthfulness and Interpretability**.

I am currently a Research Intern at **MINIMAX** (February 2025 - Present). Previously, I was a Research Intern at **Tencent WXG** (June 2024 - September 2024, advised by Zifei Shan) and **Shanghai AI Lab** (June 2023 - December 2023, advised by Prof. Yu Cheng).

Contact
======
- **Email:** jliugi@connect.ust.hk
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)

Selected Publications
======
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2>
        <hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
