---
title:          "Stochastic parareal: an application of probabilistic methods to time-parallelisation"
selected:       false
pub:            "SIAM Journal on Scientific Computing"
date:           2022-07-07 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  In this project, we introduced a stochastic variant of the parareal algorithm to speed up its convergence when solving time-dependent differential equations. 
  By sampling initial values from dynamically varying probability distributions and selecting the smoothest trajectories in time, the algorithm converges in fewer iterations compared to the traditional deterministic approach. 
  Our results show that stochastic parareal reduces iteration counts while maintaining accuracy, with potential to capture uncertainty in the solution.

# $\LaTeX$ is supported. $a=b+c$.

pub_last:       <span class="badge badge-info">Parallel-in-time</span> <span class="badge badge-info">Parareal</span> <span class="badge badge-info">Probabilistic numerics</span>

cover: /assets/images/sparareal.png

authors:
  - K. Pentland
  - M. Tamborrino
  - D. Samaddar
  - L. C. Appel

links:
  Publication: https://epubs.siam.org/doi/10.1137/21M1414231
  arXiv: https://arxiv.org/abs/2106.10139
  Code: https://github.com/kpentland/StochasticParareal
  Poster: /assets/docs/sparareal_poster.pdf
  Talk: /assets/docs/sparareal_talk.pdf
---


