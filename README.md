# RATIO 2019 Symposium . Benchmarking Workshop

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
