# Drug Discovery using Random Forest Regression

This repository demonstrates a machine learning-based approach to drug discovery, focusing on predicting the bioactivity of chemical compounds against the SARS Coronavirus 3C-like proteinase.

## Project Overview

This project explores how machine learning models can predict compound efficacy, enabling faster identification of potential inhibitors.

### Data Acquisition and Preprocessing
- Retrieved bioactivity data from the **ChEMBL database**, specifically targeting compounds with IC50 values (a measure of inhibitor potency).
- Transformed the raw data into usable molecular descriptors and fingerprints for model input.

### Machine Learning Workflow
- Implemented a regression pipeline using multiple models, including **Random Forest Regressor**, **Gradient Boosting**, and **XGBoost**, among others.
- Evaluated the models on metrics such as:
  - **\( R^2 \):** Coefficient of determination
  - **RMSE:** Root Mean Square Error
  - **Training Time**

### Exploration with LazyRegressor
- Automated the benchmarking of over 30 regression models using the **LazyRegressor** library.
- Generated performance comparisons to identify the best-suited models for predicting compound efficacy.

### Data Visualization
- Created insightful plots to compare \( R^2 \), RMSE, and time taken by each model.
- Highlighted top-performing models that achieved the highest predictive accuracy with minimal error.

### Impact
- Demonstrates how machine learning can accelerate the identification of potential inhibitors, reducing the time and cost of traditional drug discovery methods.
- Offers a reusable framework for bioactivity prediction applicable to other protein targets and diseases.
