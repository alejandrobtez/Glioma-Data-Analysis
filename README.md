# Glioma Genomic Analysis — Mutation-Based Grade Prediction

> **🚀 QUICK VIEW:** You can explore the core Exploratory Data Analysis (EDA) and the statistical logic here: [**📊 analysis_notebook.ipynb**](./analysis_notebook.ipynb)

---

## 📖 About the Project

**GliomaVision** is a data-driven project designed to characterize brain tumors using genomic and clinical data from the **TCGA (The Cancer Genome Atlas)**.

The project bridges the gap between raw mutational data and clinical diagnosis. By analyzing the relationship between **20 specific gene mutations** and patient demographics, we aim to identify the molecular signatures that distinguish Low-Grade Gliomas (LGG) from Glioblastomas (GBM).

---

## 🧬 Data Structure & Features

The dataset integrates clinical metadata with binary mutational status for key oncogenes.

* **Clinical Profile:** Includes `Age_at_diagnosis`, `Gender`, and `Race`.
* **Genomic Profile:** Binary indicators (0: Wildtype, 1: Mutated) for 20 genes such as `IDH1`, `TP53`, `PTEN`, and `EGFR`.
* **Target Variable:** `Grade` (0 for LGG, 1 for GBM).

---

## 📈 Exploratory Data Analysis (EDA)

The analysis is divided into two main stages to uncover patterns within the population.

### 1. Univariate Analysis
* **Demographics:** Examination of age distribution and gender balance within the study.
* **Mutation Frequency:** A ranking of the most prevalent genetic alterations across all patients.

### 2. Bivariate Analysis
* **Age vs. Grade:** Validation of the clinical hypothesis that higher-grade tumors (GBM) correlate with advanced age.
* **Mutational Signatures:** Identifying "diagnostic markers" by comparing mutation rates between LGG and GBM.

---

## 🛠️ Technologies Used

* **Language:** Python 3.12+
* **Data Science:** Pandas, NumPy.
* **Visualization:** Matplotlib, Seaborn.
* **Environment:** VS Code, Jupyter Notebook.

---
*Project developed as part of the Master's Degree in AI & Big Data by Alejandro Benítez.*
