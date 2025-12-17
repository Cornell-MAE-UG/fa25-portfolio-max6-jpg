---
layout: project
title: MAE 4272 Portfolio
description: Designing a Turbine
technologies: [Fusion 360, MATLAB]
image: /assets/images/spaceship-design.jpg
---


Project Overview
As part of MAE 4272 (Fluids & Heat Transfer Lab), our team designed, manufactured, and experimentally tested a small-scale horizontal-axis wind turbine blade optimized for low-speed wind conditions. The goal was to maximize power and torque output while meeting strict geometric, structural, and operational constraints, including a 6-inch blade length and a maximum operating speed of 2000 RPM. The project emphasized a full engineering workflow from analytical modeling and CAD development to wind tunnel validation.

Design Process
The design began with an iterative MATLAB-based performance model that evaluated blade torque, power output, and bending stress across a range of freestream velocities and rotational speeds. The blade was discretized into spanwise elements to compute local aerodynamic forces, structural loading, and steady-state rotation rates while enforcing a factor of safety of 2 against bending failure. Results from this model directly informed key geometric features of the blade, including the chord taper and spanwise twist distribution required to maintain near-optimal angle of attack. A three-bladed rotor using a NACA 4412 airfoil was selected, and the final geometry was implemented in Fusion 360 using multiple airfoil cross-sections and guide curves before being manufactured via SLA printing.

Testing and Results
The completed blades were tested in a wind tunnel across freestream velocities from approximately 2.75 to 7.40 m/s. Rotational speed was measured with an IR sensor, and a torque brake was used to vary loading and generate torque and power curves. Experimental data were post-processed to produce power vs. RPM and maximum power vs. wind speed plots. The turbine achieved a peak measured torque of approximately 1.92 oz-in at ~1970 RPM, satisfying all structural and operational constraints. While measured performance followed expected turbine trends, results indicated the blade was slightly overspecced for the tested RPM range, highlighting limitations in the initial modeling assumptions and identifying clear opportunities for refinement.

My Contribution
My primary contribution was developing the MATLAB modeling and optimization script used to define the blade’s key geometric parameters. I determined the spanwise blade angles (twist/pitch), chord distribution, and operating conditions that maximized predicted power while remaining within stress and RPM limits. I also supported CAD validation of the geometry and assisted in analysis comparing experimental power curves to model predictions to assess performance discrepancies.

