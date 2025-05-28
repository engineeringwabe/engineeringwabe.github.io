---
layout: post
title: "Manufacturing Fiber-Reinforced Ceramic Rocket Nozzles at Varying Hoop Angles"
description: "This study presents the ongoing development and planned hot-fire validation of composite and ceramic rocket nozzles manufactured using two distinct methods: additive manufacturing and powder-based sintering. The designs utilize fiber-reinforced materials to endure extreme thermal and mechanical loads. Structural integrity and thermal resistance have been assessed through finite element (FEM) and computational fluid dynamics (CFD) simulations, while internal nozzle flow was analytically modeled using MATLAB and ANSYS."
skills:
  - MATLAB
  - Aerodynamic Design
  - FEM
  - CFD
  - Thermal Simulations
  - Additive Manufacturing
  - Documentation
main-image: /useco.png
---


## Goal
This study aims to evaluate the manufacturability, performance, and failure response of each fabrication approach under realistic propulsion conditions, contributing to the advancement of reusable, high-performance ceramic and composite nozzles. Additional physical testing and simulations are still required. 

---
## Process
Firstly, compressible flow analysis was conducted to determine the optimal nozzle geometry. This involved using the area–Mach number relation, which provides insight into how flow properties vary along the nozzle contour and helps estimate the necessary exit area to meet desired flow conditions. Following this, MATLAB was used to calculate the thrust and axial distribution within the nozzle. By combining these methods, we generated a nozzle shape using MATLAB plots, which were refined to produce the final design shown in the image below.

{% include image-gallery.html images="uFirst.png" height="400" %} 

Once the desired nozzle contour was established, we proceeded to determine the optimal fiber orientation and wall thickness to ensure structural integrity under thermal and mechanical loading. This was achieved by plotting the relationship between fiber orientation angle and wall thickness, taking into account in-plane stress distributions resulting from internal pressure and thermal gradients. These results were then compared to a plot of wall thickness versus safety factor, calculated using maximum stress and Tsai-Wu failure criteria for composite laminates. Material properties were based on Alumina 4N, and assumptions included quasi-isotropic. Once an appropriate wall thickness and orientation were identified to meet a safety factor ≥ 2.0, the final geometry was modeled using Fusion 360 and SolidWorks for visualization and future finite element analysis (FEA).

{% include image-gallery.html images="usec.png" height="400" %} 
{% include image-gallery.html images="useco.png" height="400" %} 


Finally, the 3D CAD models were used for simulation-based performance evaluations. These simulations included Finite Element Method (FEM) structural analysis, Computational Fluid Dynamics (CFD), and thermal analysis. Thermal and CFD simulations were conducted in ANSYS Fluent and ANSYS Mechanical, allowing us to analyze internal flow characteristics, pressure distributions, heat flux, and temperature gradients within the nozzle during steady-state operation. For structural analysis, we utilized Altair HyperWorks to perform FEM simulations, evaluating deformation, stress concentrations, and failure modes under combined thermal and mechanical loading. The results from these simulations were used to validate the design and ensure that material limits were not exceeded under expected launch conditions.

{% include image-gallery.html images="uth.png" height="400" %} 
{% include image-gallery.html images="uthir.png" height="400" %} 
{% include image-gallery.html images="uthird.png" height="400" %} 


---
## Future Plans 
We received sponsorship to cover the cost of materials, including the use of alumina for 3D printing. This project is still ongoing, and our next step is to conduct physical testing of the nozzle to evaluate its real-world performance.
