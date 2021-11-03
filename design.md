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

- Handle <u>missing data</u> of stalk-root feature using imputation or data discretization.
- Encode <u>categorical data</u> using one-hot encoding.
- <u>Split data</u> into training and test sets (starting with 80:20 training:testing split)
- Feature scaling using standardization

## <font color="#E34000"><b>Step 2: Train binary classifiers</b></font>
- <font color="#4980e6"><b>Random Forest</b></font>: starting value for the number of trees hyperparameter is 100
- <font color="#4980e6"><b>Logistic Regression</b></font>: no hyperparameters to set
- <font color="#4980e6"><b>K-Nearest Neighbors</b></font>: starting value for the k hyperparameter is 80
80 is the square root of the number of instances in the training set, assuming the 80:20 ratio. 


## <font color="#E34000"><b>Step 3: Evaluate classification models' performance</b></font>

- Confusion matrices for each binary classifier
- Accuracy rate determined from Cumulative Accuracy Profile for each binary classifier

## <font color="#E34000"><b>Step 4: Conduct clustering analysis</b></font>

- <font color="#4980e6"><b>k-means</b></font> clustering: implement the Elbow Method to find the number of clusters hyperparameter
- <font color="#4980e6"><b>Hierarchical</b></font> clustering: no hyperparameters to set


