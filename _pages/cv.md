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
* **M.S. in Computer Science**, UMass Lowell, Boston, MA — *Expected 2027*
  <!-- TODO: Update with your actual degree, department, and graduation year -->
* **B.S. in Computer Science**, *Your Undergraduate University* — *Year*
  <!-- TODO: Update with your actual undergraduate degree info -->

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
