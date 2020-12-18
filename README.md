# Kaggle-house-prices-tutorial---Linear-regession-and-DNNs

In this tutorial we look at the boston house prices competition on kaggle:

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/description

The train set consists of approximately 1400 house properties (features) and the corresponding salePrice. The train set consists of approximately 1400 house properties (features) without the corresponding salePrice. There are 79 features, both continuous and categorical. The aim is use the train set to build a model to predict the salePrice given the features. Models are then applied to the test set, and the predicted salePrices are submitted to Kaggle. Kaggle evaluates the submissions by comparing the predicted values with the observed sales price (which are hidden) using the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted values and the logarithm of the observed sales prices.

We will use both linear regression and DNNs to make predictions. In both cases we will create initial rough models, submit our predictions, and give our score. We will then make alterations to the features (feature engineering), explain intuitively why we are making such changes, and generate new scores for comparison.

We aim for code robustness and clarity for easy experimentation.
