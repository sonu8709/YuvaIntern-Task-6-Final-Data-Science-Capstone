# YuvaIntern Task 6 — Final Data Science Capstone Project

## Project
**Bank Marketing Campaign Analysis and Subscription Prediction**

## Business problem
Analyze historical bank marketing campaign data to understand patterns associated with term-deposit subscription and evaluate a baseline classifier for campaign prioritization.

## Dataset
UCI Machine Learning Repository — Bank Marketing, dataset ID 222.
Official page: https://archive.ics.uci.edu/dataset/222/bank+marketing

The notebook retrieves the dataset with `ucimlrepo`. An internet connection is required for the first fetch.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter Notebook, ucimlrepo.

## Workflow
1. Problem statement and success criteria
2. Dataset loading and quality assessment
3. Target preparation and duplicate checks
4. Exploratory data analysis and visualizations
5. Preprocessing pipeline with imputation and one-hot encoding
6. Logistic Regression baseline with class balancing
7. Precision, recall, F1, accuracy, ROC-AUC, confusion matrix and ROC curve
8. Business recommendations, limitations and future scope

## Important modeling decision
The `duration` field is excluded from the main predictor set because call duration is not known before a call starts. This reduces target leakage for a pre-call prioritization use case.

## Run
`pip install -r requirements.txt`

Open `Task_6_Bank_Marketing_Capstone.ipynb` and run cells from top to bottom.
