---
title: "Research Thrust One: Design Representation"
excerpt: "**Microstructure Reconstruction**: _As process-induced material defects are stochastic and inevitable, how can we efficiently represent them in microstructures?_ To answer this, we applied microstructure reconstruction to characterize tomography-infused material features and build massive datasets of **statistically equivalent feature representations** of the inherent stochasticity. Classic reconstruction approaches often rely on image pixel-based correlation functions which are typically slow and memory intensive. we developed innovative geometric descriptor and spectral density function methods to statistically represent random material features (e.g., morphology, geometry, and composition) with significant dimension reduction, such that the computational time of reconstruction is **reduced from hours to seconds**. Such methods are promising for many applications, e.g., manufacturing defect inspection, material repository development, and experimental data augmentation.


**Reduced Order Model**: To correlate microstructures with their mechanics performance, we need to numerically assess the effective property of each sample in the material dataset. However, classic direct numerical simulations, e.g., finite element analysis (FEA), are often challenged by numerical issues such as high costs, mesh dependency, and slow convergence for modeling high nonlinearity and path-dependent material behaviors. To address such issues, we developed novel mechanistic reduced-order models (ROMs) that ensembles several contributions to simulate the behavior of spatially varying microstructures under irreversible deformations, including: (𝑖) **Data compression** that reduces unknown variables by decomposing computational domain into a small number of material clusters, (𝑖𝑖) **Deflation algorithm** that projects high-dimensional variables into lower dimensional spaces, and (𝑖𝑖𝑖) **Explicit-implicit constitutive integration** that guarantees positive-definiteness of stiffness matrices with adjustable temporal-spatial discretization for elastoplastic and damage simulations. Such ROMs provide dramatic acceleration for many outer-loop applications, e.g., design optimization, fast dataset generation, uncertainty quantification, and digital twins.

<br/><img src='/images/research_5.jpg'>
"
collection: portfolio
---
<!-- <img src='/images/500x300.png' style='width:300px;height:300px;margin-right:15px;float:left'> -->
<!-- <br/><img src='/images/research_2.jpg' align='middle'
style='width:800px;height:450px;margin-top:15px;margin-left:60px;margin-right:30px;'> -->
<!-- Design Sensitivity for CAD Defeaturing Estimation -->

<!-- Significant advancements have been achieved in microstructural modeling to account for manufacturing-induced material local defects. However, the practical application of these microscale simulations in real-world design has been limited due to their high computational costs and prohibitive memory footprints.
To overcome this challenge, we develop reduced-order models (ROMs) that approximate computationally intensive simulations with far fewer resources by projecting solution variables into a lower dimension space with spatiotemporal reductions. By integrating ROMs into a concurrent multiscale modeling framework, our reduced-order system efficiently quantifies the impacts of spatially varying heterogeneous microstructures on complex component behaviors, e.g., elasto-plasticity and fracture, which enables low-cost design applications. -->


Related Papers
------
* **Shiguang Deng**, Diran Apelian, and Ramin Bostanabad. "Adaptive spatiotemporal dimension reduction in concurrent multiscale damage analysis." _Computational Mechanics_ 72 (2023): 3-35.
* **Shiguang Deng**, Carl Soderhjelm, Diran Apelian, and Ramin Bostanabad. "Reduced-order multiscale modeling of plastic deformations in 3D alloys with spatially varying porosity by deflated clustering analysis." _Computational Mechanics_ 70 (2022): 517-548.
* **Shiguang Deng**, Carl Soderhjelm, Diran Apelian, and Krishnan Suresh. "Second-order defeaturing estimator of manufacturing-induced porosity on structural elasticity." _International Journal of Numerical Methods in Engineering_ 123.19 (2022): 4483-4517.
* **Shiguang Deng**, Carl Soderhjelm, Diran Apelian, and Krishnan Suresh. "Estimation of elastic behaviors of metal components containing process induced porosity." _Computers & Structures_ 254 (2021): 106558.
