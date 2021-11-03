---
layout: page
---
![alt-text-1](/assets/img/ED2.png "title") 

## <font color="#E34000"><b>Step 1: Data Preprocessing</b></font>
<p>
<font color="#E34000"><b>Dataset specifics</b></font>

![alt-text-1](/assets/img/Dataset.jpg "title") 

Above is a portion of how the dataset is set up, the <b>class</b> column being the dependent variable vector.
- Dataset taken from UCI Machine Learning Repository
- 8124 instances of mushroom data
- 48% poisonous, 52% nonpoisonous (balanced dataset)
- 22 attributes
- 23 features
</p>
<font color="#E34000"><b>Preprocessing requirements</b></font>

- Handle missing data of stalk-root feature using imputation or data discretization.
- Encode categorical data using one-hot encoding.
- Split data into training and test sets (starting with 80:20 training:testing split)
- Feature scaling using standardization

## <font color="#E34000"><b>Step 2: Train binary classifiers</b></font>
- <b>Random Forest</b>: starting value for the number of trees hyperparameter is 100
- <b>Logistic Regression</b>: no hyperparameters to set
- <b>K-Nearest Neighbors</b>: starting value for the k hyperparameter is 80
80 is the square root of the number of instances in the training set, assuming the 80:20 ratio. 


## <font color="#E34000"><b>Step 3: Evaluate classification models' performance</b></font>

- Confusion matrices for each binary classifier
- Accuracy rate determined from Cumulative Accuracy Profile for each binary classifier

## <font color="#E34000"><b>Step 4: Conduct clustering analysis</b></font>

- <b>k-means</b> clustering: implement the Elbow Method to find the number of clusters hyperparameter
- <b>Hierarchical</b> clustering: no hyperparameters to set


