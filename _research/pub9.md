---
title:          "Multiple solutions to the static forward free-boundary Grad-Shafranov problem on MAST-U"
selected:       true
pub:            "arXiv"
date:           2025-03-10 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  The Grad-Shafranov (GS) equation is a nonlinear elliptic partial differential equation that governs the ideal magnetohydrodynamic equilibrium of a tokamak plasma. Previous studies have demonstrated the existence of multiple solutions to the GS equation when solved in idealistic geometries with simplified plasma current density profiles and boundary conditions. Until now, the question of whether multiple equilibria might exist in real-world tokamak geometries with more complex current density profiles and integral free-boundary conditions (commonly used in production-level equilibrium codes) has remained unanswered. In this work, we discover multiple solutions to the static forward free-boundary GS problem in the MAST-U tokamak geometry using the validated evolutive equilibrium solver FreeGSNKE and the deflated continuation algorithm. By varying the plasma current, current density profile coefficients, or coil currents in the GS equation, we identify and characterise distinct equilibrium solutions, including both deeply and more shallowly confined plasma states. We suggest that the existence of even more equilibria is likely prohibited by the restrictive nature of the integral free-boundary condition, which globally couples poloidal fluxes on the computational boundary with those on the interior. We conclude by discussing the implications of these findings for wider equilibrium modelling and emphasise the need to explore whether multiple solutions are present in other equilibrium codes and tokamaks, as well as their potential impact on downstream simulations that rely on GS equilibria.

pub_last:       <span class="badge badge-info">Multiple solutions</span> <span class="badge badge-info">Grad-Shafranov</span> <span class="badge badge-info">MHD equilibria</span> <span class="badge badge-info">FreeGSNKE</span> <span class="badge badge-info">Deflated continuation</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/multiple_solutions.png

authors:
  - K. Pentland
  - N. C. Amorisco
  - P. E. Farrell
  - C. J. Ham

links:
  # Publication: https://iopscience.iop.org/article/10.1088/1402-4896/ada192
  arXiv: https://arxiv.org/abs/2503.05674
  # Code: https://github.com/luost26/academic-homepage
  # Poster: /assets/docs/freegsnke_validation_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf



---