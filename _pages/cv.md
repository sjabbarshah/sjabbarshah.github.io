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
* **Ph.D.**, UMass Lowell
* **Master's Degree**, Hanyang University, South Korea
* **Bachelor's Degree**, UET Khuzdar

Skills
======
* **Programming Languages**: Python, Java, JavaScript, C/C++
  <!-- TODO: Update with your actual skills -->
* **Frameworks & Tools**: TensorFlow, PyTorch, Git, Docker
* **Web Technologies**: HTML, CSS, React, Node.js
* **Databases**: MySQL, PostgreSQL, MongoDB

<!-- TODO: Add your work experience, publications, projects, etc. as you build your portfolio -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
