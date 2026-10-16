# Titanic Survival Prediction Using Decision Tree Classification

## Project Overview
This project uses Decision Tree Classification to predict Titanic passenger survival based on features such as age, gender, passenger class, and ticket fare.

## Dataset
The dataset contains 891 passenger records. The target variable is `Survived`, where 0 represents non-survival and 1 represents survival.

## Methods and Tools
- Python, Pandas, NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Data Cleaning and Feature Encoding
- Decision Tree Classification (Gini and Entropy)
- GridSearchCV and Cross-Validation
- Feature Importance Analysis

## Model Results

| Model | Testing Accuracy |
|---|---|
| Decision Tree (Gini) | 79.33% |
| Decision Tree (Entropy) | 80.45% |
| Tuned Decision Tree | 82.12% |

## Key Findings
Gender and passenger class were the most influential predictors in the initial Decision Tree model. Hyperparameter tuning improved the exploratory testing accuracy, while cross-validation helped evaluate model complexity and overfitting.

## Conclusion
This project demonstrates the application of supervised machine learning to a binary classification problem, including data preprocessing, model evaluation, visualization, and hyperparameter optimization.

**Note:** Missing values were initially imputed before the train/test split, so the reported performance should be considered exploratory.
