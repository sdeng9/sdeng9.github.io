---
layout: archive
title: "Research Summary"
permalink: /portfolio/
author_profile: true
---
<!-- The mission of my research is to design the next-generation multiscale and multifunctional material-structure systems by elucidating processing-structure-performance links.
My interdisciplinary work interfaces multiple domains across topology optimization, reduced order model, microstructure reconstruction, inverse design, data assimilation, and physics-constrained machine learning. -->

The **design of advanced manufacturing-material-structure systems** requires intricate data-driven frameworks that go beyond streamlining high-performance computing and classic physics-based modeling, as there are pressing needs for developing advanced design methodologies that (𝑖) Embody the stochastic nature of synthetic materials, (𝑖𝑖) Acknowledge the high costs and numerical issues of inner-loop analysis models, (𝑖𝑖𝑖) Exploit massive material repositories to establish processing-structures-properties (PSP) links, and (𝑖𝑣) Sensibly explore high dimensional design spaces.

The **objective of my research** is to address such design needs by rethinking: _How to represent process-induced randomness in a design space, and explore the design space to optimize variability-embedded material systems?_ My research uses scientific machine learning to develop a comprehensive physics-informed data-driven design framework that enables to solve some of the most challenging design problems involving high dimensionality, path-dependent material behaviors, conflicting design constraints, inverse design, multiscale design, and design under uncertainty.

My data-driven design framework consists of three major components as depicted below: (𝑖) **Design acquisition** that generates design data of statistically equivalent stochastic microstructures in high-dimensional design spaces via reconstruction, and efficiently evaluate their properties via reduced-order models, (𝑖𝑖) **Design representation** that data mines massive PSP datasets to discover material informatics, construct interpretable low-dimensional design space, build hyper-efficient deep learning surrogates, and assimilate diverse multi-fidelity data, and (𝑖𝑖𝑖) **Design optimization** that optimizes multiscale multi-physics functional material-structure systems for fast prototyping and high-throughput manufacturing.
<br/><img src='/images/research_7_update.jpg'>

<!-- Some of fundamental research questions that my research focuses on are:
* As process-induced defects are inevitable during manufacturing, how do different types of defects affect material mechanics?
* Considering microscale defects are spatially varying on components, how to statistically represent the random defects by microstructures?
* What are the computational bottlenecks of multiscale analysis, and how to efficiently compute the deformation mechanisms for microstructures of complex morphology?
* How can we address data-centric challenges for designing metamaterials-based microstructures, such as lack of data, data reliance and data assimilation?
* How to incorporate different types of performance and processing constraints in topology optimization for advanced manufacturing? -->

<!-- <br/><img src='/images/research_1.jpg' align='middle'
style='width:800px;height:450px;margin-top:15px;margin-left:60px;margin-right:30px;'> -->

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
