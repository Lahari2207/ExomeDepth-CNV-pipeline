# ExomeDepth-CNV-pipeline
Automated CNV detection pipeline for whole exome sequencing data using ExomeDepth with automated reference selection and annotation.

## Overview

This repository contains an automated bioinformatics pipeline developed for copy number variation (CNV) detection from whole exome sequencing (WES) data using the ExomeDepth R package.

The pipeline automates reference sample selection, performs sex-aware reference matching, detects CNVs, annotates identified variants, and generates analysis-ready output files.

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

