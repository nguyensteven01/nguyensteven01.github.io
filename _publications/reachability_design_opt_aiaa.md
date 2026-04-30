---
title: "Reachability-Based Design Optimization for Aircraft Maneuverability (Submitted)"
collection: publications
published: false
category: manuscripts
permalink: /publications/reachabilitiy_design_opt_aiaa
excerpt: 'This paper is about our application of reachability-based design optimization to a blended-wing-body aircraft. We submitted this to AIAA Journal in April 2026.'
date: 2026-04-30
venue: 'AIAA Journal'
paperurl: 'https://arxiv.org/abs/2604.26134'
bibtexurl: 'http://nguyensteven01.github.io/files/AIAA_reachability/reachability_des_opt_aiaa.bib'
citation: 'S. Nguyen, N. Orndorff, J. Cortés, B. Kramer, "Reachability-Based Design Optimization for Aircraft Maneuverability," 2022 IEEE International Conference on Vehicular Electronics and Safety (ICVES), Bogota, Colombia, 2022, pp. 1-6, doi: 10.1109/ICVES56941.2022.9987182'
---

This paper presents a method for incorporating control analysis into design optimization for highly-maneuverable aircraft. By studying reachable sets for aircraft dynamics, we ensure that the optimizer will take the aircraft's controlled capabilities into account. We compute reachable sets of linear dynamics for computational efficiency, and account for aircraft trim points to factor in asymmetric magnitude bounds on the input signals. We demonstrate the proposed method in design optimization of a blended-wing-body aircraft. Considering its wing half-span and center half-span as design variables, we optimize the aircraft based on its longitudinal dynamics' reachable sets to yield improvements in its controlled performance. When designing a reference tracking controller, we find up to 30\% less tracking error for angle of attack of the optimized model's nonlinear dynamics.

![BWB Design Optimization geometry](/files/AIAA_reachability/volmax_geometry.png)
*This is the result of one of our optimizations where we maximized the volume of the reachable set for the BWB at an airspeed of 200 m/s in level flight.*

![Nonlinear reference tracking simulation](/files/AIAA_reachability/volmax_nonlinear_track.png)
*Nonlinear simulation of reference tracking using integral LQR. Despite using metrics based on reachable sets for linearized dynamics, the nonlinear controlled performance improves after optimization.*