# Bacterial Genome Assembly and Annotation Pipeline

## Overview

This repository contains an end-to-end bacterial genome assembly and annotation workflow using Illumina paired-end sequencing data of *Lactiplantibacillus plantarum*.

The workflow includes sequence quality assessment, read preprocessing, genome assembly, assembly evaluation, gene prediction, and genome annotation.

---

## Workflow

```text
Raw Reads
    │
    ▼
 FastQC
    │
    ▼
 fastp
    │
    ▼
FastQC (Trimmed Reads)
    │
 ┌──┴──┐
 ▼     ▼
SPAdes MEGAHIT
 │      │
 └──┬───┘
    ▼
  QUAST
    ▼
Prodigal
    ▼
 Prokka
    ▼
Annotated Genome
```

---

## Repository Structure

```text
Bacterial-Genome-Assembly-Annotation-Pipeline/
├── README.md
├── fastp/
├── megahit/
├── prodigal/
├── prokka/
├── quast/
└── spades/
```

---

## Tools Used

| Tool | Purpose |
|------|---------|
| FastQC | Raw read quality assessment |
| fastp | Adapter trimming and filtering |
| SPAdes | De novo genome assembly |
| MEGAHIT | Alternative genome assembly |
| QUAST | Assembly quality assessment |
| Prodigal | Gene prediction |
| Prokka | Genome annotation |

---

## Input Data

- PID-1922-LAB5_S387_R1_001.fastq.gz
- PID-1922-LAB5_S387_R2_001.fastq.gz

---

## Species Analyzed

*Lactiplantibacillus plantarum*

---

## Author

**Abha**

M.Sc. Bioinformatics

Graphic Era (Deemed to be) University
