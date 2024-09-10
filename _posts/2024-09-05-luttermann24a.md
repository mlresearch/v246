---
title: Efficient Detection of Commutative Factors in Factor Graphs
abstract: Lifted probabilistic inference exploits symmetries in probabilistic graphical
  models to allow for tractable probabilistic inference with respect to domain sizes.
  To exploit symmetries in, e.g., factor graphs, it is crucial to identify commutative
  factors, i.e., factors having symmetries within themselves due to their arguments
  being exchangeable. The current state-of-the-art to check whether a factor is commutative
  with respect to a subset of its arguments iterates over all possible subsets of
  the factor’s arguments, i.e., O($2^n$) iterations for a factor with n arguments
  in the worst case. In this paper, we efficiently solve the problem of detecting
  commutative factors in a factor graph. In particular, we introduce the detection
  of commutative factors (DECOR) algorithm, which allows us to drastically reduce
  the computational effort for checking whether a factor is commutative in practice.
  We prove that DECOR efficiently identifies restrictions to drastically reduce the
  number of required iterations and validate the efficiency of DECOR in our empirical
  evaluation.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: luttermann24a
month: 0
tex_title: Efficient Detection of Commutative Factors in Factor Graphs
firstpage: 38
lastpage: 56
page: 38-56
order: 38
cycles: false
bibtex_author: Luttermann, Malte and Machemer, Johann and Gehrke, Marcel
author:
- given: Malte
  family: Luttermann
- given: Johann
  family: Machemer
- given: Marcel
  family: Gehrke
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
pdf: https://raw.githubusercontent.com/mlresearch/v246/main/assets/luttermann24a/luttermann24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
