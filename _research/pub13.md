---
title:          "Real-time virtual circuits for plasma shape control via neural network surrogates: dynamic validation in closed-loop simulations"
selected:       true
pub:            "arXiv"
date:           2026-04-01 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  Reliable confinement and stable performance of tokamak fusion plasmas require accurate real-time magnetic shape control. A promising route to reduced latency and increased flexibility in plasma control systems (PCS) is to emulate physics-based controllers using neural networks. In prior work, we have demonstrated that virtual circuits (VCs), which define the poloidal field coil current vectors able to modify each plasma shape parameter independently, can be accurately emulated with neural network models trained on a large library of simulated Grad-Shafranov equilibria. This enables magnetic controllers to accurately adapt to evolving plasma equilibria, in contrast to pre-set VC schedules whose performance degrades upon departure from their reference equilibria. Here, we investigate the performance and robustness of these emulators in closed-loop simulations using the FreeGSNKE Pulse Design Tool (FPDT): a framework that couples the FreeGSNKE evolutive equilibrium solver with a virtual PCS. The FPDT models the coupling between controllers, plasma current and shape response, and actuator constraints. Using the emulated VCs within the FPDT, we demonstrate effective in-silico control of MAST Upgrade (MAST-U) plasma scenarios and show that the emulators are robust in the presence of input measurement uncertainty and under different update frequencies. These results establish the viability of neural network emulated VCs for closed-loop plasma shape control, representing a key step toward real-time deployment in the MAST-U PCS.

pub_last:       <span class="badge badge-info">Virtual circuits</span> <span class="badge badge-info">Neural network emulation</span> <span class="badge badge-info">Plasma control</span> <span class="badge badge-info">Pulse Design Tool</span> <span class="badge badge-info">FreeGSNKE</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/CDC_paper.png

authors:
  - K. Pentland
  - A. Ross
  - N. C. Amorisco
  - P. Cavestany
  - T. Nunn
  - A. Agnello
  - G. K. Holt
  - C. Vincent

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2604.00781
  # Code: https://github.com/FusionComputingLab/freegsnke
  # Poster: /assets/docs/FPDT_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf

---