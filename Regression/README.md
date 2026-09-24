# Regression Projects

This folder contains machine learning projects focused on **regression problems**, where the objective is to predict a continuous numerical value.

The projects are intended to develop experience with exploratory data analysis, feature engineering, preprocessing, regression modelling, cross-validation, hyperparameter tuning, and model evaluation.

## Projects

| Project                | Dataset | Problem | Models / Methods | Evaluation | Status  |
| ---------------------- | ------- | ------- | ---------------- | ---------- | ------- |
| [House-Pricing](./house_pricing/)    | |   Predict residential property prices  | Linear Regression, Ridge, Lasso, Decision Trees, Random Forests     |          | In Progress |


As new projects are completed, they will be added to this table.

---

## Planned Projects

Potential regression projects include:

| Project                       | Problem                             | Techniques                                                      |
| ----------------------------- | ----------------------------------- | --------------------------------------------------------------- |
| Used Car Price Prediction     | Predict vehicle resale prices       | Feature engineering, regression pipelines, ensemble methods     |
| Energy Consumption Prediction | Predict continuous energy usage     | Regression, time-related features, model comparison             |

These projects may change as the repository develops.

---

## Regression Workflow

Projects will generally follow a workflow similar to:

```text
Problem Definition
        ↓
Exploratory Data Analysis
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train/Test Split
        ↓
Baseline Models
        ↓
Cross-Validation
        ↓
Hyperparameter Tuning
        ↓
Final Test-Set Evaluation
        ↓
Model Comparison and Conclusions
```

---

## Techniques Covered

Regression projects will explore techniques including:

* Linear regression
* Polynomial regression
* Feature scaling
* Feature engineering
* Categorical feature encoding
* Missing-value imputation
* Regularisation
* Ridge regression
* Lasso regression
* Elastic Net
* Decision Tree Regression
* Random Forest Regression
* Support Vector Regression
* Gradient boosting
* Cross-validation
* Hyperparameter tuning
* Regression pipelines

---

## Evaluation Metrics

Regression models will typically be assessed using:

| Metric | Purpose                                                    |
| ------ | ---------------------------------------------------------- |
| MAE    | Average absolute prediction error                          |
| MSE    | Average squared prediction error                           |
| RMSE   | Prediction error expressed in the same units as the target |
| R²     | Proportion of target variance explained by the model       |

Model evaluation will consider both predictive performance and the difference between training and validation performance to identify possible underfitting or overfitting.

---

## Tools

Projects primarily use:

* Python
* Jupyter Notebook
* NumPy
* pandas
* Matplotlib
* Seaborn
* scikit-learn

---

## Future Development

This folder will expand as I work through regression problems of increasing complexity, moving from baseline linear models toward regularised, tree-based, ensemble, and nonlinear regression methods.
