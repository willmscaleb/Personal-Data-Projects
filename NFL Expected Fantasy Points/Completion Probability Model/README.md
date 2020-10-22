# [Expected Fantasy Points](https://github.com/willmscaleb/Personal-Data-Projects/tree/main/NFL%20Expected%20Fantasy%20Points) Part 1: Completion Probability

## Overview
* Created completion probability models using limited situational input data achieving improved log-loss error over univariate baseline models.
* Optimized logistic regression, stochastic gradient descent, k-nearest neighbors, and xgboost classifiers hyperparameters with bayesian optimization through hyperopt.
* Transformed the model output into the following two outputs:
    * Expected fantasy points for a target not including yards after catch (YAC);
    * Expected fantasy points for a pass attempt not including YAC.
    
## Code and Resources Used
* **Python version:** 3.7
* **Packages:** pandas, numpy, scipy, sklearn, matplotlib, seaborn, xgboost, time
* **Data:** [nflfastR](https://github.com/guga31bb/nflfastR-data)
* **For web framework requirements:**

## Exploratory Data Analysis

## Modeling

### Algorithm Selection

Explain the thought process for which algorithms would likely perform well (include scikit learn selection diagram) and why. Address data normalization, for what algorithms it's necessary and what scoring.

### Baseline Models

### Hyperparameter Tuning

Add plots showing improvement iteration by iteration.

### Test Set Performance

## Expected Points By Target and Pass Attempt
