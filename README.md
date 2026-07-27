# ExomeDepth-CNV-pipeline
Automated CNV detection pipeline for whole exome sequencing data using ExomeDepth with automated reference selection and annotation.

## Overview

Copy number variants (CNVs) are an important class of genomic variation associated with numerous inherited disorders and cancers. Detecting CNVs from targeted next-generation sequencing (NGS) data is challenging because read-depth based approaches require carefully selected reference samples and extensive manual processing.

This repository presents an automated analysis pipeline developed during my Master's research to streamline CNV detection using the ExomeDepth R package. The workflow automates reference sample selection, performs sex-aware reference matching, executes CNV calling, annotates detected variants, and generates analysis-ready reports while reducing manual intervention.

---
## Pipeline Overview

Targeted sequencing BAM files
            │
            ▼
Coverage extraction
            │
            ▼
Reference sample selection
            │
            ▼
Sex-aware matching
            │
            ▼
ExomeDepth CNV detection
            │
            ▼
CNV annotation
            │
            ▼
Analysis-ready reports

---

## Features

- Automated reference sample selection
- Sex-aware reference matching
- ExomeDepth-based CNV detection
- CNV annotation
- Parallel processing of multiple samples
- Automated report generation

---

## Requirements

- R (≥4.2)
- ExomeDepth (v1.1.18)
- GenomicRanges
- dplyr
- readr
- samtools
- Python 3
- Bash

---

## Usage

```bash
bash scripts/run_pipeline.sh
```

---

## Outputs

The pipeline produces:

- CNV calls
- Annotated CNV reports
- Summary files
- Intermediate analysis files

---

## Disclaimer

This repository contains only the computational workflow.

Patient information, clinical datasets, proprietary databases, institutional infrastructure details, and confidential resources have been removed or anonymized prior to public release.

---

