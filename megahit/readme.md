# MEGAHIT Assembly

## Overview
MEGAHIT was used for de novo genome assembly of paired-end sequencing reads from Lactiplantibacillus plantarum.

## Software Version
MEGAHIT v1.2.9

## Input Files

- PID-1922-LAB5_S387_R1_001.fastq.gz
- PID-1922-LAB5_S387_R2_001.fastq.gz

## Command Used

```bash
megahit -1 PID-1922-LAB5_S387_R1_001.fastq.gz \
-2 PID-1922-LAB5_S387_R2_001.fastq.gz \
-o Megahit_Output
```

## Output Files

- final.contigs.fa
- log
- checkpoints.txt

## Author

Abha  
M.Sc. Bioinformatics  
Graphic Era (Deemed to be) University
