# Student Study Performance - Machine Learning Analysis

This repository contains a descriptive and predictive analysis of student academic performance based on various demographic and socio-economic factors.

---

## 📌 Project Overview
The goal of this project is to understand how variables such as gender, ethnicity, parental education, and preparation courses influence student scores in **Math, Reading, and Writing**. We utilized data visualization, statistical analysis, and linear regression to uncover patterns and predict outcomes.

## 📊 Dataset Description
The dataset consists of **1001 rows and 8 columns**, including:
- **Categorical:** Gender, Race/Ethnicity, Parental Level of Education, Lunch Type, Test Preparation Course.
- **Numerical:** Math Score, Reading Score, Writing Score.

## 🔍 Key Research Questions & Findings

1.  **Ethnicity and Achievement:** Does ethnic background impact performance? 
    *   *Result:* Group E consistently showed the highest average scores (~72), while Group A showed the lowest (~63).
2.  **Test Prep Effectiveness:** Does a preparation course help?
    *   *Result:* Students who completed the course scored significantly higher (approx. +5.6 in Math, +7.3 in Reading, and +9.9 in Writing).
3.  **Gender Gap:** Are there subject-specific gender differences?
    *   *Result:* Males performed better in Math, while females outperformed males in Reading and Writing.
4.  **Impact of Lunch Type:** Does nutrition/socio-economic status correlate with scores?
    *   *Result:* Students with "Standard" lunch performed significantly better and more consistently than those on "Free/Reduced" lunch programs.
5.  **Subject Correlations:** Is performance in one subject a predictor for others?
    *   *Result:* There is a very strong positive correlation (0.95) between Reading and Writing scores.
6.  **Parental Education Impact:** Does a parent's degree level predict student success?
    *   *Result:* Predictive modeling indicates that higher parental education levels generally correlate with higher student scores.

## 🛠️ Tech Stack & Methodology
- **Language:** Python
- **Libraries:** `Pandas`, `Seaborn`, `Matplotlib`, `Scikit-learn`

### Machine Learning Approach
- **Descriptive Analytics:** Used summary statistics and boxplots to visualize distributions and identify outliers.
- **Predictive Analytics:** Implemented **Linear Regression** models to predict scores based on Lunch type and Parental Education levels.

## 📂 Repository Structure
```text
├── data/                   # Dataset (csv)
├── notebooks/              # Jupyter Notebook with full analysis code
├── reports/                # Final PDF Report
└── README.md               # Project documentation
