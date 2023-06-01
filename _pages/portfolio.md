---
layout: archive
title: "Research Summary"
permalink: /portfolio/
author_profile: true
---
The mission of my research is to design next-generation multiscale and multifunctional material-structure systems by elucidating processing-structure-performance (PSP) links.
Based on the PSP links, my interdisciplinary work interfaces multiple domains across design optimization, computational mechanics, advanced manufacturing, machine learning and material science, such as **topology optimization**, **reduced-order model**, **microstructure reconstruction**, **inverse design**, **data assimilation**, and **physics-constrained deep learning**.


Some of fundamental research questions that my research focuses on are:
(_i_) As process-induced defects are inevitable during manufacturing, how do different types of defects affect material mechanics?
(_ii_) Considering microscale defects are spatially varying on components, how to statistically represent the random defects by microstructures?
(_iii_) What are the computational bottlenecks of multiscale analysis, and how to efficiently compute the deformation mechanisms for microstructures of complex morphology?
(_ⅳ_) How can we address data-centric challenges for designing metamaterials-based microstructures, such as lack of data, data reliance and data assimilation?
(_ⅴ_) How to incorporate different types of performance and processing constraints in topology optimization for advanced manufacturing?
<br/><img src='/images/research_1.jpg'>

<!-- <br/><img src='/images/research_1.jpg' align='middle'
style='width:800px;height:450px;margin-top:15px;margin-left:60px;margin-right:30px;'> -->




{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
