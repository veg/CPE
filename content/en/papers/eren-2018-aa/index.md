---
title: 'Full-Length Envelope Analyzer (FLEA): A tool for longitudinal analysis of
  viral amplicons'
description:
url: ''
date: '2018-12-01'
publishDate: '2025-03-07T18:12:09.924388Z'
authors:
- Kemal Eren
- Steven Weaver
- Robert Ketteringham
- Morné Valentyn
- Melissa Laird Smith
- Venkatesh Kumar
- Sanjay Mohan
- Sergei L Kosakovsky Pond
- Ben Murrell
publication_types:
- '2'
abstract: Next generation sequencing of viral populations has advanced our understanding
  of viral population dynamics, the development of drug resistance, and escape from
  host immune responses. Many applications require complete gene sequences, which
  can be impossible to reconstruct from short reads. HIV env, the protein of interest
  for HIV vaccine studies, is exceptionally challenging for long-read sequencing and
  analysis due to its length, high substitution rate, and extensive indel variation.
  While long-read sequencing is attractive in this setting, the analysis of such data
  is not well handled by existing methods. To address this, we introduce FLEA (Full-Length
  Envelope Analyzer), which performs end-to-end analysis and visualization of long-read
  sequencing data. FLEA consists of both a pipeline (optionally run on a high-performance
  cluster), and a client-side web application that provides interactive results. The
  pipeline transforms FASTQ reads into high-quality consensus sequences (HQCSs) and
  uses them to build a codon-aware multiple sequence alignment. The resulting alignment
  is then used to infer phylogenies, selection pressure, and evolutionary dynamics.
  The web application provides publication-quality plots and interactive visualizations,
  including an annotated viral alignment browser, time series plots of evolutionary
  dynamics, visualizations of gene-wide selective pressures (such as dN/dS) across
  time and across protein structure, and a phylogenetic tree browser. We demonstrate
  how FLEA may be used to process Pacific Biosciences HIV env data and describe recent
  examples of its use. Simulations show how FLEA dramatically reduces the error rate
  of this sequencing platform, providing an accurate portrait of complex and variable
  HIV env populations. A public instance of FLEA is hosted at http://flea.datamonkey.org.
  The Python source code for the FLEA pipeline can be found at https://github.com/veg/flea-pipeline.
  The client-side application is available at https://github.com/veg/flea-web-app.
  A live demo of the P018 results can be found at http://flea.murrell.group/view/P018.
featured: false
publication: '*PLoS Comput Biol*'
doi: 10.1371/journal.pcbi.1006498
---

Page content here