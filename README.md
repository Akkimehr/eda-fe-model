# EDA FEATURE_EXTRACTOR MODEL

A python package to do EDA, feature selection and display the best hyperparameters for a pre-built classification model.

Useful for datasets with no NaNs or null values present.

After the data massaging, call EDA() for normalizing/standardizing the numerical columns and OHE/label Encoding for categorical columns.

Call feature_extraction() for selecting the best features in a dataset to pass on to a model. You can skip the function too.

Call build_best_model() to return a list of hyperparameters seacrhed and the best score achieved.