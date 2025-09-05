# Data_Analytics

A project into the prediction of wildfire structure damage risk using CAL FIRE data, via data preparation and Machine Learning.

## Project Overview
This project uses data from the California Department of Forestry and Fire Protection (CAL FIRE)
to build a data analytics and machine learning pipeline for predicting structure damage risk during wildfires.

The goal is to clean, analyze, and model the data to identify key risk factors and build predictive models that can support decision-making in wildfire management.

## Methodology

### The work was carried out in two major parts:

1. Data Preparation & Exploration

- Data quality checks (missing values, duplicates, data types, constant columns).

- Descriptive statistics for continuous & categorical features.

- Visualization: histograms, boxplots, bar charts.

- Data quality plan: strategies for handling missing or inconsistent values.

- Feature engineering: creation of domain-informed features.

2. Predictive Modeling

- Train/test split (70% / 30%).

- Models trained and compared:
  - Linear Regression (baseline)
  - Logistic Regression
  - Random Forest

- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.

- Cross-validation for robust evaluation.

- Model improvement with feature selection, transformations, and ensemble ideas.

## Findings

- Certain geographic and structural features are strongly correlated with wildfire damage risk.

- Random Forest consistently outperformed Linear and Logistic Regression.

- Feature engineering (e.g., temporal features, combined risk indicators) improved predictive performance.