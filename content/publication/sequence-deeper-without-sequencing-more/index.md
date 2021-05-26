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

abstract: Next-generation sequencing (NGS) has transformed molecular biology and contributed to many seminal insights into genomic regulation and function. Apart from whole-genome sequencing, an NGS workflow involves alignment of the sequencing reads to the genome of study, after which the resulting alignments can be used for downstream analyses. However, alignment is complicated by the repetitive sequences; many reads align to more than one genomic locus, with 15–30% of the genome not being uniquely mappable by short-read NGS. This problem is typically addressed by discarding reads that do not uniquely map to the genome, but this practice can lead to systematic distortion of the data. Previous studies that developed methods for handling ambiguously mapped reads were often of limited applicability or were computationally intensive, hindering their broader usage. In this work, we present SmartMap: an algorithm that augments industry-standard aligners to enable usage of ambiguously mapped reads by assigning weights to each alignment with Bayesian analysis of the read distribution and alignment quality. SmartMap is computationally efficient, utilizing far fewer weighting iterations than previously thought necessary to process alignments and, as such, analyzing more than a billion alignments of NGS reads in approximately one hour on a desktop PC. By applying SmartMap to peak-type NGS data, including MNase-seq, ChIP-seq, and ATAC-seq in three organisms, we can increase read depth by up to 53% and increase the mapped proportion of the genome by up to 18% compared to analyses utilizing only uniquely mapped reads. We further show that SmartMap enables the analysis of more than 140,000 repetitive elements that could not be analyzed by traditional ChIP-seq workflows, and we utilize this method to gain insight into the epigenetic regulation of different classes of repetitive elements. These data emphasize both the dangers of discarding ambiguously mapped reads and their power for driving biological discovery.

# Summary. An optional shortened abstract.
summary: Next-generation sequencing allows researchers to efficiently determine the sequences of hundreds of millions of short DNA fragments from an experiment. Many experiments use next-generation sequencing to count nucleic acid molecules in a population by sequencing small fragments of them and assigning them to different genomic features. To find the origins of those fragments, the corresponding sequences are aligned to the genome; these alignments can then be used in downstream analyses. However, this alignment process is complicated by the fact that the genome has many highly similar and repetitive sequences, making it difficult or impossible to unambiguously assign some sequences to a single genomic location. The common “solution” to this problem is to discard those sequencing reads that do not align to a single site; however, this can lead to significant biases and will hide an important part of the genome. To address this problem, we have developed SmartMap, which serves to process and appropriately weight the alignments of reads that map to more than one genomic location. This enables us to examine many genomic regions that were previously “invisible” to analysis and helps us draw new insights into the regulation and function of repetitive elements of the genome.

# Display this page in the Featured widget?
featured: true
---
