# Estimation of Obesity Levels Using SAS Studio

**Statistical analysis of eating habits, physical activity, and factors associated with obesity**

**Tools:** SAS Studio · ANOVA · Moderation Analysis · One-Sample t-Test · Binary Logistic Regression

## Project overview

This academic group project examines associations between eating habits, physical condition, demographic factors, and body mass index (BMI). Using a dataset of **2,111 observations**, the team conducted four statistical analyses in **SAS Studio** and interpreted the results.

> This repository includes the dataset and the original group report with SAS output screenshots. The SAS source programs are not available in this repository.

## Research questions and methods

| Research question | Statistical method |
| --- | --- |
| Does mean BMI differ by snacking frequency? | One-way ANOVA with Tukey–Kramer comparisons |
| Does gender moderate the association between physical activity and BMI? | Regression with gender × activity interaction terms |
| Is mean BMI different from the reference value of 24.9? | One-sample t-test |
| Which characteristics are associated with the likelihood of obesity? | Binary logistic regression |

## Selected findings

- **Snacking frequency and BMI:** ANOVA found differences in mean BMI across snacking categories (**F = 159.99, p < 0.0001**; reported R² ≈ 0.186). The report notes that the 'sometimes' group had the highest mean BMI (≈ 31.19) and the 'frequently' group the lowest (≈ 20.90).
- **Gender and physical activity:** The fitted interaction model was significant overall (**p < 0.0001**), with reported gender × activity interaction p-values of **0.0331** and **0.0089**. The model's explanatory power was limited (adjusted R² ≈ 0.030).
- **Mean BMI comparison:** The sample mean BMI was approximately **29.70**, significantly different from the project's reference BMI of **24.9** (**p < 0.0001**).
- **Obesity classification model:** The report identified age, weight, alcohol consumption, family history, and high-calorie food consumption as statistically significant factors in the fitted logistic model. It reported a **c-statistic of 0.973** (a measure of discrimination, **not** classification accuracy).

These are associations within the analyzed dataset, not evidence of causal effects or independently validated predictive performance.

## Repository contents

```text
Obesity-Level-Analysis-Using-SAS/
├── README.md
├── data/
│   └── ObesityDataSet_raw_and_data_sinthetic_v1_updated.xlsx
└── reports/
    └── Estimation of Obesity Levels Based on Eating Habits and Physical Condition- Group A.pdf
```

## Explore the work

1. Open the [full analysis report](reports/Estimation%20of%20Obesity%20Levels%20Based%20on%20Eating%20Habits%20and%20Physical%20Condition-%20Group%20A.pdf) for research questions, SAS output screenshots, and interpretations.
2. Download the [Excel dataset](data/ObesityDataSet_raw_and_data_sinthetic_v1_updated.xlsx) to inspect the observations and variables.

## Team and attribution

This was a **group project** for **OMIS 645 – Applied Business Analytics Using SAS**, Department of Operations Management & Information Systems.

**Team members:** Rochna Trivedi, Tanvi Agarwal, Adhwaith S, and Akshata Pai.

The analysis and report are credited to the group; individual contributions are not specified in the provided report.

## Limitations

- The repository does not contain the original SAS code, so the analysis cannot be reproduced directly from scripts here.
- Findings are based on the dataset and analyses documented in the group report; no independent model validation is supplied.
- The 24.9 BMI value is the **reference used in the project report**; it should not be interpreted as a universal population mean.
