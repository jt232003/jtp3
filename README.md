Crime-Cast: Forecasting Crime Categories
This repository contains my solution for the Kaggle competition Crime-Cast: Forecasting Crime Categories. This notebook was developed as part of my machine learning practice project at IIT Madras.

Project Overview
The objective of this project is to predict crime categories using historical crime data. By employing various machine learning techniques, the goal is to identify patterns and trends in the data that can help forecast future crime categories.

Contents
Crime_Cast_Notebook.ipynb: The main notebook containing the complete workflow, including data preprocessing, feature engineering, model building, and evaluation.
data/: Directory where the training and test datasets are stored (not included in the repository due to size limitations; please download them directly from the Kaggle competition page).
models/: Saved models used in this project (optional).
results/: Output files, including predictions and evaluation metrics.
Methodology
Data Loading: Loading the training and test datasets from the provided Kaggle input directory.
Data Exploration: Conducting an initial exploration to understand the data structure and content, including checking for missing values and summarizing statistics.
Data Preprocessing:
Imputation of missing values.
Encoding categorical variables.
Feature scaling.
Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
Feature Engineering:
Selection of numerical features.
Application of polynomial features and text vectorization.
Feature selection using techniques like SelectKBest.
Modeling:
Various classifiers such as Random Forest, Logistic Regression, K-Nearest Neighbors, Gradient Boosting, MLP, SVM, and XGBoost were employed.
Model tuning and selection using GridSearchCV.
Evaluation:
Assessing model performance using metrics such as accuracy, F1 score, recall, and confusion matrices.
Visualizing the results using Seaborn and Matplotlib.
Requirements
Python 3.x

Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, xgboost, folium, imblearn, etc.

Install the required libraries using:

bash
Copy code
pip install -r requirements.txt
How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/crime-cast.git
Navigate to the project directory:
bash
Copy code
cd crime-cast
Open the notebook:
bash
Copy code
jupyter notebook Crime_Cast_Notebook.ipynb
Follow the steps in the notebook to run the analysis.
Acknowledgments
Thanks to Kaggle for hosting the competition.
This project is part of my coursework at IIT Madras for practicing machine learning.
Contact
If you have any questions or suggestions, feel free to reach out to me on LinkedIn.
