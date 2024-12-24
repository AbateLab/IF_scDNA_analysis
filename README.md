# IF_scDNA_analysis
Analyze single-cell DNA data synthesized by Instrument Free method in two-cell experiment.
1. Input: a folder containing only `.fastq.gz` files of R1 and R2
2. Output: a .csv file matrix of barcodes vs. amplicon metrics
- These amplicon metrics include:
  - Read counts aligning to each target amplicon (i.e., AML panel of MissionBio)
  - Variants called selected by two-cell line experiment
  - Quality metrics: total read counts, evenness (1- Gini coefficient), entropy, Jaccard index, etc.
