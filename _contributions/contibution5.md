---
title: "FreeGSNKE: an open source pure-Python predictive evolutive equilibrium code
for control design and validation"
type: "Talk"
event: "9th Asia-Pacific Conference on Plasma Physics"
location: "Fukuoka, Japan"
date: 2025-09-21
authors:
  - N. C. Amorisco
  - K. Pentland
  - G. K. Holt
  - A. Agnello
  - A. Ross
  - P. Cavestany
  - G. McArdle
  - C. Vincent
  - G. Cunningham
  - U. Qadri
  - J. Buchanan
  - S. Pamela


abstract: >-
  FreeGSNKE is an open source, pure-Python, finite
  difference solver of the 2D dynamic plasma equilibrium
  problem. It couples the plasma equilibrium with the
  currents in the poloidal field (PF) coils and passive
  vessel. FreeGSNKE can run predictive simulations
  of the plasma response to the voltages applied to the PF
  coils by the power supplies, thereby supporting shape
  control and control design studies.
  One of FreeGSNKE’s aims is to lower the entry barrier
  to studies seeking to adopt ML approaches to plasma
  control. FreeGSNKE is fully open source and seamlessly
  integrates with Python ML libraries and algorithms,
  overcoming the need for cross-language binders or
  socket interfaces for multi-language interaction. A set of
  examples and dedicated documentation are provided to
  facilitate adoption by new users.
  FreeGSNKE builds on FreeGS, introducing i) a static
  Grad-Shafranov (GS) solver based on the Newton-
  Krylov (NK) method; ii) linear and non-linear solvers for
  the evolutive equilibrium problem, also based on the NK
  method. We validate FreeGSNKE’s static GS solver on a
  selection of MAST-Upgrade (MAST-U) discharges with
  EFIT++ reconstructed equilibria. To validate the
  evolutive solver we simulate the ‘flat-top phase’ of
  MAST-U shots, using the recorded voltages applied to
  the PF coils and an EFIT++ reconstructed equilibrium as
  initial conditions. Fig.1 illustrates one such FreeGSNKE
  simulation by displaying the evolution of a set of
  standard plasma shape targets. These are compared with
  the corresponding reconstructed quantities.
  Several concurrent development tracks are presently
  underway. I) A Pulse Design tool is being built to allow
  for in-silico development of new plasma shapes and
  controllers to support MAST-U operations. II) An auto-
  differentiable and GPU-compatible version of
  FreeGSNKE is being developed using the JAX library.
  III) We are integrating FreeGSNKE with a transport
  module, to enable integrated modelling with time
  evolving free boundary equilibria. Using the IMAS data
  formats, we are coupling FreeGSNKE with JETTO. The
  coupling with TORAX will leverage the JAX
  implementation. IV) FreeGSNKE is being used to
  support vertical stability studies of STEP plasmas.
  The evolutive capabilities will be used to support the
  estimation of EM loads during VDEs.

links:
  # Publication: https://ieeexplore.ieee.org/document/11151371
  # arXiv: https://arxiv.org/abs/2509.01789
  # Code: https://github.com/luost26/academic-homepage
  # Poster: /assets/docs/freegsnke_validation_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf
---