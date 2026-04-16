<div align="center">

# 🚀 Elite Data Science Portfolio

**Advanced Analytics & Machine Learning Models**  
*CodeAlpha Data Science Internship Program*

<br>

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/)

**Developed by: Piyush Ramteke**

---

</div>

<br>

## 📋 Executive Summary
This repository contains a curated collection of **three end-to-end, interview-ready Data Science projects**. Each project is meticulously documented, following industry-standard workflows from Data Engineering & Preprocessing, through Exploratory Data Analysis (EDA), straight to Machine Learning Pipeline Deployment.


<br>

---

<br>

## 📂 I. The Project Architecture

```graphql
Data_Science_Projects/
│
├── 1_Unemployment_Analysis/
│   ├── Unemployment_Analysis.ipynb    ← 📊 Trend Modeling & Geographical EDA
│   ├── Unemployment in India.csv      ← 💾 Primary CMIE Raw Dataset
│   └── Unemployment_Rate_upto_11...   ← 💾 Supplementary Geography Data
│
├── 2_Sales_Prediction/
│   ├── Sales_Prediction.ipynb         ← 📈 ROAS ML Modeling & Regression
│   └── Advertising.csv                ← 💾 Multi-channel Spend Dataset
│
└── 3_Car_Price_Prediction/
    ├── Car_Price_Prediction.ipynb     ← 🚗 Advanced ML Appraisal Pipeline
    └── car data.csv                   ← 💾 Vehicle Traits & Pricing Dataset
```

<br>

---

<br>

## 📊 II. Portfolio Breakdown

### <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/chart-line.svg" width="20" height="20"> Project 1: Macro-Economic Unemployment Tracking
A deep dive into the structural shifts in the Indian Labor Market from 2019 to 2020, focusing on the sheer statistical shock introduced by the COVID-19 pandemic.
* **Core Focus:** Granular EDA, Heatmaps, Temporal Trend lines.
* **Key Finding:** A catastrophic jump from `~8%` to `25%+` national unemployment in April 2020.
* **Tech Stack:** `Pandas`, `Matplotlib`, `Seaborn`.

> **[View the Notebook →](1_Unemployment_Analysis/Unemployment_Analysis.ipynb)**

### <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/sack-dollar.svg" width="20" height="20"> Project 2: Advertising ROI & Sales Prediction
A regression engine formulated to identify which marketing channels (TV, Radio, Newspaper) possess the highest elasticity on final product sales.
* **Core Focus:** Linear vs Ensemble Tree comparisons, Pearson Mathematics.
* **Best Algorithm:** Random Forest Regressor hitting `~98%` R² Accuracy.
* **Key Finding:** TV Advertising commands an overwhelming `90%` statistical correlation to sales yields.
* **Tech Stack:** `Scikit-learn`, `Sklearn-Metrics`, `Pandas`.

> **[View the Notebook →](2_Sales_Prediction/Sales_Prediction.ipynb)**

### <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/car.svg" width="20" height="20"> Project 3: Used-Car Valuation Matrix
Constructing a digital appraisal tool capable of estimating second-hand vehicle pricing through robust feature engineering (Car Age, Transmissions, Depreciation).
* **Core Focus:** Advanced Pipeline, Categorical Deep-Encoding, Hyper-param evaluation.
* **Best Algorithm:** Random Forest achieving `R² > 95%`.
* **Key Finding:** The manufacturer's standard Present Value inherently decides `~80%` of resale potential limiters.
* **Tech Stack:** `Scikit-learn`, `LabelEncoder`, `NumPy`.

> **[View the Notebook →](3_Car_Price_Prediction/Car_Price_Prediction.ipynb)**

<br>

---

<br>

## 💻 III. Quick Start & Execution

If you wish to clone this environment and stress-test the algorithms locally:

```bash
# 1. Clone the master repository
git clone https://github.com/Piyu242005/CodeAlpha-Data-Science-Projects.git

# 2. Shift to the local directory
cd CodeAlpha-Data-Science-Projects

# 3. Ensure your local environment is equipped
pip install -r requirements.txt

# 4. Spool up the local analytics server
jupyter notebook
```

### 📦 Prerequisites Include:
* `pandas` >= 1.3.0
* `numpy` >= 1.21.0
* `matplotlib` >= 3.4.0
* `seaborn` >= 0.11.0
* `scikit-learn` >= 0.24.0

<br>

---

<br>

<div align="center">
  <b>Designed & Authored by Piyush Ramteke</b><br>
  <i>Empowering Intelligence via Data</i>
</div>
