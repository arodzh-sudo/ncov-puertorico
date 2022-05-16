# Genomic Epidemiology of SARS-CoV-2 in Puerto Rico
This public repository analyzes SARS-CoV-2 genomes using the [Nextstrain](https://nextstrain.org/) platform to understand how the virus that is responsible for the COVID-19 pandemic, evolves and spreads in Puerto Rico. By reconstructing a phylogeny we can learn about important epidemiological phenomena such as spatial spread, introduction timings and epidemic growth rate.

We maintain (updated weekly) a number of publicly-available builds, accesible at the [Nextstrain community site](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/):

I. [Dedicated VOC & VBM Nextstrain build](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time/?f_country=Puerto%20Rico)

II. [Dedicated Omicron (21K, 21L & 22C) Nextstrain build](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/Omicron?f_country=Puerto%20Rico&label=clade:21M%20%28Omicron%29)

III. [Dedicated Delta (21A, 21I & 21J) Nextstrain build](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/Delta?f_country=Puerto%20Rico&label=clade:21A%20%28Delta%29)

The "Variants of Concern (VOC) and Variants Being Monitored (VBM) build" incorporates [recent changes made by the Nextstrain team](https://github.com/nextstrain/ncov/pull/910) which splits the phylogeny into a ["six-months" build that focus subsampling on the previous six months](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time/?f_country=Puerto%20Rico) and a ["all-time" build that subsamples evenly across time](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?f_country=Puerto%20Rico). This uses the new relative dates functionality in ["augur filter" and "augur frequencies"](https://docs.nextstrain.org/projects/augur/en/stable/releases/changelog.html) to make these subsampling strategies easier to implement and set frequencies timespans to match subsampling ranges.

The SARS-CoV-2 genomes from Puerto Rico are analyzed against a diverse set of genomes from North America and the rest of the globe to provide phylogenetic context. Wuhan-Hu-1/2019 is used as a reference for site numbering and genome structure. The phylogeny is rooted relative to early samples from Puerto Rico and temporal resolution assumes a nucleotide substitution rate of 8 × 10^-4 substitutions per site per year.

Genomic sequences used in these analyses are obtained from [GISAID](https://gisaid.org) and remain subject to GISAID’s [Terms and Conditions](https://www.gisaid.org/registration/terms-of-use/). We gratefully acknowledge the authors, originating and submitting laboratories of the genetic sequences and metadata made available through [GISAID](https://gisaid.org).

*Note: These results are provided as heuristic guides only, based on literature review and phylogenetic analysis. Relationships between variants must be determined in conjunction with clinical, microbiological, and epidemiological information.*
