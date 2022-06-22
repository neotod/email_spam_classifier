# Email Spam Classifier

This is an exercise form the book Hands on ML.
Using Apache Spam assassin Dataset: [link_to_dataset](https://spamassassin.apache.org/old/publiccorpus/)

I written Data cleaning/prepration stage/functions by myself using packages including `nltk`, `re` for regex, etc.

Used Classification Algorithms are: `svm`, `random_forest`, `logistic_regression` and `desicion_tree`.

By ploting scores resulted form **K-Fold cross validation**, It's obvious from the scores dist plot that `Random forest` scored almost 1 at most of the predictions.