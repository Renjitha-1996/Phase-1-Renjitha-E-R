# Project: Nykaa Top Brands Cosmetics Product Reviews

# Overview

This project involves analyzing a dataset of cosmetics product reviews from Nykaa. The key objectives include data cleaning, exploratory data analysis (EDA), feature engineering, and feature selection to build a foundation for predictive modeling or further analysis.

# Steps Performed

# 1. Data Collection

The dataset was imported and examined for its structure and basic properties.

# 2. Data Preprocessing

*. Handling Missing Values
   Missing values were addressed using imputation techniques based on data distribution.

*. Outlier Removal
   Outliers in numerical features were detected using the IQR method and removed to improve data quality.

*. Addressing Skewness
   Log transformation was applied to reduce skewness in highly skewed numerical features.

# 3. Exploratory Data Analysis (EDA)

# Insights Gained:

*. Distributions: Visualized with histograms and KDE plots to understand feature distributions.

*. Relationships: Pair plots and correlation heatmaps identified feature relationships and potential redundancies.

*. Visualizations Used:
   1. Pie Diagrams
   2. Bar Plots
   3. Count Plots
   4. Line Plots
   5. Histograms
   6. Box Plot
   7. Pair Plot

# 4. Feature Engineering

Encoding Categorical Features:

*. One-Hot Encoding was applied to low-cardinality categorical features.
*. Frequency Encoding handled high-cardinality features to reduce memory consumption.

# 5. Feature Selection

Techniques Applied:

*. Univariate Feature Selection: SelectKBest identified the top features based on ANOVA F-values.

*. Random Forest Importance: Assessed feature relevance using tree-based methods.

*. Correlation Analysis: Removed highly correlated features (≥ 0.9 correlation threshold) to avoid redundancy.
