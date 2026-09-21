# Machine Learning Projects

This repository contains a collection of machine learning projects completed as part of my ongoing study of **data science, machine learning, and neural networks**.

The projects are currently organised into two main areas:

* **Classification**
* **Regression**

Each project is contained in its own folder and follows a structured workflow including exploratory data analysis, data preprocessing, model development, evaluation, and model comparison.

As the repository develops, projects will progress from classical machine learning methods toward **neural networks and deep learning techniques**.

---

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

The repository will expand as I work through additional machine learning problems, modelling techniques, and neural network architectures.

---

## Classification Projects

### MNIST Digit Classification

The MNIST project explores supervised classification using the MNIST handwritten digit dataset.

The objective is to classify images of handwritten digits into one of ten classes:

```text
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

This project provides a useful environment for comparing a range of classification algorithms, from traditional machine learning methods to neural networks.

Models and approaches explored or planned include:

* Stochastic Gradient Descent
* Support Vector Machines
* K-Nearest Neighbours
* Naive Bayes
* Random Forests
* Multiclass classification strategies
* Fully connected neural networks
* Convolutional Neural Networks

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
* Neural network training
* Image classification
* Comparison between classical ML and neural network approaches

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
* Neural Network Regression
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

## Neural Networks and Deep Learning

As I progress beyond classical machine learning models, this repository will also include projects exploring **neural networks and deep learning**.

The aim is to understand both how neural networks are implemented and the theory behind how they learn.

### Core Neural Network Concepts

Topics to be explored include:

* Artificial neurons
* Layers and network architecture
* Input, hidden, and output layers
* Weights and biases
* Activation functions

  * ReLU
  * Sigmoid
  * Tanh
  * Softmax
* Forward propagation
* Loss functions
* Gradient descent
* Backpropagation
* Mini-batch training
* Epochs and batch size
* Learning rates
* Weight initialisation
* Optimisers

  * Stochastic Gradient Descent
  * Momentum
  * RMSprop
  * Adam

### Model Training

Neural network projects will explore:

* Training and validation sets
* Learning curves
* Overfitting and underfitting
* Early stopping
* Dropout
* Batch normalisation
* Regularisation
* Hyperparameter tuning
* Model evaluation

### Neural Network Architectures

Planned architectures include:

| Architecture                       | Typical Application                                  |
| ---------------------------------- | ---------------------------------------------------- |
| Multilayer Perceptron (MLP)        | Tabular classification and regression                |
| Convolutional Neural Network (CNN) | Image classification and computer vision             |
| Recurrent Neural Network (RNN)     | Sequential data                                      |
| LSTM / GRU                         | Longer sequential dependencies                       |
| Autoencoder                        | Representation learning and dimensionality reduction |
| Transformer                        | Language and sequence modelling                      |

Initial projects will focus primarily on **fully connected neural networks and convolutional neural networks** before progressing to more advanced architectures.

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

For neural network projects, this workflow may additionally include:

```text
M
```
