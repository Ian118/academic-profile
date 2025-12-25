---
title: "Robotic Space Simulator: Controls Implementation for Auxiliary Axes and Zero-G Dynamics"
collection: publications
category: conferences
permalink: /publication/2025-05-19-Robotic-Space-Simulator-Controls-Implementation-for-Auxiliary-Axes-and-Zero-G-Dynamics
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-05-19
venue: 'In the proceedings of 2025 IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: '/files/ICRA_2025___RSS_Dynamics_Control.pdf'
bibtexurl: '/files/ICRA_2025___RSS_Dynamics_Control.bib'
citation: ' Eddie Hilburn,  Adam Pettinger,  Emily Wilkinson,  <b>Ian Lansdowne</b>,  Robert Ambrose, &quot;Robotic Space Simulator: Controls Implementation for Auxiliary Axes and Zero-G Dynamics.&quot; In the proceedings of 2025 IEEE International Conference on Robotics and Automation (ICRA), 2025.'
---
[Access paper here](https://ieeexplore.ieee.org/document/11128455/){:target="_blank"}

Abstract: The Robotic Space Simulator was developed as a physical simulation for in-space manipulation tasks. It incorporates external inputs to its dynamics simulation via force/torque sensors mounted to the 2 6-DoF Stewart platforms which compose its primary structure. Each platform is augmented with an additional degree of freedom in the form of an auxiliary axis - one in translation and one in rotation. Previous work has not effectively included the additional workspace provided by these auxiliary axes. Additionally, it limited the use of external force/torque inputs to the case of platform translation only because the external forces/torques due to platform motion and gravitational force were not removed from the sensor inputs prior to inclusion in the dynamic simulation. In this work, we address each of these limitations. We develop and test two methods of auxiliary axis control: Cartesian Workspace and Joint Cost-Function, and find that both methods are an improvement over the existing system. Additionally we develop and test a method for calculating the mass properties of hardware mounted to the force/torque sensors and a dynamics compensation method for this hardware. Using this technique we are able to effectively compensate for gravitational force in different platform orientations, and achieve zero-g behavior of the system.
