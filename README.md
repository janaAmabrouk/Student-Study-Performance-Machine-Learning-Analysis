# Student Study Performance - Exploratory Data Analysis & Predictive Modeling

This repository contains a comprehensive data analysis project that explores the socio-economic and demographic factors affecting student academic performance. Using **Python**, **Seaborn**, and **Scikit-Learn**, we performed descriptive analytics and built predictive models to understand score determinants in Math, Reading, and Writing.

---

## 📌 Project Highlights
- **Exploratory Data Analysis (EDA):** Visualized distributions using Boxplots and Bar charts to identify performance trends across genders, ethnicities, and lunch programs.
- **Statistical Analysis:** Calculated Pearson correlation coefficients, revealing a **0.95 correlation** between Reading and Writing scores.
- **Predictive Modeling:** Implemented **Linear Regression** to quantify the impact of variables like lunch type and parental education on final scores.

## 📊 Key Insights & Findings

### 1. The Impact of Nutrition (Lunch)
By mapping lunch types to numerical values (`standard: 1`, `free/reduced: 0`), our Linear Regression models showed that having a standard lunch has a high positive coefficient on scores:
- **Math Score Impact:** +11.55 points
- **Reading Score Impact:** +7.20 points
- **Writing Score Impact:** +8.26 points

### 2. Test Preparation Effectiveness
Students who completed the preparation course outperformed those who didn't across all categories:
- **Math:** +5.62 points avg. improvement
- **Reading:** +7.36 points avg. improvement
- **Writing:** +9.91 points avg. improvement

### 3. Subject Correlations
Performance is highly interconnected. The heatmap analysis shows:
- **Reading vs. Writing:** 0.95 (Very Strong)
- **Math vs. Reading:** 0.82 (Strong)
- **Math vs. Writing:** 0.80 (Strong)

### 4. Gender Performance Gap
- **Males** performed better on average in **Math** (~68.7 vs ~63.6).
- **Females** significantly outperformed males in **Reading** (~72.6 vs ~65.5) and **Writing** (~72.5 vs ~63.3).

## 🛠️ Technical Stack
- **Data Handling:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`
    - `LinearRegression` for predictive modeling.
    - `train_test_split` for model validation.
    - `pd.factorize` for categorical encoding.

## 📂 Repository Structure
```text
├── study_performance.csv       # Raw Dataset
├── Student_Analysis.ipynb      # Jupyter Notebook with full code & outputs
├── Machine_Learning_Report.pdf  # Formal Documentation
└── README.md                   # Project Summary
