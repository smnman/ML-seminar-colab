Predicting Infant Health Risks Using Explainable Machine Learning (XAI)

Machine Learning Seminar Project – 2026

This repository contains the full implementation of our seminar project:
Predicting Infant Health Risks Using Explainable AI (XAI).

The project evaluates classical machine learning, gradient boosting, and deep learning approaches for neonatal risk prediction, with emphasis on class imbalance handling and model interpretability (SHAP & LIME).

📌 Final Project File

The final and complete version of the project notebook is:

🔬 PredictingInfantHealthRisks.ipynb

Earlier notebooks (e.g., ML_seminar_notebook.ipynb - deleted from the repository) represent preliminary experiments and are not the finalized version of the study.

📂 Repository Structure

PredictingInfantHealthRisks.ipynb → Final project notebook

ML_seminar_notebook.ipynb → Early experimental version

newborn_health_monitoring_with_risk.csv → Dataset used in the study

README.md → Project documentation

📊 Dataset

The dataset used in this project is:

newborn_health_monitoring_with_risk.csv

The dataset has also been uploaded directly to this repository for reproducibility purposes.

If running the notebook locally, you may be prompted to upload the CSV file manually:

uploaded = files.upload()  # Choose the CSV file from your computer


Alternatively, the notebook can be modified to load the dataset from Google Drive.

⚙️ How to Run the Project

Open the notebook in Google Colab or Jupyter.

Install required dependencies if needed (e.g., xgboost, shap, imbalanced-learn).

Upload the CSV file when prompted (or adjust the file path).

Run all cells sequentially.

The notebook includes:

Data preprocessing pipeline

Feature engineering

SMOTE balancing

SVM, XGBoost, and CNN models

Cross-validation

SHAP & LIME explainability analysis

🔬 Research Context

This project was developed as part of a Computational Learning Seminar (2026).

The goal was to:

Improve neonatal risk prediction beyond previously reported baselines

Address severe class imbalance (6.5:1 ratio)

Compare classical ML and deep learning approaches

Integrate explainable AI tools for clinical transparency

📑 Reproducibility & Transparency

All preprocessing steps, model configurations, and evaluation procedures are fully documented within the final notebook.

The dataset is publicly available, and no private clinical data were used.

👥 Authors

Simon Farber
Omer Beck
Ruti Frida Danielashvili

⚠️ Notes

This repository reflects an academic research prototype and is not intended for direct clinical deployment.
