---
layout: page
title: Method
---
### Step 1: Obtain dataset
- 8124 instances of mushroom data
- 48% poisonous, 52% nonpoisonous
- 22 attributes
- 23 features 

### Step 2: Data preprocessing

- Handling missing data (imputation) 
{: .box-note}
**Note:** Missing values are located in the stalk root feature and are denoted with a ? in the dataset.
- Encoding categorical data (one-hot encoding)
{: .box-note}
**Note:** All variables are categorical, as can be seen [here](https://sonikarichamodur.github.io/2021-10-14-obtaining_the_dataset/)
- Splitting data into training and test set (80:20)
- Feature scaling (standardization)

### Step 3: Train binary classifiers

- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

### Step 4: Evaluate classification models performance

- Confusion matrices for each binary classifier
![Alt text](/assets/img/Confusion Matrix.jpg)

### Step 5: Conduct clustering anlaysis

- k-means clustering

