# Classification Projects

This folder contains machine learning projects focused on **classification problems**, where the objective is to predict a discrete class or category.

The projects are used to practise complete classification workflows, including exploratory data analysis, preprocessing, feature engineering, model training, cross-validation, hyperparameter tuning, and final model evaluation.

## Projects

| Project                                   | Dataset                  | Problem                                     | Models / Methods                                                         | Evaluation                                                 | Status      |
| ----------------------------------------- | ------------------------ | ------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------- | ----------- |
| [MNIST Digit Classification](./MNIST-classification/)    | MNIST handwritten digits | Multiclass classification of digits 0–9     | SGD, SVM, KNN, Naive Bayes, Random Forest, multiclass strategies         | Accuracy, Precision, Recall, F1, Confusion Matrix          | In Progress |
| [Titanic Survival Prediction](./Titanic-Kaggle/) | Kaggle Titanic           | Binary classification of passenger survival | Logistic Regression, Decision Tree, Random Forest, SVM, KNN, Naive Bayes | Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix | In Progress |

---

## Classification Workflow

Projects generally follow a workflow similar to:

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

Across the classification projects, I am developing experience with:

* Binary classification
* Multiclass classification
* Data preprocessing
* Missing-value imputation
* Numerical feature scaling
* Categorical feature encoding
* Feature engineering
* Stratified train/test splitting
* Cross-validation
* Hyperparameter tuning
* Model comparison
* Classification thresholds
* Confusion matrices
* ROC curves and ROC-AUC

## Evaluation Metrics

Depending on the problem, classification models are assessed using metrics such as:

| Metric           | Purpose                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------- |
| Accuracy         | Overall proportion of correct predictions                                               |
| Precision        | Proportion of predicted positives that are correct                                      |
| Recall           | Proportion of actual positives correctly identified                                     |
| F1 Score         | Balance between precision and recall                                                    |
| ROC-AUC          | Ability of a binary classifier to separate the classes across classification thresholds |
| Confusion Matrix | Breakdown of correct and incorrect predictions by class                                 |

For multiclass problems, class-level and aggregated precision, recall, and F1 scores may also be considered.

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

## Future Projects

Additional classification projects will be added as I explore more datasets and modelling techniques.

Potential future topics include:

* Customer churn prediction
* Credit risk classification
* Medical diagnosis classification
* Text classification
* Ensemble classifiers
* Gradient boosting
* Imbalanced classification
