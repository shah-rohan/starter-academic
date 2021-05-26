---
title: "Sequence deeper without sequencing more: Bayesian resolution of ambiguously mapped reads"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Alexander Ruthenburg

# Author notes (optional)
author_notes:
- Equal Contribution
- Equal Contribution

date: "2021-04-19"
doi: "10.1371/journal.pcbi.1008926"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *PLOS Computational Biology*
publication_short: In *PLOS Comp Biol*

abstract: Histone post-translational modifications (PTMs) are important genomic regulators often studied by chromatin immunoprecipitation (ChIP), whereby their locations and relative abundance are inferred by antibody capture of nucleosomes and associated DNA. However, the specificity of antibodies within these experiments has not been systematically studied. Here, we use histone peptide arrays and internally calibrated ChIP (ICeChIP) to characterize 52 commercial antibodies purported to distinguish the H3K4 methylforms (me1, me2, and me3, with each ascribed distinct biological functions). We find that many widely used antibodies poorly distinguish the methylforms and that high- and low-specificity reagents can yield dramatically different biological interpretations, resulting in substantial divergence from the literature for numerous H3K4 methylform paradigms. Using ICeChIP, we also discern quantitative relationships between enhancer H3K4 methylation and promoter transcriptional output and can measure global PTM abundance changes. Our results illustrate how poor antibody specificity contributes to the "reproducibility crisis," demonstrating the need for rigorous, platform-appropriate validation.

# Summary. An optional shortened abstract.
summary: Next-generation sequencing allows researchers to efficiently determine the sequences of hundreds of millions of short DNA fragments from an experiment. Many experiments use next-generation sequencing to count nucleic acid molecules in a population by sequencing small fragments of them and assigning them to different genomic features. To find the origins of those fragments, the corresponding sequences are aligned to the genome; these alignments can then be used in downstream analyses. However, this alignment process is complicated by the fact that the genome has many highly similar and repetitive sequences, making it difficult or impossible to unambiguously assign some sequences to a single genomic location. The common “solution” to this problem is to discard those sequencing reads that do not align to a single site; however, this can lead to significant biases and will hide an important part of the genome. To address this problem, we have developed SmartMap, which serves to process and appropriately weight the alignments of reads that map to more than one genomic location. This enables us to examine many genomic regions that were previously “invisible” to analysis and helps us draw new insights into the regulation and function of repetitive elements of the genome.

# Display this page in the Featured widget?
featured: true
---
