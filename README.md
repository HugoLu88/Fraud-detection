# Fraud-detection

## pass rate

The first part of the jupyter notebook outlines some basic data cleaning, feature engineering and then feature selection techniques.

These are then applied to labelled data using a simple logistic regression (including standard errors) to assess the viability of the model and the quality of the data


## fraud detection

The second part of the jupyter notebook also outlines some basic data cleaning, feature engineering and then feature selection techniques.

These are then applied to partially labelled data using a simple bagged decision tree classifier.

There is an inherent problem with the data in this part since not all items are labelled. While the decision tree classifier will therefore be biased, it is assumed there is a small but significant number of "frauds" that are labelled as "non frauds". Therefore, using a decision tree that essentially "casts a wide net" should in theory catch some of these (provided they are similar in terms of feature to correctly labelled "frauds").

TO ADD: clustering / unsupervised methods.
