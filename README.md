# Credit Card Fraud Detection using Feature Selection

This project investigates the effect of **feature selection techniques** on the **generalization ability** of machine learning models for fraud detection. The goal is to identify and analyze features that improve accuracy, robustness, and adaptability across different datasets.

---

## 📌 Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

---

## 🔎 Introduction
Fraud detection systems rely heavily on **machine learning models** to identify anomalous transactions.  
However, not all features contribute equally to performance. This project studies the **impact of feature selection techniques** on model generalization.  

Key objectives:
- Evaluate different **feature selection methods** (filter, wrapper, embedded).  
- Determine **feature subsets** that enhance robustness and reduce overfitting.  
- Provide guidelines for selecting features in **fraud detection applications**.

---

## 🛠 Requirements
Ensure the following Python packages are installed:

```bash
Python >= 3.7
numpy == 1.21.2
pandas == 1.3.3
scikit-learn == 0.24.2
matplotlib == 3.4.3
seaborn == 0.11.2
imbalanced-learn == 0.8.0
```
## Install them using:

```bash
pip install -r requirements.txt
```
⚙️ Installation
1. Clone the repository:
```bash
git clone https://github.com/amanyadav2022/Credit-Card-Fraud-Detection-using-feature-selection.git
cd Credit-Card-Fraud-Detection-using-feature-selection
```
🚀 Usage
1. Open the Jupyter Notebook:
```bash
jupyter notebook "Code Files.ipynb"
```
2. Run each cell sequentially.
3. The notebook includes:
   -Data loading & preprocessing
   -Feature selection & importance analysis
   -Model training, evaluation & generalization testing
   
📊 Project Workflow

  1.Dataset Collection & Preprocessing
      Data exploration, handling imbalance (SMOTE), encoding, scaling, outlier detection.
  2.Feature Selection & Dimensionality Reduction
      Linear Discriminant Analysis (LDA).
  3.Model Implementation
      Naive Bayes, KNN, Decision Tree, Random Forest, Logistic Regression, Bagging.
  4.Evaluation & Results
      Compared before/after applying SMOTE, LDA, and feature selecti
      
📈 Results

    | Model               | Precision | Recall | F1-Score | ROC-AUC |
    | ------------------- | --------- | ------ | -------- | ------- |
    | Random Forest       | 0.93      | 0.91   | 0.92     | 0.97    |
    | KNN                 | 0.90      | 0.88   | 0.89     | 0.95    |
    | Naive Bayes         | 0.85      | 0.80   | 0.82     | 0.90    |
    | Logistic Regression | 0.88      | 0.84   | 0.86     | 0.92    |

  -Random Forest and KNN with SMOTE & LDA showed the best fraud detection performance.
  -Feature selection improved generalization and reduced overfitting.
  -Visualizations of confusion matrices & ROC curves confirmed robustness.
   
