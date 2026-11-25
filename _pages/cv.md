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
* Ph.D in Computer Science, Aalto University, 2026-
* M.S. in Computer Science, University of Copenhagen, 2020-2022
* B.S. in Computer Science and Technology, Shanghai Jiao Tong University, 2016-2020

Work experience
======
{% include experience-list.md %}

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
    
Skills
======
* Programming languages: Python, C#, Typescript, C++
* Technologies: React, Node.js, .Net, Azure, Elasticsearch, MySQL, KQL, Git, Linux