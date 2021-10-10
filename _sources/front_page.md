# Titanic Survival

Essential Machine Learning Classification Coding Tutorials

![](./images/titanic.png)

Could you predict which passengers would survive the Titanic?

This is a classic classification problem, and we will use this problem to explore methods of machine learning, from logistic regression and Random Forests through to ‘Deep Learning’ using TensorFlow. Along the way we’ll look at processing data, how to run replicates, measuring accuracy, avoiding over-fitting with regularisation, trading off false positives and false negatives, feature selection and expansion, finding out how much data you need, optimising model parameters, dealing with imbalanced data, and more!

These examples will use Kaggle’s Titanic Survival data to explore machine learning. The Kaggle page may be found at: https://www.kaggle.com/c/titanic.

The contents of this book are:

## DATA PREPROCESSING

* *Kaggle Titanic survival*: data preprocessing: Getting our data in a form suitable for machine learning

## BASIC METHODS

The 'essentials' of machine learning, using a logistic regression model as our example model.

* *Logistic regression model*: A basic logistic regression model to predict survival.

* *Measuring model accuracy with K-fold stratification*: The best way to manage train/test data splits. Trains multiple models where all the data is used once, but only once, across the test sets.

* *Avoiding over-fitting with regularisation*: Prevent a model over-fitting to training data.

* *Accuracy measurements in machine learning*: Go beyond simply measuring the proportion of predictions that are right.

* *Application of alternative accuracy measurements to a logistic regression model*: See how different accuracy measurements are applied to Titanic survival data.

* *Learning curves - how much data do we need?*: Would gathering more data improve your accuracy. Do you need to use all the data you have?

* *Receiver Operator Characteristic (ROC) curve*: Many consider the ROC the 'gold standard' of measuring model performance.

## FEATURE SELECTION AND EXPANSION

Should you use all features? Is it useful to create extra polynomial features?

* *Feature selection using univariate statistical selection*: Select features based on how well they correlate with our target label.

* *Feature selection using forward selection*: Select features based on progressively selecting features that increase model accuracy most.

* *Feature selection using backward elimination*: Remove features based on progressively removing those that can be removed with the smallest loss in accuracy:

* *Feature expansion*: Add polynomial features (interactions between features) coupled with feature selection using forward selection.

## WORKING WITH IMBALANCED DATA SETS

Methods that help you manage data sets where there is not an even balance between classes.

* *Dealing with imbalanced data by model weighting*: Manage imbalance by adjusted the weight (influence) of different classes.

* *Dealing with imbalanced data by under or over sampling*: Sample the minority class more, or sample the majority class less.

* *Dealing with imbalanced data by changing classification cut-off levels*: Adjust the probability threshold used to classify data.

* *Dealing with imbalanced data by enhancing the minority class with synthetic data (SMOTE: Synthetic Minority Over-sampling Technique)*: Create synthetic examples of the minority class.

## RANDOM FOREST MODEL

A popular model type for structured data.

* *A Random *  Forest model*: Setting up a Random Forest model.

* *Random Forest Receiver Operator Characteristic (ROC) curve and balancing of model classification*: Performing a ROC analysis for Random Forest, and looking at the effect of adjusting classification threshold.

## TENSORFLOW NEURAL NETS

A popular framework for building neural networks.

* *TensorFlow neural net*: AN example taking you through the basics of setting up a neural network in TensorFlow including regularisation of neural networks, and automatically stopping training when the model is at peak performance.

* *TensorFlow api-based neural net*: A second, more versatile way, to build TensorFlow neural networks.

* *TensorFlow Receiver Operator Characteristic (ROC) curve and balancing of model classification*: Performing a ROC analysis for a neural network, and looking at the effect of adjusting classification threshold.

* *TensorFlow ‘Wide and Deep’ neural nets*: Combining 'shallow' and 'deep' learning in one neural network.

* *TensorFlow Bagging*: Train multiple networks to improve accuracy and/or get a measure of prediction uncertainty.

## EXTRAS

* *Checking model calibration*: Check that the model output probabilities are well calibrated.



