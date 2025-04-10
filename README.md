Insurance Cost Prediction using Linear Regression
Project Overview
This project analyzes how various demographic and lifestyle factors impact insurance charges using multiple linear regression. The analysis explores the relationship between insurance costs and predictors such as age, BMI, number of children, smoking status, and region of residence.
Dataset
The dataset contains 7 columns:

Age (years)
Gender (sex)
BMI (body mass index)
Children (number of dependents)
Smoker (yes/no)
Region (northeast, northwest, southeast, southwest)
Charges (insurance costs in USD)

Methodology

Data Cleaning & Preparation:

Checking for missing values
Converting categorical variables to numerical format
Analyzing descriptive statistics


Exploratory Data Analysis:

Univariate and bivariate visualization
Correlation analysis


Model Development:

Initial model with all variables
Feature selection using backward elimination
Reduced model with significant predictors


Model Evaluation:

Adjusted R² comparison
Residual analysis
Interpretation of coefficients



Key Findings

The reduced model (including age, BMI, smoker status, and region) achieved an adjusted R² of 0.8643
Smoking status had the largest impact on insurance charges
Gender and number of children were found to be statistically insignificant predictors

Recommendations

Implement targeted premium pricing based on risk factors
Develop health and wellness programs to reduce claims
Consider geographic variations in pricing models
