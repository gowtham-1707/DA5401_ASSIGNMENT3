# DA5401 Assignment 3: Addressing Class Imbalance with Clustering and Resampling

This repository contains a Jupyter Notebook for **DA5401 Assignment 3**, which explores class imbalance in credit card fraud detection. The notebook demonstrates and compares naive and clustering-based resampling methods and their impact on Logistic Regression performance.

## Contents

- `ma24c051_Assignment_3.ipynb`: Main notebook with code, visualizations, and explanations.
- `creditcard.csv`: Dataset (not included; download from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)).
- `README.md`: This file.

## Assignment Overview

**Objective:**  
To address the challenge of class imbalance in fraud detection using:
- Naive oversampling (SMOTE)
- Clustering-based oversampling (CBO)
- Clustering-based undersampling (CBU)

**Key Steps:**
1. Data exploration and baseline model.
2. Apply SMOTE and explain its limitations.
3. Implement clustering-based oversampling and undersampling.
4. Train and evaluate Logistic Regression models on each resampled dataset.
5. Compare model performances using precision, recall, and F1-score for the minority class.
6. Discuss the benefits and drawbacks of each method.

## How to Run

1. Download the `creditcard.csv` dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) and place it in the same directory as the notebook.
2. Open `ma24c051_Assignment_3.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells in order.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- imbalanced-learn (`imblearn`)

Install requirements with:
```bash
pip install pandas numpy scikit-learn matplotlib imbalanced-learn
```

## Results

The notebook provides a detailed comparison of all four models (Baseline, SMOTE, CBO, CBU) and recommends the most effective resampling strategy for fraud detection.

---

*For academic use only. Dataset copyright: ULB Machine Learning Group.*
