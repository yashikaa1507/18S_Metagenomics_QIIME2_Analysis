# 18S_Metagenomics_QIIME2_Analysis
In Silico Metagenomic Analysis (18S rRNA) using Bash and QIIME2
# 🧬 18S Metagenomic Analysis using QIIME2 and Bash

This repository showcases the metagenomic profiling of microbial communities using 18S rRNA sequencing data, analyzed via QIIME2 and Bash scripting.

---

## 🧪 Objective
To perform in silico metagenomic analysis using 18S rRNA amplicon data and classify microbial taxa present in the samples using QIIME2.

---

## 📁 Dataset
- Sample type: Fecal samples from unknown subjects  
- Platform: Illumina (paired-end)  
- 18S rRNA sequences  
- Data Size: ~100MB/sample

---

## 🔧 Tools & Technologies
- 🐧 Bash (for command-line processing)
- 🧬 QIIME2 (v2023.5)
- 📊 Excel (for downstream data interpretation)
- 🖥️ Ubuntu 20.04 LTS

---

## ⚙️ Workflow

1. Quality check of reads using FastQC  
2. Trimming adapters and low-quality regions  
3. Merging paired-end reads  
4. Creating manifest file and importing to QIIME2  
5. Denoising with DADA2  
6. Assigning taxonomy using SILVA 138 database  
7. Generating barplots and heatmaps  
8. Exporting results to Excel for visual analysis  

---

## 📊 Results

- Identified top phyla: **Ascomycota, Basidiomycota**  
- Top genera: **Candida, Saccharomyces**  
- Visualizations:  
  - ✅ Stacked barplots (relative abundance)  
  - ✅ Heatmaps for genera-level comparison

---

## 📁 Repo Contents

