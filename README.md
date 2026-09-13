# Hi, I'm Ruitao Zhang

*PhD Student in Biomedical Engineering @ Northwestern University*
*Computational Genomics • Graph Representation Learning • Spatial Proteomics • Cancer Biology*

---

## 🧬 About Me

I am a PhD student in **Biomedical Engineering at Northwestern University**, developing computational methods to study how molecular organization, cellular phenotype, and disease state are connected.

My research sits at the intersection of:

* **Machine learning and deep learning**
* **Graph representation learning**
* **Computational and single-cell genomics**
* **Spatial and proximity proteomics**
* **Cancer biology and immuno-oncology**

I am particularly interested in transforming complex biological measurements—ranging from sequencing and protein-structure data to cell-surface molecular graphs and microscopy images—into interpretable representations of cellular state.

My recent work spans three connected areas:

1. Learning the surface molecular organization of CAR-T cells from single-cell proximity graphs
2. Developing image-analysis workflows for circulating tumor cells and immune-cell clusters
3. Integrating multi-omic evidence to characterize non-canonical ORF translation and immunogenicity

---

## 🔬 Current Research

### 🧩 Learning T-Cell States from Surface Molecular Topology

In collaboration with researchers at **Chan Zuckerberg Biohub Chicago**, I study whether the nanoscale organization of cell-surface proteins can provide a learnable and biologically interpretable representation of T-cell state.

Using **Molecular Pixelation (MPX)** proximity-proteomics data, I develop computational methods to:

* Construct protein-resolved single-cell proximity graphs
* Learn topology-preserving embeddings with **GINE and PNA graph neural networks**
* Perform self-supervised reconstruction of local molecular organization
* Compare acute and chronic CAR-T stimulation states
* Evaluate donor generalization and potential biological shortcuts
* Discover interpretable local surface-organization programs
* Relate molecular topology to T-cell identity, polarization, and functional state

The broader goal is to establish cell-surface topology as a quantitative layer of cellular phenotype that complements conventional protein-abundance measurements.

---

### 🔬 CTC and Immune-Cell Image Analysis

In the **Huiping Liu Lab**, I am working on computational analysis of circulating tumor cells and associated immune-cell populations from multiplex microscopy images.

The analysis workflow integrates:

* **Cellpose-based cell segmentation**
* Cell-level morphology, intensity, texture, and spatial feature extraction
* **XGBoost-based cell-type classification**
* Identification of homotypic and heterotypic cell clusters
* Image-level and patient-level feature aggregation
* Association of cellular phenotypes with clinical and survival outcomes

A central biological interest is understanding how circulating tumor cells interact with immune cells and how these multicellular patterns vary across patient groups, including breast-cancer age groups.

---

### 🧬 Multimodal Modeling of Non-Canonical ORFs

My earlier PhD research focused on developing a multimodal computational framework for characterizing **non-canonical open reading frames (ncORFs)** and their potential immunogenicity.

The framework integrates:

* Ribo-seq periodicity and translation evidence
* RNA-seq and tissue-specific expression
* CAGE-seq transcription-start-site signals
* Proteomic evidence
* AlphaFold structural-confidence features
* B-cell and MHC epitope predictions
* Machine-learning and deep-learning models
* Reproducible HPC workflows for genome-scale analysis

The long-term goal is to identify translated ncORFs with tissue-specific, structural, and immunological evidence that may be relevant to cancer biology and therapeutic discovery.

---

## 🛠️ Technical Skills

**Programming**
Python • R • Bash • SQL

**Machine Learning**
PyTorch • PyTorch Geometric • scikit-learn • XGBoost • Self-Supervised Learning • Representation Learning • Feature Selection • Survival Modeling

**Computational Biology**
Single-Cell Analysis • Graph-Based Proteomics • Spatial Proteomics • Ribo-seq • RNA-seq • ATAC-seq • Multi-Omics Integration • Immunogenicity Prediction

**Image Analysis**
Cellpose • Cellular Segmentation • Morphological and Intensity Feature Extraction • Spatial Cell-Interaction Analysis

**Research Computing**
SLURM • Snakemake • Git/GitHub • Docker • Conda • Linux • High-Performance Computing

---

## 📂 Selected Projects

### 🔹 Cell-Surface Topology Representation Learning

A graph-learning framework for representing CAR-T-cell state from Molecular Pixelation proximity networks.

**Methods:** GINE/PNA, self-supervised learning, donor-aware validation, structural-program discovery, and interpretable graph analysis.

---

### 🔹 CTC Image-Analysis Pipeline

A modular microscopy-analysis workflow connecting cell segmentation, feature extraction, cell-type classification, cluster detection, quality control, and downstream clinical analysis.

**Methods:** Cellpose, image-derived feature engineering, XGBoost, spatial clustering, and survival analysis.

---

### 🔹 ncORF Immunogenicity Modeling

A multimodal framework integrating sequencing, proteomic, structural, tissue-specific, and epitope-prediction evidence to characterize non-canonical ORFs.

**Methods:** Ribo-seq/RNA-seq integration, AlphaFold-derived features, immunogenicity prediction, machine learning, and HPC workflow development.

---

### 🔹 RNA-Seq Analysis Pipeline

An end-to-end workflow for bulk and single-cell RNA-seq analysis, including quality control, differential expression, enrichment analysis, and visualization.

[View repository →](https://github.com/RichardRuitaoZhang/RNA-Seq-Analysis-Pipeline)

---

## 📊 GitHub Overview

<!-- Profile Summary Cards: auto-updated by GitHub Actions -->

<p align="center">
  <img src="https://raw.githubusercontent.com/RichardRuitaoZhang/RichardRuitaoZhang/main/profile-summary-card-output/github/0-profile-details.svg" width="90%"/>
  <img src="https://raw.githubusercontent.com/RichardRuitaoZhang/RichardRuitaoZhang/main/profile-summary-card-output/github/1-repos-per-language.svg" height="140px"/>
  <img src="https://raw.githubusercontent.com/RichardRuitaoZhang/RichardRuitaoZhang/main/profile-summary-card-output/github/2-most-commit-language.svg" height="140px"/>
  <img src="https://raw.githubusercontent.com/RichardRuitaoZhang/RichardRuitaoZhang/main/profile-summary-card-output/github/3-stats.svg" height="140px"/>
</p>

---

## 🎯 Research Interests

* Interpretable machine learning for biological systems
* Graph representation learning for cellular organization
* Single-cell and spatial multi-omics
* Cancer immunology and circulating tumor cells
* Non-canonical translation and tumor immunogenicity
* Computational methods that connect molecular structure to cellular phenotype

---

## 📫 Connect

I am always interested in discussions and collaborations involving computational genomics, graph learning, spatial proteomics, cancer biology, and interpretable biomedical AI.

Thank you for visiting my profile!
