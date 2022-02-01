---
layout: page
---
![alt-text-1](/assets/img/ED2.png "title") 

## <font color="#E34000"><b>Step 1: Data Preprocessing</b></font>

<font color="#E34000"><b>Dataset specifics</b></font>

![alt-text-1](/assets/img/Dataset.jpg "title") 

Above is a portion of how the dataset is set up, the <b>class</b> column being the dependent variable vector.
- Dataset taken from UCI Machine Learning Repository
- 8124 instances of mushroom data
- 48% poisonous, 52% nonpoisonous (balanced dataset)
- 22 attributes
- 23 features

<font color="#E34000"><b>Preprocessing requirements</b></font>

- Handle <u>missing data</u> of stalk-root feature by making missing values its own category in the stalk root feature. 
- Encode <u>categorical data</u> using one-hot encoding.
- Use the <u>Chi-Square test for Independence</u> to conduct feature selection

## <font color="#E34000"><b>Step 2: Overfitting Mitigation</b></font>
K fold cross validation was used, with the stratified variant in particular. Due to this implementation, it will take longer to run the model, but since this dataset is not very large, it should be fine. 

Why stratified?
It will retain the percentage of samples for each class when implemented to make the splits. It would not be good to have one group with too many red mushrooms, for example.

## <font color="#E34000"><b>Step 3: Train binary classifiers</b></font>

- <b>Logistic Regression</b>
- <b>Naive Bayes</b>
- <b>Support Vector Machine</b>

The evaluation metrics will be:

- Accuracy: percentage of correct predictions
- Precision: Rate of correctly predicting toxic mushrooms
- Recall: Rate of correctly predicting edible mushrooms 

## <font color="#E34000"><b>Step 4: Conduct clustering analysis</b></font>

 Current plan is to use <b>k-modes</b> clustering. 



