# Mental Health in Tech - Analysis and HR Report

## Project Overview

This project analyzes the **Mental Health in Tech Survey** dataset to identify key factors influencing employees' likelihood to seek mental health treatment.  
The goal is to provide actionable insights for HR teams to improve mental health support in tech workplaces.

---

## Files in this Repository

| File Name                                          | Description |
|---------------------------------------------------|-------------|
| `Supporting Mental Health in Tech Workplace.docx`  | Full HR report in Word format. Summarizes key findings and actionable recommendations. |
| `Supporting Mental Health in Tech Workplace.pptx`  | PowerPoint presentation version of the report for HR or leadership stakeholders. |
| `code_notebook.ipynb`                             | Full Jupyter notebook with data preparation, EDA, feature engineering, model training (Random Forest, XGBoost, Logistic Regression), and evaluation metrics. |
| `Question.pdf`                                    | Problem Statement |
| `data.xlsx`                                       | Cleaned dataset used for analysis (Mental Health in Tech Survey). |
| `README.md`                                       | This file — project description and file reference. |

---

## Models and Metrics

Two models were trained using the top 20-30 most important features from Random Forest feature importance:

| Model                   | AUC-ROC | F1-score |
|-------------------------|---------|----------|
| Logistic Regression     | ~0.75   | ~0.63    |
| XGBoost Classifier      | ~0.80   | ~0.68    |

---

## Key Findings

- **Work interference** is the strongest predictor of treatment-seeking.
- **Family history** plays a major role.
- **Company-provided care options, benefits, and policies** directly impact outcomes.
- **Fear of career consequences** can suppress help-seeking.
- **Small companies** often lack structures to support mental health.

Full recommendations can be found in the report files (`.docx` and `.pptx`).

---

## How to Run

1. Install required libraries:
    ```bash
    pip install pandas scikit-learn xgboost matplotlib seaborn
    ```

2. Open `code_notebook.ipynb` in Jupyter Notebook or VSCode.

3. Run all cells to reproduce the analysis and generate models.

---

---
