# wine-quality-prediction
Machine Learning project for predicting wine quality using Logistic Regression and XGBoost classifiers.

## Dataset Overview
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- Total instances: **6,497**
  - Red wine: 1,599
  - White wine: 4,898
- Features: 11 physicochemical inputs (e.g., alcohol, pH, sulphates)
- Target: Wine quality score (0–10)

## Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Visualizations of feature distributions and correlations
   - Violin plots and PCA projections for dimensionality insight

2. **Data Preprocessing**
   - Label transformation (binary: good vs. bad quality)
   - Feature scaling and train-test split

3. **Modeling**
   - Logistic Regression (with hyperparameter tuning)
   - XGBoost Classifier (with extensive parameter grid search)

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion matrix visualization
   - Model performance comparison chart

## Key Insights 
- **Alcohol** and **volatile acidity** showed strong correlation with wine quality.
- XGBoost captured non-linear feature relationships and yielded better generalization.
- Precision–Recall tradeoffs indicate XGBoost is more reliable at identifying high-quality wines.
