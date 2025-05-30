

# UTI Risk Factors Among Pregnant Women – A Data-Driven Analysis

##  Project Overview

This project explores the relationship between urinary tract infections (UTIs), symptoms, and pregnancy-related factors among a sample of pregnant women. The analysis uses real-world survey data and applies a full data science pipeline — from data cleaning and exploration to visual storytelling and predictive modeling.

The goal is to uncover hidden patterns in UTI occurrence during pregnancy, evaluate symptom prevalence, and eventually build a model to predict UTI risk.

---

##  Data Cleaning Summary

- Handled missing values logically using skip-logic (e.g., "Why didn't you take medicine?")
- Standardized categorical values (e.g., `"Positive for  UTI"` → `"Positive"`)
- Encoded binary variables like `"Yes"`/`"No"` into 1/0
- Removed irrelevant columns like respondent `CODE`
- Ensured all variables were typed correctly (`category`, `int`, etc.)

---

## Exploratory Data Analysis (EDA)

###  Univariate Insights
- Age, trimester, and education distributions
- Prevalence of symptoms like dysuria, frequent urination, and chills
- UTI testing and result breakdown

###  Bivariate Analysis
- UTI result vs. symptoms (e.g., dysuria, chills)
- UTI result vs. trimester, education, and antibiotic use
- Heatmaps showing symptom correlations

###  Multivariate Analysis
- Interaction of UTI result with both symptoms and demographic factors
- Pairplots for numeric/binary predictors
- Trimester vs UTI vs antibiotic use (facet grids)

---

