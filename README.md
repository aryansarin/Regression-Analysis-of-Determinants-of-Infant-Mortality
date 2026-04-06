# Regression Analysis of Determinants of Infant-Mortality
A Multi Linear Regression Analysis of the determinants of Infant Mortality using SDG data.
## Overview
This mini project analyzes the impact of **Skilled Birth Attendance (SBA)** and **Maternal Mortality Rate (MMR)** on infant mortality rates using regression techniques in R.

## Model
A linear regression model was estimated:

Infant Mortality rates = β0 + β1(SBA) + β2(MMR) + ε

## Diagnostics
Residual analysis was performed using:
- Residual vs Fitted Plot
- Histogram of Residuals
- Q-Q Plot

## Statistical Tests
- Breusch-Pagan Test (Heteroscedasticity)
- Shapiro-Wilk Test (Normality)

## Key Findings
- Presence of heteroscedasticity and non-normality in residuals.
- Issues corrected using **robust standard errors**.
- SBA and MMR show significant relationships with infant mortality.

## Tools Used
- R
- ggplot2
- lmtest
- sandwich
