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
* **B.S. in Computer Science**, University of Houston, Expected June 2026
  * Minor in Mathematics
  * Relevant Coursework: Software as a Service (COSC 4355), Data Structures, Algorithms

Work Experience
======
* **Student Developer**, University of Houston
  * Currently developing a professional portfolio website using Jekyll and GitHub Pages
  * Implementing Google Analytics 4 for real-time traffic monitoring
  * Maintaining version control and project documentation via GitHub

Skills
======
* **Programming Languages:** C++, JavaScript, HTML/CSS
* **Web Development:** Jekyll, GitHub Pages, SaaS architecture
* **Tools:** Git, Google Analytics 4, GitHub Actions
* **Hardware:** PC Building, System Optimization

Projects
======
* **Full-Stack Web Application:** Developed a web app integrated with a GitHub repository
* **Personal Portfolio:** Built a data-driven academic website for professional networking

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
  
Service and Leadership
======
* Member, University of Houston Computer Science Department