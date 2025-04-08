# employee-attrition-salary-performance-analysis
Statistical modeling and data analysis project investigating the interplay between employee attrition, salaries, and performance ratings using R. Includes multiple linear regression, logistic regression, and OLS modeling based on Kaggle HR dataset.



# Data-Driven Insights into Employee Attrition, Salaries, and Performance Ratings

## 📊 Project Overview

This repository contains a comprehensive data analysis project focused on employee attrition, salary structure, and performance ratings. The study leverages statistical methods such as **multiple linear regression**, **logistic regression**, and **ordinary least squares regression** to uncover critical factors influencing organizational workforce trends.

- **Course**: INFO B-518 – Applied Statistical Methods for Biomedical Informatics  
- **Instructor**: Dr. Zeyana Hamid  
- **Author**: Radhika Gedela  
- **Affiliation**: Department of Health Informatics, IUI  
- **Date**: December 14, 2023

---

## 📁 Repository Contents

| File/Folder                      | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `project_report.pdf`             | Full academic project report including methodology, results, and discussion|
| `employee_attrition.csv`         | Cleaned dataset used for analysis (original source from Kaggle)            |
| `eda_plots/`                     | Visualizations and plots generated during exploratory data analysis        |
| `regression_models.R`           | R script for multiple linear and logistic regression models                |
| `ols_model.R`                    | R script for the ordinary least squares regression model                   |
| `README.md`                      | Project overview, usage, and file explanations                             |

---

## 📈 Research Questions

1. **What factors influence employee salaries?**  
   → Using multiple linear regression on job role, level, department, etc.

2. **Can we predict employee attrition based on demographics and job variables?**  
   → Logistic regression using job level, percent salary hike, and job role.

3. **What impacts employee performance ratings?**  
   → OLS regression based on satisfaction variables.

---

## 🧪 Methodologies

- **Data cleaning** using R (`read.csv`, `str`, `summary`, `dim`)
- **Exploratory Data Analysis (EDA)** including histograms, normality tests, and correlation heatmaps
- **Statistical Testing**: Fisher’s Exact Test, ANOVA, t-tests
- **Modeling**:
  - Multiple Linear Regression (salary prediction)
  - Logistic Regression (attrition prediction)
  - Ordinary Least Squares (performance rating analysis)
- **Outlier treatment**: Winsorization

---

## 📚 Dataset

- Source: [Kaggle – Employee Attrition Dataset](https://www.kaggle.com/datasets/patelprashant/employee-attrition)
- Observations: 1470 rows × 28 columns
- Types: Categorical (Ordinal/Nominal), Continuous, and Discrete variables

---

## 🚧 Limitations

- Correlation does not imply causation
- Possible bias and confounding variables in the dataset
- Model underperformance for extreme data values
- Quasi-complete separation issues in OLS regression

---

## 📄 References

- Zhenjing et al. (2022), Alblihed & Alzghaibi (2022), Balushi et al. (2022), De Jong et al. (2019), Patel (2018)
- Vu & Harrington (2020) - Introductory statistics for the life and biomedical sciences
