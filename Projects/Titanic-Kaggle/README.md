# Titanic Survival - Machine Learning Project

Dataset from: https://www.kaggle.com/competitions/titanic/overview

A binary classification problem for predicting whether a passenger survived the Titanic disaster using machine learning.

## Notebooks
|Number| Notebook|Details|
|-|-|-|
|01|01_eda.ipynb|Initial data exploration, missing value analysis, univariate and bivariate analysis, correlation|
|02|02_data_cleaning.ipynb| Handled missing values (various imputation methods), feature engineering, category encoding (including OneHot encoding)|
|03|03_model_building.ipynb| Train/Test split of data, feature scaling, 6 classification models, cross validation, ROC curves, model comparison, fine-tuning with GridSearchCV|


## Results
6 classification models were trained and compared, with the best performing model (Random Forest) chosen for further tuning, and denoted Tuned Random Forest:
|Model|Accuracy|Precision|Recall|F1|
|-|-|-|-|-|
|Decision Tree|0.79|0.77|0.71|0.74|
|Random Forest|0.87|0.84|0.82|0.83|
|K-Nearest Neighbors|0.84|0.75|0.83|0.79|
|Support Vector Machine|0.85|0.81|0.80|0.81|
|Stochastic Gradient Descent|0.78|0.80|0.68|0.73|
|Logistic Regression|0.82|0.78|0.75|0.77|
|Tuned Random Forest|0.87|0.83|0.83|0.83|

Best GridSearchCv parameters: {'max_depth': 8, 'min_samples_leaf': 1, 'min_samples_split': 7, 'n_estimators': 50}

## Key Findings
1. **Sex** was by far the most important feature for predicting survival
2. **Feature engineering** (e.g. Fam, AgeGroup) did not have a significant impact on model performance
3. **Model tuning** with GridSearchCV meaningfully improved the Random Forest model
4. There was no strictly obvious outlier in models
5. Data standardization was utilized to improve model accuracy


## How To Run This Project
1. Clone repository into relevant project folder
2. Ensure jupyter notebook is installed, along with all relevant libraries (contained at the top of the jupyter notebook files)
3. Start with 01_eda.ipynb for data exploration
4. Move to 02_data_cleaning.ipynb for data preparation
5. Finally, run 03_model_building.ipynb to train and evaluate models (Note: you can skip directly to this one and use the prepared data instead of running the first two notebooks)
