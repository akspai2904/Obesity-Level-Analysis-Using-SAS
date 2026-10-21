# Obesity Level Analysis Using SAS Studio

## Project Overview

This project investigates the relationship between eating habits, physical activity, demographic characteristics, and obesity levels using SAS Studio.

The analysis uses a dataset of **2,111 observations** and applies statistical techniques to examine factors associated with Body Mass Index (BMI) and obesity classification.

## Tools & Technologies

- SAS Studio
- Microsoft Excel
- Statistical Hypothesis Testing
- Regression Analysis
- Data Visualization

## Research Objectives

1. Determine whether average BMI differs significantly across snacking habits.
2. Examine whether gender moderates the relationship between physical activity and BMI.
3. Test whether the sample mean BMI differs significantly from a reference BMI of 24.9.
4. Identify factors associated with the likelihood of obesity.

## Statistical Analysis & Key Findings

### 1. Analysis of Variance (ANOVA)

**Objective:** Determine whether average BMI differs across snacking habits.

**Results:**
- F-statistic: 159.99
- p-value: < 0.0001
- R²: 0.1855

**Finding:** Average BMI differed significantly across snacking categories. Participants who reported snacking sometimes had the highest average BMI (31.19), while frequent snackers had the lowest (20.90).

### 2. Moderation Analysis

**Objective:** Examine whether gender moderates the relationship between physical activity and BMI.

**Results:**
- Adjusted R²: 0.0299
- Overall model p-value: < 0.0001
- Significant gender-by-physical-activity interaction terms

**Finding:** The association between physical activity and BMI differed by gender in the fitted model.

### 3. One-Sample T-Test

**Objective:** Compare the sample mean BMI with a reference value of 24.9.

**Results:**
- Sample size: 2,111
- Mean BMI: Approximately 29.70
- p-value: < 0.0001

**Finding:** The sample mean BMI was significantly higher than the reference value.

### 4. Binary Logistic Regression

**Objective:** Investigate factors associated with obesity classification.

**Predictors examined:**
- Age
- Weight
- Alcohol consumption
- Family history of obesity
- High-calorie food consumption

**Finding:** All five predictors were statistically significant in the fitted model. The reported concordance statistic (c) was 0.973, indicating strong discrimination within the analyzed dataset.

## Project Files

- **Dataset:** [View Excel Dataset](data/ObesityDataSet_raw_and_data_sinthetic_v1_updated.xlsx)
- **SAS Analysis Report:** [View Complete Analysis Report](reports/Estimation%20of%20Obesity%20Levels%20Based%20on%20Eating%20Habits%20and%20Physical%20Condition-%20Group%20A.pdf)

The PDF report contains SAS Studio output screenshots, statistical results, diagnostic plots, and detailed interpretations.

**Note:** The original SAS source code is not included in this repository.

## Project Contributors

This project was completed as part of OMIS 645 – Applied Business Analytics Using SAS.

**Team Members:**
- Rochna Trivedi
- Tanvi Agarwal
- Adhwaith S
- Akshata Pai

## Conclusion

This project demonstrates the application of statistical techniques using SAS Studio to investigate obesity-related patterns and evaluate relationships between lifestyle factors and BMI.

The findings highlight the value of statistical modeling and hypothesis testing in extracting insights from structured datasets.
