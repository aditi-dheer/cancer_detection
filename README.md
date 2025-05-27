# 🩺 Breast Cancer Detection with Logistic Regression

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-007ACC?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

## Overview

A minimal implementation of **logistic regression from scratch** using NumPy for detecting breast cancer (malignant vs benign). This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** and includes preprocessing, training, evaluation, and accuracy metrics.

---

## Dataset

- Target: `diagnosis` → `M` (1), `B` (0)
- Dropped columns: `id`, `Unnamed: 32`
- Normalized all feature values between 0 and 1

---

## Key Features

- Gradient descent optimization with forward & backward propagation
- Accuracy metrics for both train and test datasets
- Clean preprocessing and normalization pipeline

---

## Results

- **Training Accuracy:** ~91%  
- **Testing Accuracy:** ~88%  

---

## Tech Stack

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Python      | Core programming language        |
| NumPy       | Matrix operations & math         |
| Pandas      | Data preprocessing               |
| Matplotlib  | Cost function plotting           |
| scikit-learn| Train-test splitting             |

