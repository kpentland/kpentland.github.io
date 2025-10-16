---
title:          "Real-time applicability of emulated virtual circuits for tokamak plasma shape control"
selected:       true
pub:            "2025 IEEE Conference on Control Technology and Applications"
date:           2025-05-15 00:01:00 +0800  # so the site can order them correctly

abstract: >-
  Machine learning has recently been adopted to emulate sensitivity matrices for real-time magnetic control of tokamak plasmas. However, these approaches would benefit from a quantification of possible inaccuracies. We report on two aspects of real-time applicability of emulators. First, we quantify the agreement of target displacement from VCs computed via Jacobians of the shape emulators with those from finite differences Jacobians on exact Grad-Shafranov solutions. Good agreement (≈5-10%) can be achieved on a selection of geometric targets using combinations of neural network emulators with ≈1e5 parameters. A sample of ≈1e5−1e6 synthetic equilibria is essential to train emulators that are not over-regularised or overfitting. Smaller models trained on the shape targets may be further fine-tuned to better fit the Jacobians. Second, we address the effect of vessel currents that are not directly measured in real-time and are typically subsumed into effective "shaping currents" when designing virtual circuits. We demonstrate that shaping currents can be inferred via simple linear regression on a trailing window of active coil current measurements with residuals of only a few Ampères, enabling a choice for the most appropriate shaping currents at any point in a shot. While these results are based on historic shot data and simulations tailored to MAST-U, they indicate that emulators with few-millisecond latency can be developed for robust real-time plasma shape control in existing and upcoming tokamaks.

pub_last:       <span class="badge badge-info">Plasma shape control</span> <span class="badge badge-info">Virtual circuits</span> <span class="badge badge-info">Neural network emulation</span> <span class="badge badge-info">MHD equilibria</span> <span class="badge badge-info">MAST-U</span>

cover: /assets/images/emulated_VCs.png

authors:
  - P. Cavestany
  - A. Ross
  - A. Agnello
  - A. Garrod
  - N. Amorisco
  - G. K. Holt
  - K. Pentland
  - J. Buchanan

links:
  Publication: https://ieeexplore.ieee.org/document/11151371
  arXiv: https://arxiv.org/abs/2509.01789
  # Code: https://github.com/luost26/academic-homepage
  # Poster: /assets/docs/freegsnke_validation_poster.pdf
  # Talk: /assets/docs/freegsnke_validation.pdf



---