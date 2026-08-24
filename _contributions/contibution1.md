---
title: "Real Time Virtual Circuits for plasma shape control via NN surrogates"
type: "Poster Presentation"
event: "European Physical Society Plasma Physics Conference 2026"
location: "Edinburgh, Scotland"
date: 2026-07-02
authors:
  - A. Ross
  - A. Agnello
  - A. Garrod
  - C. Vincent
  - G. K. Holt
  - G. McArdle
  - K. Pentland
  - N. C. Amorisco
  - P. Cavestany
  - T. Nunn
  
abstract: >-
  Reliable position and shape control in tokamak plasmas requires accurate real-time regulation of several strongly coupled shape parameters. The control vectors disentangling these couplings, hereafter referred to as Virtual Circuits (VCs), enable independent shape parameter control for a specific equilibrium. These VCs are conventionally computed in advance of an experiment using a small number of reference Grad–Shafranov equilibria and used to control the plasma across different pre-set time intervals. While effective near the reference equilibrium, this approach can lead to degraded performance when the plasma departs from the target trajectory and complicates the design of robust control strategies for rapidly evolving plasma configurations.
  This work presents the construction of emulators for VCs that satisfy the requirements for use in real-time control on MAST Upgrade (MAST-U). We develop an extensive library of several million simulated magnetic equilibria, covering a substantial portion of the MAST-U operational space, and use it to train neural network emulators to predict shape parameters given plant parameters. These are differentiable functions, whose Jacobians can be computed with millisecond latency, providing accurate VCs suited for real-time shape control.
  We perform extensive verification of the emulated VCs by applying small, independent shifts to a diverse set of several thousand equilibria and comparing the resulting target displacements with those obtained using finite-difference Jacobians of Grad-Shafranov solutions. The neural-network-based approach delivers high accuracy and orthogonality across the full equilibrium space. This work establishes the physical validity of emulated VCs as a scalable and general alternative to pre-set schedules of pre-computed VCs.

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  # arXiv: https://arxiv.org/abs/2509.01789
  # Code: https://github.com/luost26/academic-homepage
  # Poster: /assets/docs/freegsnke_validation_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf
---