# Expected Fantasy Points Part 1: Completion Probability

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
