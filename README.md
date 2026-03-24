# Glioma Genomic Analysis — Mutation-Based Grade Prediction
Population-based analysis of glioma mutations utilizing publicly available datasets (TCGA)
🚀 QUICK VIEW: You can explore the full Exploratory Data Analysis (EDA) and the detailed variable dictionary here: 📊 analysis_notebook.ipynb

📖 About the Project
This project focuses on the molecular and clinical characterization of gliomas, a type of brain tumor. Using data from the The Cancer Genome Atlas (TCGA), we analyze how genetic mutations and clinical factors like age and gender correlate with the tumor grade.

The primary goal is to distinguish between LGG (Lower-Grade Glioma) and GBM (Glioblastoma Multiforme) based on a patient's mutational signature. This is a critical task in precision medicine, as it helps determine the most effective treatment path. 🧬

📑 Data Dictionary
To ensure transparency and reproducibility, we have defined a structured dictionary for the variables used in this study:

Clinical Features
Grade (Target): Clinical classification of the glioma.

0: LGG (Lower-Grade Glioma).

1: GBM (Glioblastoma Multiforme).

Gender: Biological sex (0: Male, 1: Female).

Age_at_diagnosis: Patient's age at the time of initial diagnosis (in decimal years). 📅

Race: Reported ethnic group (Numerically encoded).

Mutational Status (Molecular Signatures)
For the 20 genes analyzed (including IDH1, TP53, ATRX, PTEN, and EGFR), the encoding is:

0: Wildtype (No mutation detected).

1: Mutated (Presence of genetic alteration). 🧬

📊 Exploratory Data Analysis (EDA)
The project includes a comprehensive two-stage analysis to understand the underlying patterns of the dataset.

1. Univariate Analysis
We analyzed each variable in isolation to understand the population's baseline:

Class Balance: Checking the distribution of LGG vs. GBM cases. ⚖️

Demographics: Visualizing the age distribution (histogram) and gender/race frequencies.

Mutation Ranking: Identifying which genes are most frequently mutated across the entire dataset.

2. Bivariate Analysis
We investigated the relationships between clinical factors and the tumor grade:

Age vs. Grade: Utilizing boxplots to confirm the clinical hypothesis that GBM patients tend to be significantly older at diagnosis. 📈

Genomic Signatures: Comparing mutation rates of specific genes (like IDH1) across different grades to find diagnostic markers.

🛠️ Technologies Used
Language: Python 3.12+

Data Manipulation: Pandas, NumPy.

Visualization: Matplotlib, Seaborn.

Environment: VS Code, Jupyter Notebooks.

Version Control: Git & GitHub.

Project developed as part of the Master's Degree in AI & Big Data by Alejandro Benítez.
