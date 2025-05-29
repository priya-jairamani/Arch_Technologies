# Arch-Technologies: ML Classification Internship

This repository contains implementations of fundamental machine learning classification techniques using the MNIST and Wine Quality datasets. The projects demonstrate model training, evaluation, and optimization with a focus on practical understanding of algorithms and performance analysis.

## 📌 Projects Included

### 🔢 Task 01: MNIST Digit Classification
- **Goal**: Classify handwritten digits (0–9) from the MNIST dataset.
- **Models Used**:
  - `SGDClassifier` (Stochastic Gradient Descent)
  - `RandomForestClassifier`
- **Evaluation**:
  - Cross-validation
  - Confusion Matrix
  - Precision, Recall, F1 Score, ROC Curve
- **Techniques**:
  - One-vs-Rest (OvR) vs One-vs-One (OvO)
  - Error analysis and training/validation curves
  - Image preprocessing (e.g., sharpening) for accuracy improvement

### 🍷 Task 02: Wine Quality Prediction
- **Dataset**: Red Wine Quality dataset from UCI
- **Objective**: Predict if a wine is 'good' (quality ≥ 6) or 'bad' (quality < 6)
- **Models Used**:
  - Logistic Regression
  - SGDClassifier
  - Ridge Classifier (best performing)
- **Features**:
  - Polynomial features (degree = 2)
  - Regularization: Ridge (L2), Lasso (L1), ElasticNet
  - Learning curve visualization
  - Grid search for hyperparameter tuning

## 🚀 Getting Started

### Requirements
- Python 3.8+
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn (optional for visualization)

### Installation
Clone the repository:
```bash
https://github.com/priya-jairamani/Arch_Technologies.git
cd Arch-Technologies
