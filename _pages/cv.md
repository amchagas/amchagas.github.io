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
* B.Sc in Biology, University of Sao Paulo, 2008
* M.Sc in Cellular and Molecular Neurosciences, University of Tuebingen, 2010
* Ph.D in Neural and Behavioural Neurosciences, University of Tuebingen, 2020 (expected)

Work experience
======
* 2010-2015: Research Assistant
  * University of Tuebingen
  * Duties included: Experiments and data analysis
  * Supervisor: Professor Cornelius Schwarz

* 2016-2018: Research Assistant
  * University of Tuebingen
  * Duties included: Experiments, data analysis, hardware development
  * Supervisor: Professor [Thomas Euler](http://eulerlab.de/)

Skills
======
* Project Management
* Coding
  * Python
  * Matlab
  * OpenScad
  * Igor
* Version control
  * Git/Github/Gitlab
* Fast Prototyping
  * 3D printing (OpenScad, FreeCad)
  * Laser cutting
* Electronics
  * circuit design
  * PCB design (KiCad, Fritzing)
  * Microcontrollers (Arduino, ESP32)
* Operating systems  
  * Windows   
  * GNU/Linux

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
