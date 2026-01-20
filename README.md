# Applied Classification Models: Logistic Regression, Discriminant Analysis, Naive Bayes & SVM

**Author:** Abigail Albury-Bloom
**Focus:** Multi-Class Classification, Model Assumptions, and Algorithm Comparison
**Tools:** Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Kaggle

---

## Overview

This repository demonstrates applied **multi-class classification modeling** using a real-world dataset and Kaggle evaluation. The goal is to compare multiple modeling approaches—from interpretable statistical baselines to more flexible margin-based methods—while investigating assumptions and performance trade-offs.

The work emphasizes:

* Building and comparing multiple classification algorithms
* Validating assumptions and diagnosing model behavior
* Clear interpretation of results and error patterns
* Reproducible outputs, including Kaggle submission files

---

## Problem Context

**Multi-Class Prediction of Obesity Risk (Kaggle)**
Predict obesity risk categories based on demographic, behavioral, and physical features. This problem type is common in healthcare analytics and applied machine learning settings where accurate risk stratification supports downstream decision-making.

---

## Models Implemented

### 1. Multinomial Logistic Regression (Regularized)

* Interpretable linear baseline for multi-class outcomes
* Evaluated the impact of regularization on generalization

**Key considerations:** linear decision boundaries, multicollinearity sensitivity, calibration

---

### 2. Discriminant Analysis (LDA)

* Probabilistic classifier with class-conditional Gaussian assumptions
* Effective when classes are approximately linearly separable with shared covariance

**Key considerations:** normality assumptions, shared covariance structure

---

### 3. Naive Bayes (Gaussian NB)

* Strong baseline with conditional-independence assumption
* Often performs well even when assumptions are imperfect

**Key considerations:** independence assumption, feature scaling/transformations

---

### 4. Support Vector Machine (RBF Kernel)

* Nonlinear classifier capable of capturing complex boundaries
* Tuned hyperparameters to balance margin and misclassification

**Key considerations:** feature scaling requirement, sensitivity to `C` and `gamma`

---

## Evaluation & Diagnostics

* Compared model performance using Kaggle evaluation metrics
* Reviewed class imbalance and misclassification patterns
* Investigated assumptions and practical limitations per algorithm
* Discussed interpretability vs. accuracy trade-offs

---

## Files Included

* `Albury-BloomADDS8555-5.ipynb` – Complete modeling workflow and evaluation
* `Albury-BloomADDS8555-5.pdf` – Interpreted report with figures and conclusions
* `submission_logistic_l2.csv` – Logistic regression submission output
* `submission_lda.csv` – Discriminant analysis submission output
* `submission_gaussian_nb.csv` – Naive Bayes submission output
* `submission_svm_rbf.csv` – SVM submission output

---

## Key Skills Demonstrated

* Multi-class classification modeling
* Logistic regression with regularization
* Discriminant analysis (LDA)
* Naive Bayes classification
* Support Vector Machines (RBF)
* Model assumptions and diagnostics
* Comparative model evaluation
* Clear analytical communication

---

## Why This Project Matters

Comparing diverse classifiers is a core applied ML skill. This project demonstrates the ability to:

* Establish strong, interpretable baselines
* Evaluate probabilistic vs. margin-based classifiers
* Identify when model assumptions may break down
* Communicate practical recommendations based on evidence

---

## Contact

**Abigail Albury-Bloom**
🔗 LinkedIn: [https://www.linkedin.com/in/abigail-albury-bloom/](https://www.linkedin.com/in/abigail-albury-bloom/)

---

*This repository is part of an applied machine learning portfolio highlighting supervised learning and model evaluation.*
