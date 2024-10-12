---
title:          "GParareal: a time-parallel ODE solver using Gaussian process emulation"
selected:       true
pub:            "Statistics and Computing"
date:           2023-01-02 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  In this project, we introduced GParareal, a time-parallel algorithm for solving initial value problems (IVPs) by employing a Gaussian process emulator to model the correction term between coarse and fine solutions. 
  Our results demonstrate that GParareal converges in fewer iterations than the traditional parareal method, improving computational speed and enabling the use of legacy solution archives to further enhance convergence. 
  This approach addresses limitations in existing time-parallel methods and offers a significant advancement in solving IVPs with high numerical accuracy.

pub_last:       <span class="badge badge-info">Parallel-in-time</span> <span class="badge badge-info">Parareal</span> <span class="badge badge-info">Gaussian processes</span>

cover: /assets/images/FHN5.png

authors:
  - K. Pentland
  - M. Tamborrino
  - T. J. Sullivan
  - J. Buchanan
  - L. C. Appel

links:
  Publication: https://link.springer.com/article/10.1007/s11222-022-10195-y
  arXiv: https://arxiv.org/abs/2201.13418
  Code: https://github.com/kpentland/GParareal
  Poster: /assets/docs/gparareal_poster.pdf
  Talk: /assets/docs/gparareal_talk.pdf
---


