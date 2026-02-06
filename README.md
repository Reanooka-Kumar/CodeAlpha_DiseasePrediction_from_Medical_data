# 🏥 HealthGuard AI: Advanced Disease Prediction Framework

> **AI-Driven Medical Diagnostics for Early Detection and Prevention**

[![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-15B550?style=for-the-badge&logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

## 📖 Overview
**HealthGuard AI** is a robust machine learning framework designed to assist medical professionals in the early prediction of critical diseases. By leveraging state-of-the-art classification algorithms—including **XGBoost**, **Random Forest**, and **Support Vector Machines (SVM)**—this system analyzes clinical data to predict the likelihood of **Heart Disease**, **Diabetes**, and **Breast Cancer** with high precision.

## 🚀 Key Features
- **Multi-Disease Support**: Specialized pipelines for three distinct medical conditions.
- **Advanced Preprocessing**: Automatic handling of missing values (Imputation), feature scaling (StandardScaler), and data balancing.
- **Model Comparison**: Benchmarks performance across 4 top-tier algorithms to select the best predictor.
- **High Accuracy**:
  - 🫀 **Heart Disease**: ~88% Accuracy (Random Forest)
  - 🎀 **Breast Cancer**: ~97% Accuracy (SVM)
  - 🩸 **Diabetes**: ~76% Accuracy (Random Forest)

## 🛠️ Tech Stack
- **Language**: Python 3.12+
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn, XGBoost
- **Visualization**: Matplotlib, Seaborn

## 📂 Project Structure
```bash
disease_prediction/
├── data_loader.py    # Handlers for UCI and Scikit-learn datasets
├── preprocessing.py  # Cleaning, imputation, and scaling pipelines
├── models.py         # Model wrapper for LR, SVM, RF, and XGB
├── main.py           # Orchestrator script for full workflow
└── requirements.txt  # Project dependencies
```

## ⚡ Getting Started

### Prerequisites
Ensure you have Python installed.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/healthguard-ai.git
   cd disease_prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Usage
Run the main analysis script to load data, train models, and generate reports:
```bash
python main.py
```

## 📊 Performance Insights
The system generates detailed classification reports (Precision, Recall, F1-Score).
*Example Output:*
```text
Dataset: Breast Cancer
  Best Model: SVM (Accuracy: 0.9737)
    Logistic Regression: 0.9649
    Random Forest: 0.9737
    XGBoost: 0.9737
```


