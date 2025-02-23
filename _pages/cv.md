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
* Ph.D in Neural and Behavioural Neurosciences, University of Tuebingen, 2020
* M.Sc in Cellular and Molecular Neurosciences, University of Tuebingen, 2012
* B.Sc in Biology, University of Sao Paulo, 2008

Work experience
======
* September 2023 - present: Assistant Professor in Open Science
  * University of Sussex - Sussex Neuroscience
  * Duties include: Teaching, developing Open source Neuroscience tools and Equipment

* May 2019 - present: Scientific Officer in Bioengineering
  * University of Sussex - Sussex Neuroscience
  * Duties include: developing Open Source Neuroscience tools and Equipment, repair and customisation of tools

  
Skills
======
* Teaching
* Programming
  * Python
  * C++
* PCB design
* Design for 3D printing
* Article review
* Supervision of projects and students

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
  

