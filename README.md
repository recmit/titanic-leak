# The Titanic has a Leak

We explore a source of data leakage in the popular [Titanic competition](https://www.kaggle.com/c/titanic) on Kaggle: Passengers traveling together have similar survival outcomes and this correlation can be used to make predictions for the test set in a way that wouldn't be possible "in reality". To prevent the leakage we implement a "leak-proof" cross-validation. We compare the accuracy of an XGBoost classifier to various baselines to investigate which role, if any, the leakage is playing in the predictions of our classifier.

This [blog post](https://david-recio.com/2022/04/11/titanic-leak.html) is a more reader friendly version of the notebook.

Let me know if you have any thoughts on this notebook!
