---
title:          "Real-time virtual circuits for plasma shape control via neural network emulators: integration and testing in the MAST-U PCS"
selected:       false
pub:            "arXiv"
date:           2026-08-28 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  The deployment of advanced, AI-enabled control algorithms in tokamak experiments requires robust integration with existing plasma control system (PCS) architectures and extensive pre-experimental validation. In this contribution, we describe the integration and testing of neural-network-emulated virtual circuits for plasma shape control within the MAST Upgrade (MAST-U) PCS environment. The neural network models predict the plasma shape using the plasma current, poloidal field coil currents, and plasma profile parameters. In this paper, we explain how they are deployed via a real-time C++ inference server that interfaces with the PCS, returning the shape prediction and its Jacobian, and how, from the latter, virtual circuit matrices and updated coil current requests are computed for real-time actuation. Emphasis is placed on the validation workflow and best practices adopted to ensure confidence in the proposed control framework prior to experimental deployment. This work demonstrates practical AI-based shape control components for fusion control systems, with direct relevance for upcoming MAST-U experiments and future devices.

pub_last:       <span class="badge badge-info">Real-time control</span> <span class="badge badge-info">Shape control</span> <span class="badge badge-info">MAST-U</span> <span class="badge badge-info">Neural network emulators</span> <span class="badge badge-info">Real-time inference</span>

cover: /assets/images/RTVC_process.png

authors:
  - M. J. Marshall
  - E. Jones
  - G. McArdle
  - A. Ross
  - K. Pentland
  - N. C. Amorisco
  - C. Vincent
  - M. Kochan
  - C. Hogben
  - G. Jones
  - A. Stephen
  - G. K. Holt
  - A. Agnello

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2608.26216
  # Code: https://github.com/FusionComputingLab/freegsnke
  # Poster: /assets/docs/FPDT_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf

---