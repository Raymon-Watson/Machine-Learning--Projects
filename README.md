# Machine Learning Projects

This repository contains a collection of machine learning projects completed as part of my ongoing study of data science and machine learning.

The projects are organised into two main areas:

* **Classification**
* **Regression**

Each project is contained in its own folder and follows a structured workflow including exploratory data analysis, data preprocessing, model development, evaluation, and model comparison.

## Repository Structure

```text
machine-learning-projects/
│
├── classification/
│   │
│   ├── mnist/
│   │   ├── notebooks/
│   │   ├── data/
│   │   └── README.md
│   │
│   └── titanic/
│       ├── notebooks/
│       ├── data/
│       └── README.md
│
├── regression/
│   └── ...
│
└── README.md
```

The repository will expand as I work through additional machine learning problems and modelling techniques.

---

## Classification Projects

### MNIST Digit Classification

The MNIST project explores supervised classification using the MNIST handwritten digit dataset.

The objective is to classify images of handwritten digits into one of ten classes:

```text
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

This project is being used to explore and compare several classification algorithms, including:

* Stochastic Gradient Descent
* Support Vector Machines
* K-Nearest Neighbours
* Naive Bayes
* Random Forests
* Multiclass classification strategies

Topics covered include:

* Data inspection and visualisation
* Feature scaling
* Binary and multiclass classification
* Cross-validation
* Confusion matrices
* Precision, recall, and F1 score
* ROC curves
* Hyperparameter tuning
* Model comparison

---

### Titanic Survival Prediction

This project uses the Kaggle Titanic dataset to predict whether a passenger survived the sinking of the Titanic.

The project focuses on working with mixed numerical and categorical data and developing a complete classification workflow.

Topics covered include:

* Exploratory data analysis
* Missing-value analysis
* Data imputation
* Categorical feature encoding
* Feature engineering
* Train/test splitting
* Stratified sampling
* Classification pipelines
* Cross-validation
* Hyperparameter tuning
* Model evaluation

Models explored include:

* Logistic Regression
* Decision Trees
* Random Forests
* Support Vector Machines
* K-Nearest Neighbours
* Naive Bayes

Model performance is assessed using metrics such as:

* Accuracy
* Precision
* Recall
* F1 score
* ROC-AUC
* Confusion matrices

---

## Regression Projects

Regression projects will be added as I progress through different supervised regression techniques.

Planned topics include:

* Linear Regression
* Polynomial Regression
* Regularisation

  * Ridge
  * Lasso
  * Elastic Net
* Decision Tree Regression
* Random Forest Regression
* Support Vector Regression
* Gradient Boosting
* Feature engineering
* Cross-validation
* Hyperparameter optimisation
* Regression model evaluation

Typical regression metrics will include:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² score

---

## General Project Workflow

Where appropriate, projects follow a similar machine learning workflow:

```text
1. Problem Definition
        ↓
2. Data Loading
        ↓
3. Exploratory Data Analysis
        ↓
4. Data Cleaning
        ↓
5. Feature Engineering
        ↓
6. Data Preprocessing
        ↓
7. Train/Test Split
        ↓
8. Baseline Models
        ↓
9. Cross-Validation
        ↓
10. Hyperparameter Tuning
        ↓
11. Final Model Evaluation
        ↓
12. Conclusions
```

Using a consistent structure makes it easier to compare different datasets, models, and modelling approaches.

---

## Tools and Libraries

The projects primarily use Python and the standard data science and machine learning ecosystem.

### Core Tools

* Python
* Jupyter Notebook
* Git
* GitHub

### Data Analysis

* NumPy
* pandas

### Visualisation

* Matplotlib
* Seaborn

### Machine Learning

* scikit-learn

Common scikit-learn components used throughout the projects include:

```python
train_test_split
cross_val_score
cross_validate
cross_val_predict
GridSearchCV
Pipeline
StandardScaler
OneHotEncoder
SimpleImputer
```

as well as classification and regression estimators.

---

## Goals

The main goals of this repository are to:

* Develop practical machine learning skills using real datasets.
* Build a strong understanding of the major supervised learning algorithms.
* Learn how to construct reproducible machine learning workflows.
* Improve Python, pandas, NumPy, Matplotlib, and scikit-learn skills.
* Practise exploratory data analysis and feature engineering.
* Learn appropriate model evaluation techniques.
* Compare multiple models rather than relying on a single algorithm.
* Develop experience with cross-validation and hyperparameter optimisation.
* Build a portfolio of machine learning projects demonstrating practical data science skills.

---

## Future Projects

As the repository develops, I plan to add projects covering areas such as:

* Housing price prediction
* Customer churn prediction
* Credit risk classification
* Medical classification datasets
* Ensemble learning
* Gradient boosting
* Dimensionality reduction
* Unsupervised learning
* Clustering
* Principal Component Analysis
* End-to-end machine learning pipelines

---

## Status

This repository is a work in progress and will continue to expand as I work through additional machine learning techniques and datasets.
