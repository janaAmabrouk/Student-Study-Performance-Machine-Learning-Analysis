🎓 Student Success Analysis: Predictive Modeling & EDA
This project explores the socio-economic factors influencing student performance. Using a dataset of 1,000 students, we applied Machine Learning and Statistical Visualization to identify the strongest predictors of success in Math, Reading, and Writing.
📂 Repository Structure
code
Text
├── data/                   # Raw Dataset (study_performance.csv)
├── notebooks/              # Jupyter Notebook with full implementation
├── reports/                # Final PDF Machine Learning Report
└── README.md               # Project documentation
🔍 Analysis Breakdown & Techniques
Q1: Ethnicity and Achievement
Technique: Mean Aggregation (groupby) & Multi-color Bar Plotting.
Insight: Ethnicity acts as a "performance floor." Group E emerged as the top-performing demographic, suggesting that localized community support or cultural academic emphasis provides a consistent edge.
Q2: Test Prep Effectiveness
Technique: Boolean Filtering & Mean Difference Analysis.
Insight: Test preparation is a high-ROI intervention. The analysis proves writing is the most "trainable" skill, showing nearly a 10-point boost upon course completion compared to lower gains in math.
Q3: Gender Performance Gap
Technique: Categorical Cross-Analysis.
Insight: Divergent cognitive strengths are evident; males lead in quantitative reasoning (Math), while females significantly dominate in literacy and communication tasks (Reading/Writing).
Q4: Lunch Type & Socio-Economic Impact
Technique: Linear Regression Modeling & map() Numerical Encoding.
Insight: Nutrition is a primary "score stabilizer." Using regression, we quantified that a standard lunch correlates with a +11.5 point increase in Math, proving that economic stability reduces performance volatility.
Q5: Subject Correlations
Technique: Pearson Correlation Matrix & Heatmap Visualization.
Insight: Reading and Writing are functionally the same skillset (0.95 correlation). This suggests that a single literacy-focused intervention will simultaneously improve performance in both subjects.
Q6: Parental Education Impact
Technique: Categorical Factorization (pd.factorize) & Predictive Modeling.
Insight: Academic success is generational. Our model confirms that parental degree attainment provides a reliable "forecast" for a student's baseline scores, highlighting the influence of the home-learning environment.
Q7: Global Distribution Analysis
Technique: Descriptive Statistics (describe) & Boxplot Outlier Detection.
Insight: While average scores are healthy, boxplot analysis reveals significant "low-end outliers" in specific demographics, identifying exactly which student groups are most at risk of falling behind.
🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.
Methodology: Descriptive Analytics, Linear Regression, Data Preprocessing.
