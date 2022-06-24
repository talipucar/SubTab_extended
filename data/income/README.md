
### Summary:

It is a well-known public dataset extracted from the 1994 Census database [1].
It includes the details such as education level and demographics to predict whether the income of a
person exceeds 50K/yr. The data consists of six continuous and eight categorical features. After
one-hot encoding of categorical features, there are total of 105 features.

**Train-Validation-Test Split:** Training and test sets are provided separately. 

**Features:** The dataset has 14 attributes consisting of 8 categorical and 6 continuous features. The rows with missing values are dropped, and categorical features are encoded using one-hot encoding.
Features are normalized by subtracting the mean and dividing by the standard deviation, both of
which are computed using training set.

The orders of the features in the pre-processed data are as following:

- One-hot encoded features [1-99]:

>'Private', 'Self-emp-not-inc', 'Self-emp-inc', 'Federal-gov', 'Local-gov', 'State-gov', 'Without-pay', 'Never-worked',

>'Bachelors', 'Some-college', '11th', 'HS-grad', 'Prof-school', 'Assoc-acdm', 'Assoc-voc', '9th', '7th-8th', '12th', 'Masters', '1st-4th', '10th', 'Doctorate', '5th-6th', 'Preschool',

>'Married-civ-spouse', 'Divorced', 'Never-married', 'Separated', 'Widowed', 'Married-spouse-absent', 'Married-AF-spouse',

>'Tech-support', 'Craft-repair', 'Other-service', 'Sales', 'Exec-managerial', 'Prof-specialty', 'Handlers-cleaners', 'Machine-op-inspct', 'Adm-clerical', 'Farming-fishing', 'Transport-moving', 'Priv-house-serv', 'Protective-serv', 'Armed-Forces',

>'Wife', 'Own-child', 'Husband', 'Not-in-family', 'Other-relative', 'Unmarried',

>'White', 'Asian-Pac-Islander', 'Amer-Indian-Eskimo', 'Other', 'Black',

>'Female', 'Male',

>'United-States', 'Cambodia', 'England', 'Puerto-Rico', 'Canada', 'Germany', 'Outlying-US(Guam-USVI-etc)', 'India', 'Japan', 'Greece', 'South', 'China','Cuba', 'Iran', 'Honduras', 'Philippines', 'Italy', 'Poland', 'Jamaica', 'Vietnam', 'Mexico', 'Portugal', 'Ireland', 'France', 'Dominican-Republic', 'Laos', 'Ecuador', 'Taiwan', 'Haiti', 'Columbia', 'Hungary', 'Guatemala', 'Nicaragua', 'Scotland', 'Thailand', 'Yugoslavia', 'El-Salvador', 'Trinadad&Tobago', 'Peru', 'Hong', 'Holand-Netherlands',
    
- Continous [100-105]:  

>'Age','Final-Weight','Education-Num','Capital-Gain','Capital-Loss','Hours-Per-Week'



**Class imbalance:** It is an imbalanced dataset, with only 25% of the samples being positive


Original dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/adult


### References:

1- Ron Kohavi. Scaling up the accuracy of naive-bayes classifiers: A decision-tree hybrid. In Kdd, volume 96, pages 202–207, 1996.


### License: 

Adult Income is under Open Data Commons Public Domain Dedication and License (PDDL).
