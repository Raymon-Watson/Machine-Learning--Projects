# Titanic Survival - Machine Learning Project

Dataset from: https://www.kaggle.com/competitions/titanic/overview

A binary classification problem for predicting whether a passenger survived the Titanic disaster using machine learning.

## Project Structure
```text
Titanic-Kaggle/
├── data/
│   └── titanic.csv              # Raw dataset
│   └── titanic_cleaned.csv      # Cleaned dataset
├── 01_eda.ipynb                 # Exploratory Data Analysis
├── 02_data_cleaning.ipynb       # Data Cleaning & Feature Engineering
├── 03_model_building.ipynb      # Model Training & Evaluation
└── README.md
```

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
1. **Random Forest was the best performing model** with a tuned accuracy of 0.87 and F1 score of 0.83
2. **Sex** was by far the most important feature for predicting survival (~74% female survival, ~19% male survival)
3. **Overall survival rate** was only ~38%
4. **Lower fare reduced survival rate**, those with the lowest fare had a significantly lower chance of survival
5. **Larger family size improved survival rate**
6. **Passenger class** significantly impacted survival rate, with upper class having a survival percentage of ~63%, and lower class of ~24%


## How To Run This Project
1. Clone repository into relevant project folder
2. Ensure jupyter notebook is installed, along with all relevant libraries (contained at the top of the jupyter notebook files)
3. Start with 01_eda.ipynb for data exploration
4. Move to 02_data_cleaning.ipynb for data preparation
5. Finally, run 03_model_building.ipynb to train and evaluate models (Note: you can skip directly to this one and use the prepared data instead of running the first two notebooks)
