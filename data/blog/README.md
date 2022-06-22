
### Summary:

**Please note that BlogFeedback data is attached as zip file in the release due to its file size. So please check out the release.**

The data originates from blog posts, and is originally used for regression task of
predicting the number of comments in the upcoming 24 hours. In this work, it is used for a binary classification task of predicting whether there is a comment for a post or not.There are 280 integer and real valued features, and separate training and test datasets are provided.

**Train-Validation-Test Split:** The original dataset includes one training set, and 60 small test sets.
We combined all the test sets into one test set. We split training set to training and validation using
80-20% split to search for hyper-parameters. We trained the final model using all of the training set.

**Features:** It includes 281 variables consisting of 280 features and 1 target variable indicating the
number of comments a blog post received in the next 24 hours relative to the basetime. We converted
the target (the last column in the dataset) to a binary variable, in which 0/1 indicates whether the blog
post received any comments. We used min-max scaling to normalize the features.

**Class imbalance:** ∼ 36% of the samples are positive in training set while it is ∼ 30% in the test set.



Original dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/BlogFeedback


### References:

Krisztian Buza. Feedback prediction for blogs. In Data analysis, machine learning and
knowledge discovery, pages 145–152. Springer, 2014.

### License: 

BlogFeedback is under Open Data Commons Public Domain Dedication and License (PDDL).