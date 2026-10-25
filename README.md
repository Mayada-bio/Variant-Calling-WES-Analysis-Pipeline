# 🧬 Variant-Calling-WES-Analysis-Pipeline

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1esBPzmlFm-iO2HTwelOMZyk-cj9_82pr)
![Bioinformatics](https://img.shields.io/badge/Domain-Bioinformatics-blue.svg)
![GATK4](https://img.shields.io/badge/GATK-v4.0+-orange.svg)
![Python](https://img.shields.io/badge/Python-3.10+-green.svg)

An end-to-end, production-grade clinical bioinformatics pipeline for **Whole Exome Sequencing (WES)** data processing, high-confidence variant discovery, and automated clinical annotation using GATK Best Practices and NCBI ClinVar integration.

---

## 🔬 Scientific Overview
This pipeline addresses the core requirements of clinical genomics by taking raw sequencing reads (`FASTQ`), evaluating base quality, aligning reads against the human reference genome (GRCh37/hg19 Chromosome 21), marking PCR duplicates, executing variant calling via `GATK HaplotypeCaller`, and annotating clinical pathogenicity through direct querying of the **NCBI ClinVar** database.

---

## ⚙️ Workflow Pipeline Architecture
