---
title: "Real Time Virtual Circuits for plasma shape control via NN surrogates"
type: "Poster Presentation"
event: "European Physical Society Plasma Physics Conference 2026"
location: "Edinburgh, Scotland"
date: 2026-07-02
authors:
  - M. Marshall
  - E. Jones
  - G. McArdle
  - A. Ross
  - N. C. Amorisco
  - C. Vincent
  - C. Hogben
  - G. Jones
  - A. Stephen
  - K. Pentland
  - G. K. Holt
  - A. Agnello
  
abstract: >-
  The deployment of advanced, AI-enabled control algorithms in tokamak experiments requires robust integration with existing plasma control system (PCS) architectures and extensive pre-experimental validation. In this contribution, we describe the implementation of neural-network-emulated virtual circuits for plasma shape control within the MAST Upgrade (MAST-U) PCS environment.

  The neural network models are transformed into a real-time-suitable data structure and deployed via a C++ inference server that interfaces with the General Atomics Plasma Control System (GAPCS), a real-time control framework. An integration layer transfers real-time GAPCS signals into the neural network input space, executes inference within real-time constraints, and returns the resulting Jacobian coefficients to the control system. These coefficients are then used to assemble and invert the virtual circuit matrices and compute updated coil current requests for real-time actuation.

  We discuss the overall software architecture and data pathways underpinning this integration, the timing and latency constraints encountered, and the challenges of interfacing modern AI components with real-time control infrastructure. Emphasis is placed on the validation workflow and best practices adopted to ensure confidence in the solution prior to experimental deployment. This work demonstrates a practical pathway for introducing AI-based control components into operational fusion control systems, with direct relevance for upcoming MAST-U experiments and future devices.

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  # arXiv: https://arxiv.org/abs/2509.01789
  # Code: https://github.com/luost26/academic-homepage
  # Poster: /assets/docs/freegsnke_validation_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf
---