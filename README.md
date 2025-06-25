# AI-and-ML-Internship-Task-2

# Titanic Dataset – ML Data Cleaning and Exploratory Data Analysis

This project focuses on cleaning and exploring the Titanic dataset to prepare it for machine learning tasks. It includes exploratory data analysis (EDA) with visualizations and statistical summaries.

# Dataset
- Dataset used: `Titanic-Dataset.csv`

# Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Plotly (for interactive visualizations)

# Task 2: Exploratory Data Analysis (EDA)

# 1. Generate Summary Statistics
We used `.describe()` to generate key statistics like mean, median, standard deviation, and quartiles. This gave a high-level view of each feature’s distribution.

# 2. Create Histograms and Boxplots for Numeric Features
Histograms were used to visualize distributions of features like `Age`, `Fare`, `SibSp`, and `Parch`. Boxplots identified skewness and outliers, particularly in the `Fare` column which was highly right-skewed.

# 3. Use Correlation Matrix and Pairplot to Understand Feature Relationships
We generated a correlation heatmap for numeric columns, which showed how strongly each feature correlated with others, especially `Survived`. A pairplot further illustrated relationships and clustering between `Age`, `Fare`, and `Pclass` with respect to survival.

# 4. Identify Patterns, Trends, or Anomalies
We explored feature-wise survival patterns:
- Countplots showed overall survival distribution.
- We saw clear differences in survival across **Pclass** and **Sex**.
- Women and first-class passengers had higher survival rates.

# 5. Make Feature-Level Inferences from Visuals
Using Plotly, we created an interactive scatter plot of `Age` vs `Fare`, colored by survival status. It visually revealed that passengers paying higher fares and younger individuals had better chances of survival.

# Final Outputs
- Cleaned and scaled Titanic dataset ready for ML model building.
- Visualizations highlighting feature importance and trends.
- Informed insights on passenger survival based on class, age, and gender.
