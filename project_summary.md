# Project Summary: Ames Housing Price Prediction

## Overview

This project aims to predict the sale prices of houses in Ames, Iowa using a linear regression model. The dataset contains 82 features and over 2900 entries.

## Key Steps Taken

- Handled missing data and filtered irrelevant columns.
- Performed EDA to understand correlations (e.g., `Gr Liv Area`, `Overall Qual` strongly correlated with `SalePrice`).
- Built a Linear Regression model.
- Evaluated model using R² Score and residual analysis.

## Model Performance

- **R² Score**: 0.822
- **mean_absolute_error**: 22708.90

## Insights

- High-quality homes (Overall Qual > 7) command significantly higher prices.
- Above-ground living area is one of the most predictive features.
- Garage and basement features also contribute significantly.

---

## Recommendations

- Try tree-based models like Random Forest or XGBoost.
