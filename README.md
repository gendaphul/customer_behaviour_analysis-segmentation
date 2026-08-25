# Customer Behaviour Analysis & Prediction

<p align="center">
  <img src="assets/customer-behaviour-banner.png" width="900">
</p>

<p align="center"><b>Data Analysis • Machine Learning • Customer Segmentation</b></p>

---

## 📌 Project Overview

An end-to-end customer analytics and machine-learning project covering **data cleaning, exploratory data analysis, feature engineering, PCA, classification, regression and customer segmentation**.

The analysis is organized into six focused Jupyter notebooks for easier understanding, execution and presentation.

## 🎯 Objectives

- Understand customer behaviour and purchasing patterns
- Prepare and transform raw customer data
- Predict marketing campaign offer acceptance
- Estimate average customer product spending
- Segment customers into behavioural groups using K-Means

## 🔄 Project Workflow

<p align="center">
  <img src="assets/project-workflow.png" width="900">
</p>

## 🧠 Machine Learning Tasks

<p align="center">
  <img src="assets/ml-tasks.png" width="900">
</p>

| Task | Approach | Objective |
|---|---|---|
| 🎯 Classification | SVC / Random Forest | Predict offer acceptance |
| 📈 Regression | SVR | Predict average spending |
| 👥 Clustering | K-Means | Identify customer segments |
| 📉 Dimensionality Reduction | PCA | Reduce feature dimensions |

## 🗂️ Project Structure

```text
Customer-Behaviour-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
├── data/
├── notebooks/
│   ├── 01_data_collection_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_feature_engineering_pca.ipynb
│   ├── 04_classification_modeling.ipynb
│   ├── 05_regression_modeling.ipynb
│   └── 06_customer_segmentation.ipynb
└── outputs/
```

## 📓 Notebook Guide

### 01 — Data Collection & Cleaning
Imports and inspects the customer dataset, handles missing values, creates derived variables such as `Age`, `AgeGroup`, `FirstVisit` and `OfferAccepted`, and saves cleaned data.

### 02 — Exploratory Data Analysis
Explores customer distributions, income across demographic groups, purchasing patterns, income vs spending, and purchasing channels.

### 03 — Feature Engineering & PCA
Encodes categorical variables, creates the modelling dataframe, performs Pearson correlation analysis and PCA, and visualizes PCA component loadings.

### 04 — Classification Modelling
Predicts whether a customer will accept a marketing campaign offer using Polynomial-kernel SVC and Random Forest, with hyperparameter experiments and classification evaluation.

### 05 — Regression Modelling
Predicts average product spending using an RBF-kernel Support Vector Regressor (SVR) and evaluates it using R².

### 06 — Customer Segmentation
Standardizes features, uses the Elbow Method to inspect cluster count, fits K-Means with six clusters as used in the analysis, and profiles customer segments.

## 👥 Customer Segmentation Concept

<p align="center">
  <img src="assets/customer-segmentation-concept.png" width="750">
</p>

> This is a **conceptual illustration**, not a measured result. Replace it with the actual K-Means plot from Notebook 06 when presenting final results.

## 🛠️ Technologies

Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn • Jupyter Notebook

## 🚀 Installation

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks in order:

```text
01 → 02 → 03 → 04
             ↘ 05
             ↘ 06
```

## 📊 Key Concepts

- Data cleaning
- Feature engineering
- Categorical encoding
- EDA
- Correlation analysis
- PCA
- Train/test splitting
- Hyperparameter experimentation
- SVM classification
- Random Forest classification
- SVR regression
- R² evaluation
- Feature standardization
- K-Means clustering
- Elbow Method
- Customer profiling

## ⚠️ Limitations

The notebooks preserve the methodology and modelling choices of the original analysis. Further improvement could include cross-validation, systematic hyperparameter search, stronger preprocessing pipelines, class-imbalance analysis and additional evaluation metrics.

## 👤 Author

**Kapil Gunde**



