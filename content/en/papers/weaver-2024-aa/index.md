---
title: 'AUTO-TUNE: selecting the distance threshold for inferring HIV transmission
  clusters'
description:
url: ''
date: '2024-01-01'
publishDate: '2025-03-07T18:12:04.214093Z'
authors:
- Steven Weaver
- Vanessa M Dávila Conn
- Daniel Ji
- Hannah Verdonk
- Santiago Ávila-Rı́os
- Andrew J Leigh Brown
- Joel O Wertheim
- Sergei L Kosakovsky Pond
publication_types:
- '2'
abstract: Molecular surveillance of viral pathogens and inference of transmission
  networks from genomic data play an increasingly important role in public health
  efforts, especially for HIV-1. For many methods, the genetic distance threshold
  used to connect sequences in the transmission network is a key parameter informing
  the properties of inferred networks. Using a distance threshold that is too high
  can result in a network with many spurious links, making it difficult to interpret.
  Conversely, a distance threshold that is too low can result in a network with too
  few links, which may not capture key insights into clusters of public health concern.
  Published research using the HIV-TRACE software package frequently uses the default
  threshold of 0.015 substitutions/site for HIV pol gene sequences, but in many cases,
  investigators heuristically select other threshold parameters to better capture
  the underlying dynamics of the epidemic they are studying. Here, we present a general
  heuristic scoring approach for tuning a distance threshold adaptively, which seeks
  to prevent the formation of giant clusters. We prioritize the ratio of the sizes
  of the largest and the second largest cluster, maximizing the number of clusters
  present in the network. We apply our scoring heuristic to outbreaks with different
  characteristics, such as regional or temporal variability, and demonstrate the utility
  of using the scoring mechanism's suggested distance threshold to identify clusters
  exhibiting risk factors that would have otherwise been more difficult to identify.
  For example, while we found that a 0.015 substitutions/site distance threshold is
  typical for US-like epidemics, recent outbreaks like the CRF07_BC subtype among
  men who have sex with men (MSM) in China have been found to have a lower optimal
  threshold of 0.005 to better capture the transition from injected drug use (IDU)
  to MSM as the primary risk factor. Alternatively, in communities surrounding Lake
  Victoria in Uganda, where there has been sustained heterosexual transmission for
  many years, we found that a larger distance threshold is necessary to capture a
  more risk factor-diverse population with sparse sampling over a longer period of
  time. Such identification may allow for more informed intervention action by respective
  public health officials.
featured: false
publication: '*Front Bioinform*'
tags:
- HIV; molecular epidemiology; network; surveillance; transmission cluster
doi: 10.3389/fbinf.2024.1400003
---

Page content here