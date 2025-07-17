# 📊 Banking Term Deposit Subscription Prediction (Mini Project)

This project focuses on building a Machine Learning model to predict whether a customer will subscribe to a term deposit product offered by a bank. The data is derived from a real-world marketing campaign dataset.

## 🧠 Project Objective

The goal is to:
- Analyze customer data and campaign interactions.
- Apply classification techniques to predict subscription behavior.
- Help banks improve targeting strategies for future campaigns.

## 📁 Dataset Overview

The dataset contains client information, previous campaign contact details, and outcomes. Key features include:

- `age`, `job`, `marital`, `education`, `balance`, etc.
- `contact`, `day`, `month`, `poutcome`
- Target variable: `y` (whether the client subscribed: `yes`/`no`)

## 🔧 Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn** (for visualization)
- **Scikit-learn** (model building and evaluation)
- **Jupyter Notebook**

## ⚙️ ML Techniques Used

- Label Encoding
- Train-Test Split
- Logistic Regression
- Accuracy, Confusion Matrix, Classification Report

## 🏁 Project Workflow

1. Data Import and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Data Cleaning & Encoding
4. Model Training using Logistic Regression
5. Model Evaluation & Interpretation

## ✅ Results

- Final Accuracy: ~89.3%
- Precision, Recall, and F1-Score evaluated for both classes

## 📦 Files Included

- `banking term deposit mini project-main.ipynb` – Complete code
- `best_model.pkl` *(optional)* – Trained model file (if uploaded)
- `dataset.csv` *(optional)* – Input dataset (if uploaded)

## 📘 How to Run

1. Clone the repo or download it as ZIP.
2. Install dependencies using `requirements.txt`.
3. Run the notebook in Jupyter or any compatible environment.

```bash
pip install -r requirements.txt
