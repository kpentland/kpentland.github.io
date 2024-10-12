---
title:          "A blending hybrid model for simulating reaction-diffusion equations"
selected:       false
pub:            "Undergraduate Summer Research Project"
date:           2017-09-01 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  The main focus of this project was to speed up the simulation time of reaction-diffusion systems.
  We did this by developing an algorithm that tracks the concentration of the quantity of interest using "compartments" in one region of the spatial domain, using individual "molecules" in another region, and then a "blend" of both in the overlapping region.
  This resulted in a hybrid "blending" method for simulating reaction-diffsuion systems. 
# $\LaTeX$ is supported. $a=b+c$.

pub_last:       <span class="badge badge-info">Reaction-Diffusion</span> <span class="badge badge-info">PDEs</span> <span class="badge badge-info">Gillespie algorithm</span> <span class="badge badge-info">Brownian motion</span> 

cover: /assets/images/blending.jpg

authors:
  - K. Pentland
  - C. A. Yates

links:
  Presentation: /assets/docs/blending_presentation.pdf
  # arXiv: https://arxiv.org/abs/2106.10139
  # Code: https://github.com/kpentland/StochasticParareal
---