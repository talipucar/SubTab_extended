
### Summary:

It is a well-known public dataset extracted from the 1994 Census database [1].
It includes the details such as education level and demographics to predict whether the income of a
person exceeds 50K/yr. The data consists of six continuous and eight categorical features. After
one-hot encoding of categorical features, there are total of 105 features.

**Train-Validation-Test Split:** Training and test sets are provided separately. 

**Features:** The dataset has 14 attributes consisting of 8 categorical and 6 continuous features. The rows with missing values are dropped, and categorical features are encoded using one-hot encoding.
Features are normalized by subtracting the mean and dividing by the standard deviation, both of
which are computed using training set.

**Class imbalance:** It is an imbalanced dataset, with only 25% of the samples being positive


Original dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/adult


### References:

1- Ron Kohavi. Scaling up the accuracy of naive-bayes classifiers: A decision-tree hybrid. In Kdd, volume 96, pages 202–207, 1996.


### License: 

Adult Income is under Open Data Commons Public Domain Dedication and License (PDDL).
