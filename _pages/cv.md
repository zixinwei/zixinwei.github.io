---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- B.S. in China, The Chinese University of Hong Kong, Shenzhen, 2026 (expected)
- Exchange in the U.S., University of North Carolina at Chapel Hill, 2025

# Research experience

- Jan. 2024 - Now: Undergraduate Research Assistant

  - The Chinese University of Hong Kong, Shenzhen
  - Topics includes: Dataset Discovery, Retrieval-augmented Generation
  - Supervisor: [Chenhao Ma](https://chenhao-ma.github.io/)

# Skills

- Languages: Chinese (Native), English (TOEFL 106)
- Programming Languages:
  - Python, Java, C/C++, Erlang, Elixir, Go, SQL
  - HTML, Javascript, Typescript
- Frameworks: PyTorch, FastAPI, Angular, SQLAlchemy
- Tools: Git, GitHub, Docker

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
