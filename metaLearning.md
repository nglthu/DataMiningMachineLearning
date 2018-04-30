# Purpose of meta learning
The mixture of experts: combining several different models. 

# Data involved

[labour](/DataMiningMachineLearning/meta-learning/data/labor.arff)
[glass](/DataMiningMachineLearning/meta-learning/data/glass.arff)

# Collection of model


1.  dividing the training data into several segments (n) 

2. building a model on each segment

3. keeping the dataset as it is without splitting but using several different algorithms to build model

## Bagging and Boosting

Noted: Meta tab

### Bagging

+ Select Meta option of Bagging from the classify tab in Weka 
+ select J48 as the base learner 
(note that the default base learner is the REP tree method). 
+ change REP tree to J48
(click in the white space beside the “Choose” button and then specify J48 as the base learner from the screen that appears (use the “Choose” button from the new screen).

### Boosting

### Bagging

+ Select Meta option of Boosting from the classify tab in Weka 
+ select J48 as the base learner 
(note that the default base learner is the REP tree method). 
+ change REP tree to J48
(click in the white space beside the “Choose” button and then specify J48 as the base learner from the screen that appears (use the “Choose” button from the new screen).

## Vote meta-learner

### Steps
1. meta-classifiers available, 
2. select the “Vote” meta-learner

```
Noted: The Vote meta-learner combines the output of two or more classifier models by choosing one of five voting rules. 
```