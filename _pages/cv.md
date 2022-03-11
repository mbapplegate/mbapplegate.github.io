---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click [here](../files/LaTex_CV_10Mar2022.pdf) for a PDF version of my CV

Education
======
* B.S. in Electrical Engineering, Cornell University, 2009
* Ph.D in Biomedical Engineering, Tufts University 2016
  
Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Optical system design
* Alignment
* Microscopy
* AI-based Image Processing
* Machine Learning
* PCB design and assembly
* Programming
  * Matlab
  * Python
  * C++
  * VHDL
  * LaTeX
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

  

