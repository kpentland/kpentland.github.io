---
title: "FreeGSNKE Pulse Design Tool: in silico scenario design and control validation for tokamak plasmas"
type: "Poster Presentation"
event: "European Physical Society Plasma Physics Conference 2026"
location: "Edinburgh, Scotland"
date: 2026-07-02
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
description: >-
  FreeGSNKE is a Python-based, open-source suite for solving a range of static and dynamic Grad–Shafranov equilibrium problems in tokamak fusion plasmas. It employs finite-difference discretisation with a Newton–Krylov nonlinear solver and is designed to integrate with modern machine learning and artificial intelligence libraries. FreeGSNKE supports static forward and inverse equilibrium calculations, as well as time-evolving simulations through a coupling between plasma equilibria and currents in poloidal field coils and passive conducting structures. The framework enables virtual circuit construction for plasma shape control and estimation of vertical growth rates for vertical displacement event modelling. The codebase is tokamak-agnostic, well documented, and includes worked examples. The solvers have been validated against MAST-U equilibria, with ongoing development including a JAX-based implementation of the core solvers and a coupling with the current diffusion equation.

  Recent work has focused on coupling FreeGSNKE's evolutive solver with a newly developed modular and customisable virtual Plasma Control System (PCS). Using user-defined waveforms and control parameters, the PCS employs feedback and feedforward techniques to regulate plasma current, position, and shape throughout a simulation, while enforcing machine safety limits on coil currents and voltages. This combined framework, termed the FreeGSNKE Pulse Design Tool (FPDT), enables predictive modelling and virtual testing of advanced plasma configurations, new control schemes, and the impact of diagnostic uncertainties on plasma evolution and performance. This significantly reduces reliance on costly and iterative physical experiments. Although inspired by the MAST-U PCS architecture, the virtual PCS is inherently machine-independent, supporting the implementation of diverse control algorithms tailored to specific tokamaks. The FPDT has been validated by re-simulating previously executed MAST-U discharges and comparing nonlinear and piecewise-linear simulation modes. Under modest uncertainties in the initial equilibrium, current density profiles, and plasma resistivity, the FPDT achieves strong quantitative agreement with target control waveforms and real-time MAST-U measurements. With this extension to the FreeGSNKE open-source suite, we aim to foster greater reproducibility and collaboration in plasma modelling and control research.
# links:
#   Slides: "/assets/slides/icml2025.pdf"
#   Video: "https://youtube.com/..."
---
