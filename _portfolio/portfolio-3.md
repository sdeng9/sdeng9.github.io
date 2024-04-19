---
title: "Research Thrust Three: Design Optimization"
excerpt: "**Topology Optimization** (TO) aims to maximize structural performance by optimizing material layouts. However, one of the critical challenges that hinders TO from evolving into widespread industrial applications is the high cost of large-scale models and the complexity of multiple conflicting constraints. We addressed this challenge in a two-step manner. Firstly, we answered the question ‘_Given an existing design, is it really worth a computationally intensive TO for a new design?_’ by predicting the benefits of potential TO. Then, we developed a topological level-set method that, for the very first time, systematically combined topological sensitivity, level-set, augmented Lagrangian, and HPC. It guarantees unambiguous manufacturing-ready design and dramatically shortens computational time (hours to minutes reduction) for **3D large-scale designs with millions of degrees of freedom**. It was further extended to multi-physics designs where TO adjoints of various thermal quantities of interest were derived to improve optimization efficiency.


**Data-Driven Metamaterial Design**: Metamaterials have garnered substantial attention because they offer a new paradigm in achieving structure-property relationships over a large spectrum of applications (e.g., optical, thermal, and mechanical properties). However, most metamaterial investigations have been restricted to periodic architectures with perfect symmetry which are highly sensitive to inevitable manufacturing defects. In this line of research, we developed a data-driven multiscale design approach that integrated neural networks-based TO with data-driven surrogates to design **aperiodic bio-inspired spinodal metamaterials** with tunable anisotropy for energy absorption applications, e.g., impact-resistant armors.

<br/><img src='/images/research_9.jpg'>
"
collection: portfolio
---
<!-- <br/><img src='/images/research_4.jpg' align='middle'
style='width:800px;height:450px;margin-top:15px;margin-left:60px;margin-right:30px;'> -->


<!-- Topology optimization (TO) optimizes structural performance by designing material layouts. TO usually involves few design responses but a very large number of design variables characterizing material topology.
Multiphysics TO requires solving coupled multiphysics governing equations with various field variables in optimization loops where the calculation of design sensitivities is considerably expensive. We develop an efficient discrete adjoint sensitivity approach that reduces the dimension of design space and dispenses with matrix inversion.
TO faces theoretical challenges when solving design problems subject to multiple, various, and conflicting constraints. In this line of research, we combine the topological level-set method (i.e., treating topological sensitivity as a level-set) with the augmented Lagrangian method (i.e., quantifying active and inactive constraints via Lagrangian multipliers) to cast classic gradient-based continuous optimization as a discrete TO with clear 0-1 topological definition.
Our method helps to gain deep insights into high dimensional design space and to discover high-value, non-intuitive and manufacturing-feasible designs that would be otherwise difficult, if possible, to obtain through traditional methods. -->


Related Papers
------
* **Shiguang Deng** and Krishnan Suresh. "Stress constrained thermo-elastic topology optimization with varying temperature fields via augmented topological sensitivity-based level-set." _Structural and Multidisciplinary Optimization_ 56 (2017): 1413-1427.
* **Shiguang Deng** and Krishnan Suresh. "Topology optimization under thermo-elastic buckling." _Structural and Multidisciplinary Optimization_ 55 (2017): 1759-1772.
* **Shiguang Deng** and Krishnan Suresh. "Multi-constrained 3D topology optimization via augmented topological level-set." _Computers & Structures_ 170 (2016): 1-12.
* **Shiguang Deng** and Krishnan Suresh. "Multi-constrained topology optimization via the topological sensitivity." _Structural and Multidisciplinary Optimization_ 51 (2015): 987-1001.
* **Shiguang Deng**, and Krishnan Suresh. "Predicting the Benefits of Topology Optimization." International Design Engineering Technical Conferences and Computers and Information in Engineering Conference. Vol. 2. American Society of Mechanical Engineers Digital Collection, 2015.
