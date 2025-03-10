---
title: 'Not so different after all: a comparison of methods for detecting amino acid
  sites under selection'
description:
url: ''
date: '2005-05-01'
publishDate: '2025-03-07T18:12:21.499972Z'
authors:
- Sergei L Kosakovsky Pond
- Simon D W Frost
publication_types:
- '2'
abstract: 'We consider three approaches for estimating the rates of nonsynonymous
  and synonymous changes at each site in a sequence alignment in order to identify
  sites under positive or negative selection: (1) a suite of fast likelihood-based
  \"counting methods\" that employ either a single most likely ancestral reconstruction,
  weighting across all possible ancestral reconstructions, or sampling from ancestral
  reconstructions; (2) a random effects likelihood (REL) approach, which models variation
  in nonsynonymous and synonymous rates across sites according to a predefined distribution,
  with the selection pressure at an individual site inferred using an empirical Bayes
  approach; and (3) a fixed effects likelihood (FEL) method that directly estimates
  nonsynonymous and synonymous substitution rates at each site. All three methods
  incorporate flexible models of nucleotide substitution bias and variation in both
  nonsynonymous and synonymous substitution rates across sites, facilitating the comparison
  between the methods. We demonstrate that the results obtained using these approaches
  show broad agreement in levels of Type I and Type II error and in estimates of substitution
  rates. Counting methods are well suited for large alignments, for which there is
  high power to detect positive and negative selection, but appear to underestimate
  the substitution rate. A REL approach, which is more computationally intensive than
  counting methods, has higher power than counting methods to detect selection in
  data sets of intermediate size but may suffer from higher rates of false positives
  for small data sets. A FEL approach appears to capture the pattern of rate variation
  better than counting methods or random effects models, does not suffer from as many
  false positives as random effects models for data sets comprising few sequences,
  and can be efficiently parallelized. Our results suggest that previously reported
  differences between results obtained by counting methods and random effects models
  arise due to a combination of the conservative nature of counting-based methods,
  the failure of current random effects models to allow for variation in synonymous
  substitution rates, and the naive application of random effects models to extremely
  sparse data sets. We demonstrate our methods on sequence data from the human immunodeficiency
  virus type 1 env and pol genes and simulated alignments.'
featured: false
publication: '*Mol Biol Evol*'
doi: 10.1093/molbev/msi105
---

Page content here