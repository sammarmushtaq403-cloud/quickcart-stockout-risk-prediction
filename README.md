# 📦 QuickCart – Stockout Risk Prediction

A Data Science and Machine Learning project focused on predicting **product stockout risk** and identifying the key factors that influence inventory shortages.

## 🚀 Project Overview

QuickCart uses historical inventory, store, supplier, product, and event data to predict whether a product is at risk of going out of stock.

The goal is to transform raw inventory data into actionable insights that can support **better inventory planning and supply-chain management**.

## 📊 Dataset

The project combines 5 datasets:

- Stores
- SKUs / Products
- Suppliers
- Events
- Inventory

After data cleaning and integration:

- **50,000 records**
- **22 features**
- Missing values handled
- Duplicate records removed
- Supplier reliability standardized

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Data cleaning
- Missing-value treatment
- Duplicate removal
- Data type correction
- Dataset integration
- Supplier reliability standardization
- Feature engineering

## 🛠️ Feature Engineering

Important features created include:

- Days of Cover
- Reorder Gap
- Supplier Reliability
- Previous Stockout
- Demand Forecast
- Day of Week
- Weekend Flag
- Perishable Flag
- Festival-Relevant Flag

## 📈 Exploratory Data Analysis

EDA was performed to understand:

- Stockout distribution
- Product-level stockout patterns
- Store-level trends
- Supplier reliability
- Demand forecasts
- Perishable vs non-perishable products
- Festival-related demand
- Inventory coverage

## 🤖 Machine Learning Models

Two classification models were implemented:

1. Logistic Regression
2. Random Forest Classifier

The dataset was divided using an **80/20 train-test split**.

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Random Forest Results

| Metric | Score |
|---|---:|
| Accuracy | 87.6% |
| Precision | 84.2% |
| Recall | 80.1% |
| F1 Score | 82.1% |

## 🔍 Feature Importance

The analysis identified several important factors related to stockout risk, including:

- Days of Cover
- Reorder Gap
- Supplier Reliability
- Previous Stockout
- Demand Forecast

## 💡 Key Takeaway

This project demonstrates how **data preprocessing, exploratory analysis, feature engineering, and machine learning** can be combined to solve a practical inventory management problem.

> **Better data → Better features → Better predictions → Smarter inventory decisions.** 📦📈

## 🧰 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Project Structure

```text
QuickCart-Stockout-Prediction/
│
├── data/
│   ├── stores.csv
│   ├── skus.csv
│   ├── suppliers.csv
│   ├── events.csv
│   └── inventory.csv
│
├── notebooks/
│   └── stockout_prediction.ipynb
│
├── outputs/
│   ├── predictions.csv
│   ├── model_comparison.csv
│   └── feature_importance.csv
│
├── README.md
└── requirements.txt
