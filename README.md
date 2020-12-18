# Kaggle-house-prices-tutorial---Linear-regession-and-DNNs

In this tutorial we look at the boston house prices competition on kaggle:

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/description

The train set consists of approximately 1400 house properties (features) and the corresponding salePrice. The train set consists of approximately 1400 house properties (features) without the corresponding salePrice. There are 79 features, both continuous and categorical. The aim is use the train set to build a model to predict the salePrice given the features. Models are then applied to the test set, and the predicted salePrices are submitted to Kaggle. Kaggle evaluates the submissions by comparing the predicted values with the observed sales price (which are hidden) using the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted values and the logarithm of the observed sales prices.

We will use both linear regression and DNNs to make predictions. We aim for code robustness and clarity for easy experimentation:

  - Part 7 contains the full linear regression code.
  - Part 9 contains the full DNN regression code.
  
The remaining parts introduce the different parts of the linear and DNN code, explaining intuitively what we do and why:
  
  - Part 0 contains basic data preprocessing.
  - Parts 1-5 discusses different types of simple feature engineering.
  - Part 6 discusses different types of compensation for outlier data.
  - Part 8 discusses how to implement DNNs using tensorflow.
 
 
We use our code to generate predictions, submit our predictions to kaggle, and give the resulting scores. We do this multiple times, experimenting with the effects of the different types of feature engineering and compensation for outlier data, and generate multiple scores for comparison.
