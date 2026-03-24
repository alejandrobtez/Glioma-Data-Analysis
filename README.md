# Glioma Genomic Analysis — Mutation-Based Grade Prediction

> **🚀 QUICK VIEW:** You can explore the core Exploratory Data Analysis (EDA) and the statistical logic here: [**notebook**](./glioma.ipynb)

---

## 📖 About the Project

**Gliomas** are the most common brain tumors and are classified into two groups based on their aggressiveness: **LGG** (Lower-Grade Glioma) and **GBM** (Glioblastoma Multiforme). Traditionally, grading is performed through histological criteria and imaging, but molecular and mutational factors are now crucial for an accurate diagnosis.

However, performing exhaustive molecular testing is very expensive. The challenge here is to use data from **20 frequently mutated genes** to correctly predict the tumor grade using publicly available datasets.

**The Goal:** To develop a predictive model that determines whether a patient has LGG or GBM based on their clinical and mutational profile. By identifying the optimal subset of genes and clinical features, we seek to improve diagnostic performance and significantly reduce the costs associated with comprehensive molecular testing. 🧪🔬

---

## 🧬 Data Structure & Features

The project utilizes a clinical and genomic dataset with the following key components:

* **Clinical Profile:** Key demographic indicators such as `Age_at_diagnosis`, `Gender`, and `Race`.
* **Genomic Profile:** Mutational status (0: Wildtype, 1: Mutated) for 20 genes (e.g., `IDH1`, `TP53`, `ATRX`, `PTEN`, `EGFR`). 🧬
* **Target:** `Grade` classification (0 for LGG, 1 for GBM). 🎯

---

## 📈 Exploratory Data Analysis (EDA)

The analysis performed focuses on identifying the key drivers of tumor aggressiveness.

### 1. Univariate Analysis
* **Class Distribution:** Evaluation of the balance between LGG and GBM cases. ⚖️
* **Age Distribution:** Statistical analysis of the patient population's age at diagnosis. 📅
* **Demographic Profile:** Breakdown of gender and race frequencies. 🌍
* **Mutational Frequency:** A ranking of the 20 genes based on how often they appear mutated in the population. 🧬

### 2. Bivariate Analysis
* **Age vs. Grade:** Visualizing how the patient's age correlates with tumor aggressiveness using boxplots. 📈
* **Mutations vs. Grade:** Comparative analysis of mutation rates per gene for each grade to identify specific diagnostic markers. 🔍

---

## 🛠️ Technologies Used

* **Language:** Python 3.12+ 
* **Data Science:** Pandas, NumPy. 
* **Visualization:** Matplotlib, Seaborn. 
* **Environment:** Antigravity, Jupyter Notebook. 

---
## 📂 Data Source

This project utilizes the **Glioma Grading Clinical and Mutation Features** dataset, sourced from the **UCI Machine Learning Repository**:

🔗 [Access the dataset here](https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset)

---
*Project developed by Alejandro Benítez.*
