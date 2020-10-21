# NFL Expected Fantasy Points

## Introduction

## Problem Statement

In fantasy football there is a well known saying that "volume is king". In other words, when analyzing players, the most important thing to consider is the opportunity they receive, not the efficiency (or skill) of said player. Expected fantasy points is a metric meant to capture the value of a player's opportunity. 

The concept was first introduced by Mike Clay from ESPN. He calls it OFP for opportunity adjusted fantasy points and describes it as what an average player would most likely score given the workload. 

So, what's the difference between my model and Mike Clay's? Well, first of all, you can't access Mike Clay's numbers without a subscription to ESPN+ and if you're like me, you want your metrics free (other expected fantasy points models are also not freely available). Secondly, it isn't public knowledge what his model considers and how it works, so you just have to take his numbers at face value without truly understanding what they're specifically telling you. Thirdly, Mike Clay has discussed one shortfall of his metric (I listen to an ESPN podcast he frequently speaks on) - that the per play expected points totals are always additive regardless of whether or not they should be. For example, a RB could get 4 carries in a row from the 1 yardline and fail on them all. His OFP would then be much higher than 6.1, despite this being the theoretical maximum number of points the RB could have scored since his model adds all expected points per play independently. My model fixes this issue.

## Approach

Instead of making a single model to predict play by play fantasy points scored, I decomposed the problem into several sub-problems in order to more easily determine and predict patterns unique to each sub-problem. So this project has 6 models that make up the overall expected points model. They are:
1. [Completion Probability](https://github.com/willmscaleb/Personal-Data-Projects/edit/main/NFL%20Expected%20Fantasy%20Points/README.md): when a pass is attempted, what is the probability it is completed?
2. Expected Yards After Catch: when a pass is completed, how many yards after the catch will the receiver accumulate?
3. Touchdown Probability: 
    1. Pass Attempts: when a pass is attempted, what is the probability it ends in an offensive touchdown?
    2. Rush Attempts: when a run is attempted, what is the probability it ends in an offensive touchdown?
4. Expected Rushing Yards: when a run is attempted, how many yards will the runningback accumulate?
5. Fumble Lost Probabilty: when a pass is completed, a run is attempted or a quarterback is sacked, what is the likelihood that the ball carrier loses a fumble? 
6. Interception Probability: when a pass is attempted, what is the probability it ends in an interception?

## Results

## Applications

## Areas to Improve


