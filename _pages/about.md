---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a biomedical engineer specializing in opto-electric systems for medical applications. My experience spans hardware, software, firmware, system integration, data collection/analysis, and machine learning methods. 

I received my B.S. in Electrical engineering from Cornell University in 2009 where I focused on signal processing. I got my PhD in Biomedical Engineering with [Fiorenzo Omentto's lab](https://ase.tufts.edu/biomedical/unolab/home.html) at Tufts University in 2016. My thesis looked at different methods of photo-modification of biomaterials with a particular focus on silk. From 2016 to 2021 I worked with [Darren Roblyer](https://www.bu.edu/botlab/) at Boston University to develop and test novel diffuse optical imaging modalities. Currently, I'm working with [Jennifer Dy](https://coe.northeastern.edu/people/dy-jennifer/) and [Milind Rajadhyaksha](https://www.mskcc.org/research-areas/labs/milind-rajadhyaksha) to develop new machine learning algorithms for diagnosis and monitoring of skin cancer. 


Recent research
---
{% for post in site.research reversed %}
  {% if forloop.index < 3 %}
    {% include archive-double-research.html %}
  {% endif %}
{% endfor %}

For more check the [Research](/research/), [Publications](/publications/), or [CV](/cv/) pages
