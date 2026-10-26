# Sales Data Set Analysis

## Overview
An exhaustive exploratory data analysis (EDA), anomaly detection, principal component analysis (PCA), and predictive modeling project on retail sales datasets (dress, sweater, and pants sales).

## Architecture & Pipeline
1. **Data Ingestion**: Loads multi-sheet Excel workbooks (`DataSetVentes.xlsx`) containing dress, sweater, and pants sales.
2. **Cleaning & Preprocessing**: Handles duplicates, outlier detection via Z-scores and box plots, and feature standardization.
3. **Dimensionality Reduction**: Implements manual PCA from scratch (covariance matrix calculation, eigenvalue decomposition, Kaiser rule component selection).
4. **Regression Modeling**: Trains linear regression models across product categories and evaluates performance with MSE, MAE, RMSE, and $R^2$ scores.

## Data
- **Dataset**: Multi-sheet Excel workbook (`DataSetVentes.xlsx`) with dress, sweater, and pants sales figures.

## Method & Algorithms
- **Exploratory Data Analysis**: Statistical summaries, distribution analysis, correlation matrices (Pearson correlation), and boxplot visualizations.
- **PCA**: Manual Eigenvalue decomposition and Kaiser criterion component selection.
- **Regression Evaluation**: $R^2$ score, MSE, RMSE, and Mean Absolute Error.

## Verified Results & Metrics
- Achieved **$R^2 = 0.94$** on sweater sales regression modeling.
- Achieved **$R^2 = 0.83$** on dress sales regression modeling.
- Achieved **$R^2 = 0.65$** on pants sales regression modeling.

## Limitations & Caveats
- Analysis performed on historical retail dataset workbook; offline analytical study.

## Run Instructions
```bash
jupyter notebook projet.ipynb
```

## CV Bullet Points
- Performed comprehensive EDA, anomaly detection, and regression modeling on multi-category retail sales datasets achieving high predictive fit ($R^2 = 0.94$ for sweaters, $R^2 = 0.83$ for dresses).
- Implemented Principal Component Analysis (PCA) from scratch via eigenvalue decomposition and Kaiser rule component selection.
- Calculated Pearson correlation matrices and evaluated regression performance using MSE, RMSE, and $R^2$ metrics.

## Claims to Avoid
- Do not claim real-time enterprise retail deployment or commercial pipeline integration.
