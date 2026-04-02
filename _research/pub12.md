---
title:          "The FreeGSNKE Pulse Design Tool (FPDT): a computational framework for evolutive plasma scenario and control design"
selected:       true
pub:            "arXiv"
date:           2026-03-31 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  We present the FreeGSNKE Pulse Design Tool (FPDT), an open-source, Python-based computational framework that enables in silico testing and predictive design of tokamak plasma scenarios and control strategies. The FPDT couples the FreeGSNKE evolutive equilibrium solver with a virtual Plasma Control System (PCS) containing modular and customisable controllers. Given a set of user-defined waveforms and control parameters, the virtual PCS uses feedback and feedforward control to modulate plasma current, position, and shape, while adhering to machine safety limits on poloidal field coil currents and voltages. The resulting framework allows simulation of the controlled dynamic evolution of plasma equilibria, along with the currents in both active poloidal field coils and passive conducting structures, under the assumption of axisymmetry. The FPDT can be used to develop plasma scenarios, test control schemes, calibrate control parameters, and perform uncertainty quantification studies, thereby reducing iterative and expensive experimental testing on a physical tokamak. The FPDT is machine-agnostic and can be customised to implement different control algorithms tailored to the specific tokamak of interest. Here, we outline the overall framework and validate its performance on plasma discharges on the MAST Upgrade tokamak in the `flat-top' phase. We demonstrate excellent quantitative agreement between the FPDT simulations, the desired control waveforms, and the experimental shot data. With this extension to the FreeGSNKE open-source suite of codes we aim to encourage more reproducible and collaborative research in plasma modelling and control.

pub_last:       <span class="badge badge-info">Pulse design tool</span> <span class="badge badge-info">Plasma control system</span> <span class="badge badge-info">Grad-Shafranov</span> <span class="badge badge-info">MHD equilibria</span> <span class="badge badge-info">FreeGSNKE</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/FPDT.png

authors:
  - K. Pentland
  - N. C. Amorisco
  - A. Ross
  - P. Cavestany
  - T. Nunn
  - A. Agnello
  - G. K. Holt
  - G. McArdle
  - C. Vincent
  - J. Buchanan
  - S. J. P. Pamela

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2603.28513
  Code: https://github.com/FusionComputingLab/freegsnke
  Poster: /assets/docs/FPDT_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf



---