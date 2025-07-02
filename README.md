# ECSE-551
 
Classification is a fundamental problem in machine learning, with applications spanning healthcare,
manufacturing, finance, and beyond. Logistic regression, a widely used linear classifier, provides
an interpretable and computationally efficient method for binary classification by modeling the
probability of class membership using a sigmoid function. In this project, we implement logistic
regression from scratch and apply it to two datasets: the Chronic Kidney Disease (CKD) dataset and
the Battery dataset. The CKD dataset, consisting of 28 biological features, aims to predict whether
a patient has CKD, while the Battery dataset, comprising 32 numerical features, is used to classify
batteries as either normal or defective.

We begin by performing data analysis to examine the distributions of features and class labels. This
allows us to gain insights into potential feature correlations, class imbalances, and preprocessing
requirements. We then construct a logistic regression model from scratch, optimizing its parameters
through gradient descent. To assess our model’s robustness, we implement 10-fold cross-validation
and evaluate performance using accuracy. Additionally, we experiment with different learning rates,
feature selection techniques, and potential feature engineering strategies to determine their impact on
classification accuracy.
