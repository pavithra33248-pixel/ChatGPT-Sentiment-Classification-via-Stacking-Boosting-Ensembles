Set-Content -Path README.md -Value @"
# ChatGPT Sentiment Classification via Stacking & Boosting Ensembles

A comparative machine learning framework analyzing public sentiment on ChatGPT tweets using AdaBoost, XGBoost, LightGBM, and CatBoost combined via Stacking and Voting ensembles.

## Overview
- **Ensembles:** Stacking Classifier, Majority Voting Classifier
- **Base Estimators:** AdaBoost, XGBoost, LightGBM, CatBoost
- **Metrics:** Precision, Recall, F1-Score, ROC-AUC curves

## Execution
1. Data Cleaning: Run \`preprocessing.ipynb\`
2. Model Training: Run \`ensemble.ipynb\`
3. Evaluation: Run \`performanceevalution.ipynb\`
"@