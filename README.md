# predict_purchase
Here, we create models that compute the likelihood of a customer making a purchase, where the features are gender, salary and age.

The `logistic_regression.ipynb` notebook uses logistic regression. At the end of this notebook, the least relevant features (which in this case is gender) are determined by analyzing the weights and then discarded.

The `model_comparison_nogender.ipynb` notebook compares the performance of the following models: logistic regression, random forest, XGBoost and SVM. 
