---
title:          "Validation of the static forward Grad-Shafranov equilibrium solvers in FreeGSNKE and Fiesta using EFIT++ reconstructions from MAST-U"
selected:       true
pub:            "arXiv"
date:           2024-10-10 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  In this paper, we are interested in solving the static forward Grad-Shafranov (GS) problem for free-boundary MHD equilibria. 
  Our focus is on the validation of the static forward solver in the Python-based equilibrium code FreeGSNKE by solving equilibria from magnetics-only EFIT++ reconstructions of MAST-U shots. 
  In addition, we also validate FreeGSNKE against equilibria simulated using the well-established MATLAB-based equilibrium code Fiesta. 
  To do this, we develop a computational pipeline that allows one to load the same (a)symmetric MAST-U machine description into each solver, specify the required inputs (active/passive conductor currents, plasma profiles and coefficients, etc.) from EFIT++, and solve the GS equation for all available time slices across a shot. 
  For a number of different MAST-U shots, we demonstrate that both FreeGSNKE and Fiesta can successfully reproduce various poloidal flux quantities and shape targets (e.g. midplane radii, magnetic axes, separatrices, X-points, and strikepoints) in agreement with EFIT++ calculations to a very high degree of accuracy.

pub_last:       <span class="badge badge-info">MHD equilibria</span> <span class="badge badge-info">Grad-Shafranov</span> <span class="badge badge-info">FreeGSNKE</span> <span class="badge badge-info">Fiesta</span> <span class="badge badge-info">EFIT++</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/machine_description.png

authors:
  - K. Pentland
  - N. C. Amorisco
  - O. El-Zobaidi
  - S. Etches
  - A. Agnello
  - G. K. Holt
  - C. Vincent
  - J. Buchanan
  - S. J. P. Pamela
  - G. McArdle
  - L. Kogan
  - G. Cunningham

links:
  # Publication: https://link.springer.com/article/10.1007/s11222-022-10195-y
  arXiv: https://arxiv.org/abs/2407.12432
  # Code: https://github.com/luost26/academic-homepage
  Poster: /assets/docs/freegsnke_validation_poster.pdf
  Talk: /assets/docs/freegsnke_validation.pdf

---