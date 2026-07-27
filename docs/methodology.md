# Methodology

## Overview

The pipeline performs copy number variation (CNV) detection from whole exome sequencing (WES) data using ExomeDepth.

The workflow consists of:

1. Coverage extraction from aligned BAM files.
2. Selection of optimal reference samples based on read count correlation.
3. Sex-aware reference matching to improve CNV detection accuracy.
4. CNV calling using the ExomeDepth algorithm.
5. Annotation of detected CNVs.
6. Generation of analysis-ready output reports.

The pipeline was designed to automate repetitive analysis steps while ensuring reproducibility and minimizing manual intervention.
