# SARS-CoV-2 Bioinformatics Analysis Project

## Overview

This project focuses on the bioinformatics analysis of SARS-CoV-2 whole-genome sequencing data. The 
workflow includes quality assessment, genome alignment, variant identification, and genomic 
characterization using reproducible computational approaches.

The project demonstrates the application of next-generation sequencing (NGS) bioinformatics tools for 
viral genomic surveillance.

---

## Research Objectives
The objectives for this research are to:-
- Perform quality assessment of SARS-CoV-2 sequencing reads.
- Map viral reads against the SARS-CoV-2 reference genome.
- Identify genomic variants.
- Generate reproducible bioinformatics analysis workflows.
- Demonstrate genomic surveillance approaches for viral pathogens.

---

## Dataset

The analysis uses publicly available SARS-CoV-2 sequencing datasets from the NCBI Sequence Read 
Archive (SRA).

Samples analysed:

| Sample ID |
|-----------|
| SRR13500958 |
| ERR5181310 |
| ERR5405022 |
| ERR5556343 |
| ERR5743893 |

---

## Reference Genome

Reference genome:

**SARS-CoV-2 Wuhan-Hu-1**

Accession: MN908947.3

Reference files and alignment indexes are stored in: reference/

---

## Bioinformatics Workflow


Raw FASTQ Reads
|
↓
Quality Control
(FastQC + MultiQC)
|
↓
Genome Alignment
(BWA-MEM)
|
↓
BAM Processing
(Samtools)
|
↓
Variant Calling
(FreeBayes)
|
↓
Variant Analysis


---

## Tools and Software

| Tool | Purpose |
|---|---|
| FastQC | Sequencing quality assessment |
| MultiQC | QC report aggregation |
| BWA | Genome alignment |
| Samtools | BAM processing |
| FreeBayes | Variant calling |
| Nextflow | Workflow management |
| nf-core/viralrecon | Viral genome analysis pipeline |

---

## Repository Structure


SARS_CoV2_Bioinformatics_Project/

├── data/
│ └── samples.txt

├── reference/
│ └── MN908947.fasta

├── results/
│ ├── QC_Reports/
│ └── Mapping/

├── scripts/

├── docs/

└── README.md


---

## Reproducibility

The project uses documented workflows and computational tools to enable reproducible SARS-CoV-2 
genomic analysis.

Raw sequencing data files are excluded from this repository because of their large size.

---

## Author

**Mugambi Isaiah**

Bioinformatics | Molecular Biology | Genomic Medicine

GitHub:
Mugambi24

---

## License

This project is intended for research and educational purposes.
