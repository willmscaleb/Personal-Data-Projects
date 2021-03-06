# Caleb Willms Project Portfolio

## Background

During my undergraduate studies in Mechanical Engineering at McGill University, I took a Combustion course that required I learn python. Learning python led me to discover Kaggle, where I started to dabble in machine learning. It was fascinating! I have always been obsessed with sports analytics (particularly hockey and football) and I realized that I could use my new found data and programming skills to uncover an entire new world of possibilities in this field. As an added bonus, I would be developing highly valued data science skills that could lead to fascinating employment opportunities. So, I started documenting my projects. This repository is a compilation of my most interesting work to date.

## Projects

### [NFL Expected Fantasy Points](https://github.com/willmscaleb/Personal-Data-Projects/tree/main/NFL%20Expected%20Fantasy%20Points)
The goal of this project is (currently the project is in progress) to create a metric for expected individual player fantasy points based on the opportunity that player receives in a given game. This metric should be more predictive of future fantasy points than any freely available metrics.

To achieve this goal, instead of making a single model to predict overall play by play fantasy points scored, I decomposed the problem into several sub-problems in order to more easily determine and predict patterns unique to each sub-problem. There are 4 classification models and 2 regression models that will make up the expected fantasy points metric.

#### 1. [Completion Probability](https://github.com/willmscaleb/Personal-Data-Projects/tree/main/NFL%20Expected%20Fantasy%20Points/Completion%20Probability%20Model)
* Created completion probability models using limited situational input data achieving improved log-loss error over univariate baseline models.
* Optimized logistic regression, stochastic gradient descent, k-nearest neighbors, and xgboost classifiers hyperparameters with bayesian optimization through hyperopt.
* Transformed the model output into the following two outputs:
    * Expected fantasy points for a target not including yards after catch (YAC);
    * Expected fantasy points for a pass attempt not including YAC.

![](NFL%20Expected%20Fantasy%20Points/Completion%20Probability%20Model/Images/cmp_gridm.png)

#### 2. Expected Yards After Catch <sup>1</sup>
#### 3. Touchdown Probability <sup>1</sup>
#### 4. Expected Rushing Yards <sup>1</sup>
#### 5. Fumble Lost Probabilty <sup>1</sup>
#### 6. Interception Probability <sup>1</sup>



<sup>1</sup> : Model is currently in development

## Contact
[Linkedin Profile](https://www.linkedin.com/in/calebwillms/)

willms.caleb@gmail.com
