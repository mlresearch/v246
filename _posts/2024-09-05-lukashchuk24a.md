---
title: Q-conjugate Message Passing for Efficient Bayesian Inference
abstract: Bayesian inference in nonconjugate models such as Bayesian Poisson regression
  often relies on computationally expensive Monte Carlo methods. This paper introduces
  {Q}-conjugacy, a generalization of classical conjugacy that enables efficient closed-form
  variational inference in certain nonconjugate models. {Q}-conjugacy is a condition
  in which a closed-form update scheme expresses the solution minimizing the Kullback-Leibler
  divergence between a variational distribution and the product of two potentially
  unnormalized distributions. Leveraging {Q}-conjugacy within a local message passing
  framework allows deriving analytic inference update equations for nonconjugate models.
  The effectiveness of this approach is demonstrated on Bayesian Poisson regression
  and a model involving a hidden gamma-distributed latent variable with Gaussian-corrupted
  logarithmic observations. Results show that {Q}-conjugate triplets, such as (Gamma,
  LogNormal, Gamma), provide better speed-accuracy trade-offs than Markov Chain Monte
  Carlo.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lukashchuk24a
month: 0
tex_title: "{Q}-conjugate Message Passing for Efficient Bayesian Inference"
firstpage: 295
lastpage: 311
page: 295-311
order: 295
cycles: false
bibtex_author: Lukashchuk, Mykola and {\c{S}en\"{o}z}, {\.{I}}smail and {de Vries},
  Bert
author:
- given: Mykola
  family: Lukashchuk
- given: İsmail
  family: Şenöz
- given: Bert
  family: de Vries
date: 2024-09-05
address:
container-title: Proceedings of The 12th International Conference on Probabilistic
  Graphical Models
volume: '246'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 9
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v246/main/assets/lukashchuk24a/lukashchuk24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
