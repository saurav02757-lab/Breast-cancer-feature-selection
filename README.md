# breast-cancer-feature-selection
Machine learning project demonstrating feature engineering and feature selection techniques using the Breast Cancer dataset.
# Breast Cancer Classification using Feature Engineering and Feature Selection

## Project Overview
In this project, I built a machine learning pipeline to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer dataset from scikit-learn.

The project demonstrates a complete ML workflow including:

- Feature Engineering
- Data Preprocessing using Pipelines
- Feature Selection (Filter, Wrapper, Embedded methods)
- Model Training using Random Forest
- Model Evaluation with Stratified K-Fold Cross Validation

## Tools & Technologies
- Python
- NumPy
- Pandas
- Scikit-learn

## Feature Selection Methods
1. **SelectKBest (Filter Method)** – selects top features based on univariate statistical tests  
2. **Recursive Feature Elimination (RFE, Wrapper Method)** – recursively removes least important features using Logistic Regression  
3. **SelectFromModel (Embedded Method)** – selects important features based on Random Forest feature importance  

## Key Results
- **Baseline (All Features):** 96.5% ± 0.55% accuracy  
- **SelectKBest:** 95.4% ± 1.51%  
- **RFE:** 95.1% ± 1.80%  
- **SelectFromModel:** 95.6% ± 2.0%  

**Insights:**  
- Baseline model achieved the highest accuracy, but feature selection improves interpretability.  
- Feature engineering significantly contributed to predictive performance.  
- SelectFromModel captured most important features while maintaining high accuracy.

## How to Run
1. Clone the repository:  
