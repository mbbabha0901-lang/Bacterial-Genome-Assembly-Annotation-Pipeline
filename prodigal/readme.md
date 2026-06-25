# PRODIGAL Gene Prediction

## Overview
Prodigal was used to predict protein-coding genes from the SPAdes-assembled genome of Lactiplantibacillus plantarum.

## Software Version
Prodigal v2.6.3

## Input File

- contigs.fasta

## Command Used

```bash
prodigal \
-i contigs.fasta \
-a proteins.faa \
-d genes.ffn \
-f gff \
-o genes.gff
```

## Output Files

- proteins.faa
- genes.ffn
- genes.gff

## Purpose

The predicted genes can be used for:
- Functional annotation
- Comparative genomics
- Metabolic pathway analysis
- Protein sequence analysis

## Author

Abha  
M.Sc. Bioinformatics  
Graphic Era (Deemed to be) University
