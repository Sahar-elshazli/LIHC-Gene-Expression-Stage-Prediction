# LIHC Gene Expression Stage Prediction

## Overview
This project focuses on predicting the cancer stage (Stage I, II, or III) of Liver Hepatocellular Carcinoma (LIHC) patients using gene expression data. It utilizes two main approaches for feature selection and classification:
- **DESeq2 Analysis**: Machine learning models trained on genes identified as significant through DESeq2.
- **Wrapper & Embedded Methods**: Feature selection using RFECV and classification using an ensemble of models.

## Installation
To set up the environment, ensure you have Python installed and run:
```bash
pip install -r requirements.txt