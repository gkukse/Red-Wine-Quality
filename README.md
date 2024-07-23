# Red Wine Quality
## Overview
The project inspects Red Wine dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?resource=download). The primary objectives are to clean the data, perform exploratory data analasys, statistical analasys, and model linear regression on Quality and Alcohol features. Multicollinearity analysis, feature engineering and resampling were explored.

## Dataset
Dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?resource=download).

## Python Libraries

This analysis was conducted using Python 3.11. The following packages were utilized:

- duckdb=0.9.1
- matplotlib=3.7.1
- numpy=1.25.0
- pandas=1.5.3
- scipy=1.11.1
- seaborn=0.12.2
- sqlite3=3.41.2
- sklearn=0.0.post5
- statsmodels=0.14.0
- textblob=0.17.1
- unidecode=1.3.7

## Findings

- Exploratory Data Analysis (EDA): The dataset appeared to have no missing values or outliers, and the variables showed a mix of normal and non-normal distributions.
- Correlation: No strong linear correlations were evident among the variables.
- Multicollinearity: Techniques such as variance inflation factor (VIF) analysis and feature engineering were applied to tackle multicollinearity issues.
- Statistical Testing: Hypothesis testing revealed some notable differences in mean feature values across different Quality scores.
- Models: Initially, linear regression models were created but faced challenges due to issues like multicollinearity and dataset imbalance. Attempts to improve model performance through resampling techniques and feature engineering did not yield significant enhancements.

## Future Work

- Explore the non-linear models: Decision Trees, Random Forests, or Gradient Boosting to improve predictive performance.
- Employing dimensionality reduction techniques like Principal Component Analysis (PCA) or t-Distributed Stochastic Neighbor Embedding (t-SNE) to condense the feature space and enhance interpretability.
- Address class imbalance by utilizing advanced methods, such as Synthetic Minority Over-sampling Technique (SMOTE), Adaptive Synthetic Sampling (ADASYN), or weighted loss functions within models.


## Visualization Dashboard

For a visual overview, you can visit the [Tableau Public overview](https://public.tableau.com/app/profile/gintare6386/viz/Wine_quality_17040495299440/RedWineQuality_1?publish=yes).
