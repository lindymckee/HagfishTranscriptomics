# HagfishTranscriptomics
## Background

## Methods
We are trying to identify genes that are differentially expressed among skin, slime gland, and barbel tissues in the Atlantic Hagfish (Myxine glutinosa). Our project includes four major steps:
  1. Assemble transcriptome
  2. Map reads to transcriptome
  3. Measure gene expression based on read coverage
  4. Identify the genes that are differentially expressed

Step 1: Assemble transcriptome Transcriptome was assembled using Trinity. Forward reads were concatenated to one file from forward reads from a skin, slime gland, and barbel sample. We also concatenated backward reads from each sample.

Step 2: Map reads to transcriptome Paired-end reads from 4 barbel samples, 3 skin samples, and 3 slime gland samples will be mapped onto the transcriptome using Salmon.

Step 3: Measure gene expression based on read coverage. Download mapping directory and upload to R. Analyze differential gene expression using EdgeR. Build multi-dimensional-scaling plot. Do pairwise comparisons between tissues (barbel vs skin, barbel vs slime gland, skin vs slime gland).

Step 4: Identify the genes that are differentially expressed BLAST search of nucleotide sequences identified in step 3

## Findings
