---
title: "Research Thrust Two: Design Exploration"
excerpt: "**Data-Driven Surrogate**: While classic mechanistic models (e.g., homogenization-based multiscale FEA models) provide fundamental understanding of continuum mechanics and facilitate material innovation, they are generally too expensive for the design of multiscale material-structure systems (e.g., composites, alloys, hydrogels, or polymers) across spatial-temporal scales in high dimensional design spaces. In this research, by data mining the massive datasets of stochastic microstructures with their associated anisotropic properties, we developed a **physics-informed deep learning surrogate** to efficiently emulate the effective responses of heterogeneous microstructures under irreversible plastic deformation with hardening and softening behaviors. It demonstrated a significant accuracy improvement over pure data-driven ‘black-box’ models and a dramatic efficiency boost of about **four orders of magnitude of acceleration** than FEA.


**Material Data Assimilation**: In data-centric design, one important question is: _Given the limited amount of engineering data, how can we address the data reliance challenges, such as lack of data, low-quality data, and data interpretability?_ To answer this question, we developed a robust statistical learning model to assimilate data from multiple sources and constructed a **multi-fidelity scheme** to calibrate the parameters of low-fidelity models as a function of microstructural morphology and data fidelity. The data assimilation scheme not only reduces data reliance on expensive high-fidelity samples by systematically fusing cheap low-fidelity data, provides interpretable latent spaces and quantifies material informatics via statistical sensitivity analysis, but also shows promising potential to **augment numerical-experimental datasets** to build large material repositories for future material discovery.

<br/><img src='/images/research_6.jpg'>
"
collection: portfolio
---
<!-- <br/><img src='/images/research_3.jpg' align='middle'
style='width:800px;height:450px;margin-top:15px;margin-left:60px;margin-right:30px;'> -->

<!-- While physics-based simulations provide fundamental understanding of material mechanics and facilitate material innovation, they are generally too expensive for multiscale material systems (e.g., composites, alloys and crystals) involving high dimensional design space and complex deformation mechanisms. In this research theme, we develop a data-driven framework that integrates microstructure reconstruction, model reduction, statistical and machine learning models to statistically represent material heterogeneity, relieve data reliance and provide trustworthy prediction.
Our framework is successfully demonstrated in several studies including: (_i_) data assimilation that relies on Gaussian process to fuse and calibrate reduced-order solutions of different fidelities; (_ii_) physics-informed deep learning that incorporates thermodynamics into sequential learners to emulate multiscale path-dependent plasticity and fracture propagation; and (_iii_) metamaterials design that exploits image-based deep learning to accelerate material geometric optimization with spatially varying unit cells. -->


Related Papers
------
* **Shiguang Deng**, Carlos Mora, Diran Apelian and Ramin Bostanabad. "Data-driven calibration of multi-fidelity multiscale fracture models via latent map Gaussian process." _Journal of Mechanical Design_ 145.1 (2023): 011705.
* **Shiguang Deng**, Shirin Hosseinmardi, Diran Apelian and Ramin Bostanabad. "Data-Driven Physics-Constrained Recurrent Neural Networks for Multiscale Damage Modeling of Metallic Alloys with Process-Induced Porosity." _Computational Mechanics_ (2024), https://doi.org/10.1007/s00466-023-02429-1.
* **Shiguang Deng**, Liwei Wang, Stefan Knapik, Horacio Espinosa, Wei Chen. "Data-Driven Multiscale Design of Spinodal Materials with Nonlinear Responses.", in preparation, 2024.
