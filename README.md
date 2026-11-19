# Machine Learning-Based Early Prediction of Chronic Kidney Disease Using Clinical Data

## Overview
This project focuses on the early prediction of Chronic Kidney Disease (CKD) using clinical and laboratory data through machine learning techniques. It includes data preprocessing, exploratory data analysis, model development, performance evaluation, statistical analysis, and explainable AI.

## Objectives
- Preprocess and analyse clinical data.
- Perform exploratory data analysis (EDA).
- Develop and compare machine learning classification models.
- Evaluate models using multiple performance metrics.
- Identify important clinical features.
- Explore model interpretability using SHAP and LIME.

## Dataset
The project uses the Chronic Kidney Disease dataset from the UCI Machine Learning Repository.

- Original records: 400
- Features: 25
- Target: CKD classification (CKD / Not CKD)

## Methodology
1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Machine Learning Model Development
4. Hyperparameter Tuning
5. Model Evaluation and Comparison
6. Statistical Analysis
7. Explainable AI using SHAP and LIME

## Machine Learning Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Extra Trees
- Gaussian Naive Bayes
- CatBoost
- LightGBM

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Best Model
Extra Trees Classifier achieved the best overall performance in the experiments.

| Metric | Score |
|---|---:|
| Accuracy | 98.75% |
| Precision | 100% |
| Recall | 96.67% |
| F1-Score | 98.31% |
| ROC-AUC | 1.0000 |

Logistic Regression also achieved a recall of 100%.

## Explainable AI
SHAP and LIME were used to investigate feature importance and improve the interpretability of machine learning predictions.

## Repository Structure
- `Dataset/` – Dataset files
- `Figures/` – Research visualizations
- `Notebooks/` – Jupyter notebooks
- `Results/` – Experimental results and analysis
- `Saved_Models/` – Trained models

## Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, LightGBM, CatBoost, SHAP, LIME, Jupyter Notebook, Google Colab, Git, and GitHub.

## Limitations
The dataset is relatively small. The experimental results should not be interpreted as evidence of clinical reliability. Further validation using larger and independent datasets is necessary.

## Author
**Shoriful Islam**  
Computer Science and Engineering

## Disclaimer
This project is intended for academic and research purposes only. It is not intended for medical diagnosis or clinical decision-making.
