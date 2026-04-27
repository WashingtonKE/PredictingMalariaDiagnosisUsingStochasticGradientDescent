# Malaria Diagnosis & Prediction Models
**Author:** Washington Anyango  
**Reg. No.:** ST61/80935/2024  
**Course:** CSA 821: Machine Learning

This repository contains two distinct machine learning implementations focused on diagnosing malaria using clinical data. These projects address the healthcare challenges in Kenya, specifically in the Lake and Coastal regions, by providing scalable diagnostic tools.

## 1. Malaria Diagnosis Model (Random Forest & Pipelines)
This project compares multiple classifiers to determine the most robust method for clinical diagnosis.

- **Key Features:** End-to-end Scikit-Learn Pipelines, Hyperparameter tuning via `GridSearchCV`.
- **Top Performer:** **Random Forest** outperformed Logistic Regression.
- **Key Predictors:** Clinical markers such as **Hemoglobin levels** and **Parasite Density** were the most significant predictors.
- **Goal:** Support the **Kenya Health Policy** by reducing diagnostic turnaround time in rural health centers.

## 2. Predicting Malaria via Stochastic Gradient Descent (SGD)
This project focuses on computational efficiency for large-scale healthcare datasets using iterative optimization.

- **Model:** Logistic Regression optimized with **Stochastic Gradient Descent (SGD)**.
- **Focus:** Performance on binary classification tasks and the effect of feature scaling on model convergence.
- **Workflow:** Includes robust preprocessing, categorical encoding, and standardization essential for SGD stability.

---

## Technical Workflow
1. **Data Preprocessing:** - Handling missing values via `SimpleImputer`.
   - Feature Scaling using `StandardScaler`.
   - Categorical Encoding with `OneHotEncoder`.
2. **Model Training:** Comparative analysis of ensemble methods and linear models.
3. **Evaluation:** Metrics include Accuracy, Confusion Matrix, and Multi-class ROC curves.

## Installation & Usage
1. **Clone the repo:**
   ```bash
   git clone <your-repository-url>