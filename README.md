# Crime-Cast: Forecasting Crime Categories

This repository contains my solution for the Kaggle competition [Crime-Cast: Forecasting Crime Categories](https://www.kaggle.com/competitions/crime-cast-forecasting-crime-categories). This notebook was developed as part of my machine learning practice project at IIT Madras.

## Project Overview

The objective of this project is to predict crime categories using historical crime data. By employing various machine learning techniques, the goal is to identify patterns and trends in the data that can help forecast crime categories.

## Contents

- **`Crime_Cast_Notebook.ipynb`**: The main notebook containing the complete workflow, including data preprocessing, feature engineering, model building, and evaluation.
- **`data/`**: Directory where the training and test datasets are stored (not included in the repository due to size limitations; please download them directly from the Kaggle competition page).
- **`results/`**: Output files, including predictions and evaluation metrics.

## Methodology

1. **Data Loading**: Loading the training and test datasets from the provided Kaggle input directory.
2. **Data Exploration**: Conducting an initial exploration to understand the data structure and content, including checking for missing values and summarizing statistics.
3. **Data Preprocessing**: 
   - Imputation of missing values.
   - Encoding categorical variables.
   - Feature scaling.
4. **Feature Engineering**: 
   - Selection of numerical features.
   - Feature selection using techniques like SelectKBest.
5. **Modeling**:
   - Various classifiers such as Random Forest, Logistic Regression, K-Nearest Neighbors, Gradient Boosting, MLP, SVM, and XGBoost were employed.
   - Model tuning and selection using GridSearchCV.
6. **Evaluation**: 
   - Assessing model performance using metrics such as accuracy, F1 score, recall, and confusion matrices.
   - Visualizing the results using Seaborn and Matplotlib.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`, `folium`, `imblearn`, etc.

## Contact

If you have any questions or suggestions, feel free to reach out:

- **LinkedIn**: [Jalaj Trivedi](https://www.linkedin.com/in/jalaj-trivedi-961b62221)

