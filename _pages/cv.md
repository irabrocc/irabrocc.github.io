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
* B.S. in Mathematics With Computer Science, Guangdong Technion Israel Institute of Technology, 2027(Expected)

Work experience
======
* Winter 2025: Undergraduate Teaching Assistant
  * Guangdong Technion Israel Institute of Technology
  * Duties included: Assist With Teaching Undergraduates
  
Skills
======
* Machine Learning
  * Pytorch
* Programming
* Latex Typesetting

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
