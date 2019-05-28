# RATIO 2019 Symposium . Benchmarking Workshop

We present 2 tasks related to argumentation mining:
  - Task 1: Same Side Classification
  - Task 2: Stance Classification
 
## Task 1: Same Side Classification

Given two arguments on the same topic, decide whether they have the same or opposite stance towards the topic. 


## Task 2: Stance Classification

Given an argument along with a topic, classify whether the argument is *pro* or *con* towards the topic.

## Settings
We have two experimental settings:
 - Within: Train on a set of topics and evaluate on the same set of topics.
 - Cross: Train on one topic and evaluate on another topic.
We choose the 2 topics with highest number of arguments: abortion and gay marriage


## Data
### Data source:
idebate.org, debatepedia.org, debatewise.org, debate.org

The data folder contains task1 and task2 training and testing data, for *cross* and *within* topics. You can split the *training* data as you like in order to train your model. After that, the model will be evaluated using the test data.


