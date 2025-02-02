Overview

This repository contains Python scripts that run three separate linear regression models to analyze how different treatment groups influence public perception regarding immigration. Each model compares different groups to assess variations in attitudes.

Regression Models & Comparisons

The following regression models are included:

1️⃣ IV: Control Group vs. Treatment Group 1

DV: Economic Growth Model: Measures agreement with "Immigrants can contribute to Italy’s economic growth".

DV: National Duty Model: Measures agreement with "Assisting migrants is a national duty".

Script: regression_model.py

2️⃣ IV: Control Group vs. Treatment Group 2

DV: Economic Growth Model: Measures agreement with "Immigrants can contribute to Italy’s economic growth".

DV: National Duty Model: Measures agreement with "Assisting migrants is a national duty".

Script: regression_model_treatment2.py

3️⃣ IV: Treatment Group 1 vs. Treatment Group 2

DV: Economic Growth Model: Measures agreement with "Immigrants can contribute to Italy’s economic growth".

DV: National Duty Model: Measures agreement with "Assisting migrants is a national duty".

Script: regression_model_treatment1_vs_treatment2.py

Output & Analysis

Each script provides:

Regression Results from statsmodels:

R² (coefficient of determination)

Regression coefficients

Statistical significance (p-values)

Performance Metrics from sklearn:

Mean Squared Error (MSE)

R² Score

These results help determine whether the treatment groups have statistically significant effects on public opinion.

License

This project is intended for research purposes only.
