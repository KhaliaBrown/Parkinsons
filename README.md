This project applies multiple regression techniques to predict the total Unified Parkinson’s Disease Rating Scale (UPDRS) score using the Parkinson’s UPDRS dataset. 
The goal is to compare model performance, analyze overfitting and underfitting, and identify the most effective approach for accurate prediction in a medical context.

The following regression models were trained and evaluated:

- Linear Regression (baseline model)

- Lasso Regression (L1 regularization) for feature selection

- Ridge Regression (L2 regularization) to reduce overfitting

- Decision Tree Regression to capture non-linear relationships

- Gradient Boosted Regression Trees (GBRT) as an ensemble learning method

The dataset was split into 70% training and 30% testing, with performance evaluated using R² scores and residual analysis.

Overall, Linear Regression showed strong generalization with identical training and test R² scores of 0.910, while Lasso and Ridge Regression provided limited regularization benefits but lost accuracy with large alpha values. 
Decision Tree Regression achieved higher accuracy (R² = 0.958) but required depth control to avoid overfitting. 
Gradient Boosted Regression Trees performed best, with training and test R² scores of 0.988 and 0.986, demonstrating high accuracy and minimal overfitting.
