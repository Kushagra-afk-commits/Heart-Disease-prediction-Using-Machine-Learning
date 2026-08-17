# Heart-Disease-prediction-Using-Machine-Learning
Machine learning project for predicting heart disease using the UCI Cleveland Heart Disease dataset.

# Heart Disease Machine Learning Project

This project predicts the presence of heart disease using the processed Cleveland Heart Disease dataset from the UCI Machine Learning Repository.

## Project Aim

The aim is to compare machine learning models for heart disease prediction using patient clinical information and select the best-performing overall model.

## Dataset

- Source: UCI Machine Learning Repository
- Dataset: Processed Cleveland Heart Disease dataset
- Records: 303
- Predictors: 13
- Target: Heart disease presence

The original `num` target variable ranged from 0 to 4. It was converted into a binary target:

- 0 = No heart disease
- 1 to 4 = Heart disease present

## Project Workflow

1. Dataset loading and variable understanding
2. Data-quality checks and descriptive analysis
3. Exploratory data analysis and correlation analysis
4. Preprocessing and stratified train-test split
5. Model training and evaluation
6. Confusion-matrix comparison
7. ROC curve comparison and best-model selection

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbours
- Support Vector Machine
- Gradient Boosting
- Neural Network

## Preprocessing

- Median imputation for numerical missing values
- Most-frequent imputation for categorical missing values
- StandardScaler for numerical variables
- One-hot encoding for categorical variables
- 80:20 stratified train-test split
- `random_state=42`

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix
- ROC curves

## Best Model

Logistic Regression was selected as the best overall model.

- Accuracy: 0.89
- Precision: 0.84
- Recall: 0.93
- F1-score: 0.88
- ROC-AUC: 0.97
- False negatives: 2

## Student Roles

- 1: Dataset loading and basic understanding
- 2: Data-quality checks and descriptive analysis
- 3: EDA and correlation analysis
- 4: Preprocessing, Logistic Regression and Decision Tree
- 5: Remaining models, metrics, confusion matrices, ROC curves and best-model selection

## Repository Files
- `Heart_Disease_All_Models.ipynb` – Complete Python notebook
- `README.md` – Project overview
- `requirements.txt` – Required Python libraries

## Important Note

This project is for academic and educational purposes only. It is not a clinical diagnostic system and requires external validation before any real-world healthcare use.
