# Eda-Feature-LifestyleDataset
1) Project Overview

This project explores the relationship between lifestyle habits and health indicators using a dataset of 5,000 individuals. The goal is to understand patterns in human behavior related to exercise, sleep, nutrition, and physical attributes such as BMI — through data analysis and feature engineering only.

This project focuses on EDA, insights, and engineered wellness metrics — a strong fundamental step before machine learning.

2) Objectives

Clean and structure the dataset

Perform Exploratory Data Analysis (EDA)

Visualize key lifestyle + health patterns

Engineer new meaningful health-related features

Interpret trends and derive insights

Build foundation for future ML extension

3) Tools & Libraries
Category	Tools Used
Language	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn
IDE	Jupyter Notebook / VS Code

4) Steps Performed
 
 a) Data Loading & Cleaning

Imported dataset

Standardized column names

Converted categorical columns

Checked missing values & duplicates
(none found)

5) Exploratory Data Analysis (EDA)

Univariate Analysis

Distribution of age, height, weight, exercise, sleep, sugar intake, BMI

Count plots for smoking, alcohol, marital status, profession

Key Observations

Balanced age distribution

Majority sleep 6–8 hours

BMI slightly right-skewed (normal to overweight majority)

Most people moderate exercisers and moderate sugar consumers

Higher count of non-smokers and non-alcohol consumers

Bivariate Analysis

Correlation heatmap among numeric features

Observed expected patterns:

BMI  Weight: strong positive correlation

Exercise  BMI: slight negative pattern

Sugar BMI: weak trend

Sleep independent — varies across lifestyles

6) Feature Engineering

Created meaningful wellness metrics:


These engineered features help quantify lifestyle quality and can later feed into ML models.

📊 Insights

Most individuals fall into normal or slightly overweight BMI ranges

Majority maintain moderate lifestyle habits

Sleep, exercise & sugar intake patterns vary across demographic groups

Engineered features reveal behavioral health signals

This analysis builds a base to later perform segmentation or health risk prediction.

🚀 Future Improvements

Add real-world survey data / wearable data

Build clustering model to segment lifestyle groups

Develop supervised model to predict health risk

Deploy as health lifestyle analysis dashboard

Add SHAP/Explainability after ML phase

💡 Key Learning Outcomes

Real-world EDA & data cleanup

Feature engineering mindset

Interpreting patterns & trends

Building foundation before ML

Understanding of lifestyle-health relationships

“Focusing on strong fundamentals & mastering the base first.
