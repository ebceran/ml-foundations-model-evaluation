 Machine Learning Foundations — Model Evaluation Lab

This project demonstrates three fundamental techniques used in evaluating machine learning models:

Train / Validation / Test Split

Regularization (L1 & L2) with Logistic Regression

K-Fold Cross-Validation

These concepts form the backbone of reliable, explainable, and production-ready ML models in real-world environments such as finance, credit risk, and fraud detection.


 1. Train / Validation / Test Split

We divide the dataset into three parts to examine how well a model generalises:

Training Set → where the model learns

Validation Set → used for tuning model performance

Test Set → final evaluation on unseen data

A well-generalised model will show similar accuracy across all three sets.

 
 2. Regularization (L1 & L2)

We compare two types of regularization:

L2 (Ridge) → shrinks coefficients but does not eliminate them

L1 (Lasso) → performs feature selection by setting some coefficients to zero

This helps reduce overfitting and improves model stability.


3. K-Fold Cross-Validation

Cross-validation evaluates the model across multiple splits of the data, ensuring stable and trustworthy results.
We use:

5-fold CV

10-fold CV

The mean accuracy across folds indicates the true generalisation capability of the model.


** Dataset

Breast Cancer Wisconsin Dataset

Loaded from sklearn.datasets

Commonly used for binary classification benchmarks


* What This Project Demonstrates

✔ How to properly split data for fair evaluation
✔ How regularization affects model complexity
✔ How L1 eliminates features and L2 smooths them
✔ How cross-validation increases confidence in model performance
✔ Why these techniques are essential in risk modelling and financial ML


* Technologies Used

Python

NumPy

Pandas

scikit-learn

Matplotlib (optional)


Author
Emine Ceran — Financial Data Scientist in training
Building strong foundations in machine learning, statistics, and financial modelling.
