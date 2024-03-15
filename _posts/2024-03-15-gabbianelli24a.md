---
title: Importance-Weighted Offline Learning Done Right
abstract: We study the problem of offline policy optimization in stochastic contextual
  bandit problems, where the goal is to learn a near-optimal policy based on a dataset
  of decision data collected by a suboptimal behavior policy. Rather than making any
  structural assumptions on the reward function, we assume access to a given policy
  class and aim to compete with the best comparator policy within this class. In this
  setting, a standard approach is to compute importance-weighted estimators of the
  value of each policy, and select a policy that minimizes the estimated value up
  to a “pessimistic” adjustment subtracted from the estimates to reduce their random
  fluctuations. In this paper, we show that a simple alternative approach based on
  the “implicit exploration” estimator of \citet{Neu2015} yields performance guarantees
  that are superior in nearly all possible terms to all previous results. Most notably,
  we remove an extremely restrictive “uniform coverage” assumption made in all previous
  works. These improvements are made possible by the observation that the upper and
  lower tails importance-weighted estimators behave very differently from each other,
  and their careful control can massively improve on previous results that were all
  based on symmetric two-sided concentration inequalities. We also extend our results
  to infinite policy classes in a PAC-Bayesian fashion, and showcase the robustness
  of our algorithm to the choice of hyper-parameters by means of numerical simulations.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gabbianelli24a
month: 0
tex_title: Importance-Weighted Offline Learning Done Right
firstpage: 614
lastpage: 634
page: 614-634
order: 614
cycles: false
bibtex_author: Gabbianelli, Germano and Neu, Gergely and Papini, Matteo
author:
- given: Germano
  family: Gabbianelli
- given: Gergely
  family: Neu
- given: Matteo
  family: Papini
date: 2024-03-15
address:
container-title: Proceedings of The 35th International Conference on Algorithmic Learning
  Theory
volume: '237'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 3
  - 15
pdf: https://proceedings.mlr.press/v237/gabbianelli24a/gabbianelli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
