# Loan Approval Prediction using Machine Learning

## 📌 Project Overview

This project builds a machine learning model that predicts whether a loan application will be approved based on applicant financial and demographic data.

Key challenges addressed:
- Class imbalance (significantly more approvals than rejections)
- Real-world financial data preprocessing
- ML pipeline with proper evaluation

---

## 🧪 Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib / seaborn (for visualization)

---

## 🔥 Problem Statement

Financial institutions need automated models to assess loan applications more efficiently. This project creates a supervised ML model to classify loan approvals based on applicant information like income, credit history, dependents, loan amount, etc.

---

## 🔄 ML Pipeline

1️⃣ Data Cleaning and Preparation  
2️⃣ Feature Scaling using **StandardScaler**  
3️⃣ Class Imbalance Handling using **SMOTE (Synthetic Minority Oversampling Technique)**  
4️⃣ Model Training using **Support Vector Machine (SVM)**  
5️⃣ Evaluation using **Confusion Matrix, Classification Report, Accuracy Score**

---

## 📊 Model Performance

- **Test Accuracy:** 83%
- **High Recall on minority class (loan rejections) after applying SMOTE**
- Evaluated using:
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## 🚀 Files in this Repository

| File | Description |
| ---- | ----------- |
| `notebook/loan_prediction_model.ipynb` | Full Jupyter Notebook with code |
| `data/loan_dataset.csv` | Raw dataset |
| `models/final_model.pkl` | (Optional) Saved trained model |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

---

## ⚙ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/loan-prediction-ml-project.git
cd loan-prediction-ml-project
pip install -r requirements.txt
