---
title:          "Real-time virtual circuits for plasma shape control via neural network emulators"
selected:       false
pub:            "arXiv"
date:           2026-05-15 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  Reliable position and shape control in tokamak plasmas requires accurate real-time regulation of several strongly coupled shape parameters. The control vectors that disentangle these couplings, referred to as virtual circuits (VCs), enable independent shape parameter control for a specific Grad--Shafranov (GS) equilibrium. Numerical calculation of VCs is not currently feasible in real time, therefore VCs are usually computed prior to each experiment,  using a small number of reference GS equilibria sampled along the desired scenario trajectory, with each VC used to control the plasma within a preset time interval. While effective near the reference equilibrium, this approach can lead to degraded performance as the plasma departs from the reference equilibrium and/or from the desired trajectory, and it complicates the design of robust control strategies for rapidly evolving plasma configurations. In this paper, we construct neural-network-based emulators of plasma shape parameters from which VCs can be derived, to provide the MAST Upgrade (MAST-U) plasma control system with state-aware VCs in real-time. To do this, we develop an extensive library of over a million simulated GS equilibria, covering a substantial portion of the MAST-U operational space. These emulators provide differentiable functions whose gradients can be rapidly computed, enabling the derivation of accurate VCs for real-time shape control. We perform extensive verification of the emulated VCs by testing whether they disentangle the control problem. The neural-network-based approach delivers high accuracy and orthogonality across a diverse range of equilibria. This work establishes the physical validity of emulated VCs as a scalable and general alternative to schedules of precomputed VCs. 

pub_last:       <span class="badge badge-info">Plasma control</span> <span class="badge badge-info">Virtual circuits</span> <span class="badge badge-info">Neural network emulators</span> <span class="badge badge-info">Grad-Shafranov</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/static_validation_VCs.png

authors:
  - A. Ross
  - G. K. Holt
  - K. Pentland
  - A. Agnello
  - N. C. Amorisco
  - P. Cavestany
  - A. Garrod
  - T. Nunn
  - C. Vincent
  - G. McArdle

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2605.14939
  # Code: https://github.com/FusionComputingLab/freegsnke
  # Poster: /assets/docs/FPDT_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf

---