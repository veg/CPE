---
title: A simple hierarchical approach to modeling distributions of substitution rates
description:
url: ''
date: '2005-02-01'
publishDate: '2025-03-07T18:12:21.918674Z'
authors:
- Sergei L Kosakovsky Pond
- Simon D W Frost
publication_types:
- '2'
abstract: Genetic sequence data typically exhibit variability in substitution rates
  across sites. In practice, there is often too little variation to fit a different
  rate for each site in the alignment, but the distribution of rates across sites
  may not be well modeled using simple parametric families. Mixtures of different
  distributions can capture more complex patterns of rate variation, but are often
  parameter-rich and difficult to fit. We present a simple hierarchical model in which
  a baseline rate distribution, such as a gamma distribution, is discretized into
  several categories, the quantiles of which are estimated using a discretized beta
  distribution. Although this approach involves adding only two extra parameters to
  a standard distribution, a wide range of rate distributions can be captured. Using
  simulated data, we demonstrate that a \"beta-\" model can reproduce the moments
  of the rate distribution more accurately than the distribution used to simulate
  the data, even when the baseline rate distribution is misspecified. Using hepatitis
  C virus and mammalian mitochondrial sequences, we show that a beta- model can fit
  as well or better than a model with multiple discrete rate categories, and compares
  favorably with a model which fits a separate rate category to each site. We also
  demonstrate this discretization scheme in the context of codon models specifically
  aimed at identifying individual sites undergoing adaptive or purifying evolution.
featured: false
publication: '*Mol Biol Evol*'
doi: 10.1093/molbev/msi009
---

Page content here