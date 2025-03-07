---
title: CPE tools
description: Software tools
showHeader: false
---

{{< toc >}}

## HyPhy

**Description:** HyPhy (Hypothesis testing using Phylogenies) is a software package for the analysis of molecular sequences using phylogenetic methods. It provides a wide range of statistical methods for testing evolutionary hypotheses, particularly selection pressure, recombination, and molecular clock models, using phylogenetic trees.

**Use in Pathogen Evolution:** HyPhy is extensively used to study pathogen evolution by:

  * **Detecting natural selection:** Identifying genes or sites under positive or negative selection, which is crucial for understanding how pathogens adapt to their hosts and environments.
  * **Analyzing evolutionary rates:** Estimating the rate of evolution in different lineages or genes of pathogens, helping to understand their adaptation and spread.
  * **Inferring recombination:** Detecting and characterizing recombination events in pathogen genomes, which is a significant mechanism of pathogen evolution and drug resistance.
  * **Testing molecular clock models:** Evaluating the temporal signal in pathogen sequences to understand their evolutionary history and timescale.

**Estimated Citations:**  Over 2,000 (estimated based on citation counts for key HyPhy papers on Google Scholar).

**Original Paper Citation:**

Pond, S. L. K., Frost, S. D. W., & Muse, S. V. (2005). HyPhy: hypothesis testing using phylogenies. *Bioinformatics*, *21*(5), 676-679. [https://academic.oup.com/bioinformatics/article/21/5/676/228688](https://academic.oup.com/bioinformatics/article/21/5/676/228688)

-----

## GARD

**Description:** GARD (Genetic Algorithm Recombination Detection) is a method implemented within HyPhy for detecting recombination breakpoints in sequence alignments. It uses a genetic algorithm to search for the optimal placement of breakpoints that minimize the phylogenetic incongruence across different genomic regions.

**Use in Pathogen Evolution:** GARD is specifically used in pathogen evolution to:

  * **Identify recombination events:** Accurately detect and locate recombination breakpoints in pathogen genomes. Recombination is a major driver of evolution in many pathogens, including viruses and bacteria, allowing for rapid adaptation and the emergence of novel strains.
  * **Characterize mosaic structures:**  Understand the mosaic structure of recombinant pathogen genomes, which is essential for tracking the origins and spread of recombinant variants.
  * **Improve phylogenetic inference:** By accounting for recombination, GARD can help to generate more accurate phylogenetic trees for pathogens, leading to better evolutionary and epidemiological analyses.

**Estimated Citations:** Over 700 (estimated based on citation counts for the original GARD paper on Google Scholar).

**Original Paper Citation:**

Kosakovsky Pond, S. L., Posada, D., Gravenor, M. B., Woelk, C. H., & Frost, S. D. W. (2006). GARD: genetic algorithm recombination detection. *Bioinformatics*, *22*(24), 3092-3098. [https://academic.oup.com/bioinformatics/article/22/24/3092/219931](https://academic.oup.com/bioinformatics/article/22/24/3092/219931)

-----

## 3SEQ

**Description:** 3SEQ is a method for detecting recombination signals in DNA sequence alignments. It identifies triplets of sequences where two sequences are more closely related to each other in a specific region of the alignment than they are to the third sequence, suggesting a recombination event.

**Use in Pathogen Evolution:** In the context of pathogen evolution, 3SEQ is used to:

  * **Screen for recombination:** Quickly screen large datasets of pathogen sequences to identify potential recombination events. It is particularly useful for exploratory analysis and identifying regions of interest for further investigation.
  * **Support recombination hypotheses:** Provide statistical support for recombination events detected by other methods or inferred from phylogenetic incongruence.
  * **Understand recombination hotspots:** Identify genomic regions that are prone to recombination in pathogens.

**Estimated Citations:** Over 300 (estimated based on citation counts for the original 3SEQ paper on Google Scholar).

**Original Paper Citation:**

Boni, M. F., Posada, D., & Feldman, M. W. (2007). An approximate Bayesian method for detecting recombination in DNA sequences. *Genetics*, *176*(4), 2539-2552. [https://www.genetics.org/doi/10.1534/genetics.107.073184](https://www.genetics.org/doi/10.1534/genetics.107.073184)

-----

## HIV Trace

**Description:** HIV-TRACE (HIV-TRansmission Analysis by Co-occurrence of Evolutionarily-similar sequences) is a tool designed for identifying potential HIV transmission clusters from large sequence databases. It uses phylogenetic methods to analyze HIV sequences and identify groups of sequences that are closely related, suggesting recent transmission links.

**Use in Pathogen Evolution:** HIV-TRACE is specifically tailored for studying HIV transmission dynamics and evolution by:

  * **Inferring transmission clusters:** Identifying groups of individuals likely linked by direct or indirect HIV transmission, which is crucial for understanding HIV epidemiology and designing targeted interventions.
  * **Analyzing transmission networks:** Mapping potential HIV transmission networks to understand patterns of spread and identify high-risk populations or transmission routes.
  * **Monitoring epidemic dynamics:** Tracking the evolution and spread of HIV over time and geographically, providing insights into epidemic trends and the impact of interventions.

**Estimated Citations:** Over 200 (estimated based on citation counts for the HIV-TRACE paper on Google Scholar).

**Original Paper Citation:**

Pond, S. L. K., Weaver, S., Leigh Brown, A. J., & Wertheim, J. O. (2018). HIV-TRACE (TRansmission Analysis by Co-occurrence of Evolutionarily-similar sequences). *Infectious Diseases and Therapy*, *7*(1), 45-59. [https://link.springer.com/article/10.1007/s40121-017-0189-y](https://link.springer.com/article/10.1007/s40121-017-0189-y)

-----

## Seroepi

**Description:** Seroepi is a term referring to serological epidemiology, which is the study of the distribution and determinants of health and disease in populations using serological data. While not a specific software tool like the others, seroepidemiological studies utilize various statistical and computational methods to analyze antibody data. In the context of pathogen evolution, it involves analyzing changes in antibody prevalence and titers over time to infer past infections and population immunity.

**Use in Pathogen Evolution:** Seroepidemiology is used in pathogen evolution to:

  * **Reconstruct past epidemics:** Infer the timing and magnitude of past pathogen outbreaks by analyzing serological data from different time points.
  * **Estimate infection rates and seroprevalence:** Determine the proportion of a population that has been infected with a pathogen and developed antibodies.
  * **Understand population immunity:** Assess the level of population immunity to a pathogen, which is important for predicting future outbreaks and evaluating vaccine effectiveness.
  * **Infer evolutionary dynamics:** By linking serological data with genetic data, seroepi can help to understand how pathogen evolution shapes and is shaped by population immunity.

**Estimated Citations:**  Seroepidemiology is a field of study, not a specific tool, so citation counts are not directly applicable to a single "original paper". However, key methodological papers and studies in seroepidemiology are highly cited. For example, papers describing fundamental statistical methods for analyzing serological data or seminal seroepidemiological studies of important pathogens can have thousands of citations.

**Original Paper Citation (Example - Methodological Paper):**

Macdonald, P. D. M. (1970). Statistical inference from serological surveys. *Journal of Hygiene*, *68*(4), 743-750. [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2130558/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2130558/)

*(Note: This is an example of a foundational paper in serological data analysis.  For specific applications of "Seroepi" in pathogen evolution, you would cite papers relevant to the specific pathogen and serological methods used.)*