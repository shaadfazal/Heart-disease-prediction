# ❤️ Heart Disease Detection Project

## 📘 Overview

This project builds a machine learning model to **predict the presence of heart disease** in patients using clinical and demographic data. The implementation is provided in the Jupyter Notebook `heart_disease.ipynb` and demonstrates the end-to-end ML pipeline from preprocessing to evaluation.

---

## 🎯 Objective

To develop a predictive system that determines whether a patient is likely to have heart disease based on historical patient data and diagnostic indicators.

---

## 📂 Dataset

The dataset includes anonymized medical records of patients, with a binary target indicating the presence (`1`) or absence (`0`) of heart disease. Each record captures vitals, test results, and clinical observations.

> Note: You’ll need to place the dataset CSV in the same directory as the notebook if it’s not already embedded.

---

## ⚙️ Technical Workflow

The notebook implements the following steps:

### 🔄 Data Preprocessing

- Handles missing values where necessary
- Applies **Label Encoding** or **One-Hot Encoding** to convert categorical features into numerical format for modeling

### 🧠 Modeling

- Uses a **Random Forest Classifier** to learn patterns from the training data
- Employs a **Train/Test Split** to assess model performance on unseen data

### 📊 Evaluation

Model performance is measured using:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (includes Precision, Recall, and F1-score)

---

## 🛠️ Requirements

Install the following Python packages:

```bash
pip install pandas scikit-learn matplotlib seaborn
