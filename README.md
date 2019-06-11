
 - Prerequisite:
 Please download [Git lfs](https://git-lfs.github.com/) 
 
# Same Side Classification

We present 1 task related to argumentation mining:
  - Same Side Classification
  
## Task: Same Side Classification

Given two arguments on the same topic, decide whether they have the same or opposite stance towards the topic. 


## Settings
We have two experimental settings:
 - Within: Train on a set of topics and evaluate on the same set of topics.
 - Cross: Train on one topic and evaluate on another topic.
We choose the 2 topics with highest number of arguments: abortion and gay marriage


## Data
### Data source:
idebate.org, debatepedia.org, debatewise.org, debate.org

The data folder contains the training and testing data, for *cross* and *within* topics. You can split the *training* data as you like in order to train your model. After that, the model will be evaluated using the test data.

## Baseline
We trained a model using lemma 3 grams for argument1 and argument2 on the training set and then we evaluated the model using the test set. The results are the following:

 - Within Topics:
   - 	Accuracy: 54%
   - 	Macro-F1:  0.39
   - 	Micro-F1: 0.54

 - Cross Topics:
   - 	Accuracy: 58%
   - 	Macro-F1:  0.39
   - 	Micro-F1: 0.58

