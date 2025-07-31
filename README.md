# DS_TASK3 - Machine Learning Project: Breast Cancer Detection

This project focuses on building a classification model to detect **breast cancer** using the **Wisconsin Breast Cancer Dataset**. The model is trained using different classification algorithms with a focus on evaluating model performance using accuracy, confusion matrix, and other metrics.

---

## 📁 Files

- `DS3.ipynb` – Jupyter Notebook containing the complete workflow from data preprocessing to model training and evaluation.

---

## 🔍 Project Overview

- **Dataset**: Breast Cancer Wisconsin dataset (available via `sklearn.datasets`)
- **Target**: Classify tumors as **Malignant (M)** or **Benign (B)**.
- **Features**: Includes measurements such as radius, texture, perimeter, area, smoothness, etc.

---

## ⚙️ Workflow

1. **Data Loading & Preprocessing**
   - Loading dataset from `sklearn.datasets`
   - Checking for null values
   - Label encoding target variables

2. **Exploratory Data Analysis**
   - Checking data distribution and correlation
   - Visualizing class imbalance

3. **Train-Test Split**
   - Splitting the data into training and testing sets

4. **Model Building**
   - Logistic Regression
   - Random Forest
   - Decision Tree

5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 📦 Requirements

Install the dependencies before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
