# Customer Conversion Predictor Model

An end-to-end machine learning pipeline built to predict whether an e-commerce website visitor will complete a purchase. This repository serves as the final capstone submission for the **Summer Analytics 2026** week 2 mini-hackathon challenge.

---

## 📌 Project Overview
This challenge focuses on predictive modeling using structured tabular data. Participants are expected to analyze the dataset, perform appropriate preprocessing, engineer meaningful features, and build machine learning models to predict customer conversion outcomes.

## 🛠️ Technical Workflow & Methodology

The pipeline follows a data science workflow to ensure optimal model stability and interpretability:

* **Data Preprocessing & Cleaning:**  Addressed missing data points across features using **Median Value Imputation** to preserve data distribution without introducing bias.
   Normalized and scaled numerical features via **Standard Scaling** ($Z$-score normalization) to bring all continuous variables to a common scale.
* **Feature Engineering:**  Extracted valuable predictive signals from categorical traffic resources and device behavioral insights using **One-Hot Encoding**.
* **Predictive Modeling:**  Implemented and validated a **Logistic Regression** classifier. This algorithm serves as an ideal baseline for conversion prediction due to its strong performance on linearly separable behavioral data and high interpretability of feature coefficients.

---

📊 Core Dependencies
The project relies on the standard Python data science ecosystem:

**pandas** - Data manipulation and structural analysis.
<br>
**numpy** - Numerical computing.
<br>
**scikit-learn** - Data preprocessing, scaling, and Logistic Regression modeling.
<br>
**Jupyter notebook** - Interactive development environment

**Developed as part of the Summer Analytics 2026.**
