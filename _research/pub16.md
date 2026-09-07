---
title:          "Real-time virtual circuits for plasma shape control via neural network emulators: experimental demonstration on MAST Upgrade"
selected:       true
pub:            "arXiv"
date:           2026-08-31 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  Conventional plasma shape control in tokamaks relies on virtual circuits (VCs) that are computed offline from linearisations around a small, tailored number of reference equilibria, and deployed as expertly prepared schedules during the discharge. Here, we report on the first experimental deployment of real-time VCs. We replace pre-set look up tables with VCs updated in real time using surrogates of the plasma response. Both the existing control architecture and the interpretability of VC-based control are retained. Previous work showed that neural network emulators can produce accurate VCs, and validated their performance in closed-loop shape control simulations. Here, we report their first experimental validation on MAST Upgrade (MAST-U). Dedicated experiments spanning different scenarios, including prescribed shape perturbations, feedback-driven divertor-leg motion, and strongly evolving plasma configurations, show that real-time VCs can realise plasma shape control tasks within the MAST-U plasma control system. These results establish the experimental feasibility of real-time linearisations as a practical extension of conventional plasma shape control in tokamaks. The present implementation demonstrates a central step towards a simpler control workflow, in which manually constructed, phased VC schedules are replaced by VCs generated automatically online from a trained surrogate model, without scenario-specific retraining.

pub_last:       <span class="badge badge-info">Virtual circuits</span> <span class="badge badge-info">Real-time control</span> <span class="badge badge-info">Neural-network emulators</span> <span class="badge badge-info">Plasma control systems</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/RTVC_diagram.png

authors:
  - N. C. Amorisco
  - K. Pentland
  - A. Agnello
  - G. K. Holt
  - A. Ross
  - M. J. Marshall
  - E. Jones
  - G. McArdle
  - C. Vincent
  - T. Nunn
  - M. Kochan
  - P. Cavestany
  - A. Garrod
  - S. J. P. Pamela
  - J. Buchanan
  - The MAST Upgrade Team

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2608.28468
  # Code: https://github.com/FusionComputingLab/freegsnke
  # Poster: /assets/docs/FPDT_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf
---