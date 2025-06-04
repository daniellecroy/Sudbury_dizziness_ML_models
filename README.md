# Machine Learning Models for Serious Outcome Risk Stratification in ED patients with dizziness or vertigo
 
This repository contains the R Markdown file used to clean data, train machine learning models, and generate plots and tables related to serious diagnoses among emergency department (ED) patients presenting with dizziness.

## 📁 Files

- `Sudbury_ML_Dizziness_models_final.Rmd` – Full analysis pipeline
  - Data cleaning and preprocessing
  - Model training (e.g., XGBoost, random forest, LASSO logistic regression)
  - Generation of plots and performance tables
- `Sudbury_ML_Dizziness_models_final.html` – Rendered output of the R Markdown file, viewable in a web browser

> Figures and tables are generated in the RMarkdown file, but not saved as separate output files.

## 📊 Data Access

Due to privacy considerations, the dataset used in this project is not publicly available.  
However, access may be granted upon reasonable request to:

📧 [robert.ohle@gmail.com](mailto:robert.ohle@gmail.com)

## 🔁 How to Reproduce

1. Download or clone the repository.
2. Open `Sudbury_ML_Dizziness_models_final.Rmd` in RStudio.
3. Install the required packages: 
    install.packages(c("tidyverse", "xgboost", "caret", "randomForest", "pROC"))
4. Add the dataset (if granted access) to the appropriate path used in the .Rmd.
5. Knit the RMarkdown file to reproduce all results and figures.

## 🧪 Purpose
This project aims to develop and evaluate machine learning models for improving the risk stratification of patients presenting with dizziness in the ED. The ultimate goal is to support more accurate diagnosis and reduce unnecessary imaging or consultations.

## 📜 License
This project is licensed under the [MIT License](LICENSE.txt).  
You are free to use, modify, and distribute this work with proper attribution.

## 📬 Contact
For questions or collaboration inquiries, please contact:
Danielle Roy
📧 danroy@hsnri.ca
