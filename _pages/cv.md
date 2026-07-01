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
* Ph.D. in Electrical Engineering, University of California, Berkeley, 2021–Present
* B.Sc., University of Dhaka, 2016–2021

Research Experience
======
* **Research Intern** — Meta AI Audio (June 2025 – Present)
* **Research Intern** — Amazon Alexa (May 2024 – August 2024)

Research Interests
======
* Low-Resource Speech Recognition
* Neural Speech Synthesis
* Self-Supervised Audio Representation Learning

Awards
======
* Prime Minister Gold Medal Scholarship — University of Dhaka

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
