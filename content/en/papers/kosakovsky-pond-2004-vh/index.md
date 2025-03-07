---
title: 'Column sorting: rapid calculation of the phylogenetic likelihood function'
description:
url: ''
date: '2004-10-01'
publishDate: '2025-03-07T18:12:21.647973Z'
authors:
- Sergei L Kosakovsky Pond
- Spencer V Muse
publication_types:
- '2'
abstract: Likelihood applications have become a central approach for molecular evolutionary
  analyses since the first computationally tractable treatment two decades ago. Although
  Felsenstein's original pruning algorithm makes likelihood calculations feasible,
  it is usually possible to take advantage of repetitive structure present in the
  data to arrive at even greater computational reductions. In particular, alignment
  columns with certain similarities have components of the likelihood calculation
  that are identical and need not be recomputed if columns are evaluated in an optimal
  order. We develop an algorithm for exploiting this speed improvement via an application
  of graph theory. The reductions provided by the method depend on both the tree and
  the data, but typical savings range between 15%and 50%. Real-data examples with
  time reductions of 80%have been identified. The overhead costs associated with implementing
  the algorithm are minimal, and they are recovered in all but the smallest data sets.
  The modifications will provide faster likelihood algorithms, which will allow likelihood
  methods to be applied to larger sets of taxa and to include more thorough searches
  of the tree topology space.
featured: false
publication: '*Syst Biol*'
doi: 10.1080/10635150490522269
---

Page content here