# EDA FEATURE_EXTRACTOR MODEL

A python package to do EDA, feature selection and display the best hyperparameters for a pre-built classification model.

Useful for datasets with no NaNs or null values present.
Can be used for normal classification tasks, next update will work for Regression type problems and incorporate a sorted arrangement of variables.

before utilizing the package, ensure no Null or NaN values remain.

installing the package:
    pip install eda-fe-model==0.1.1

## Using the library
from eda_fe_model import package

package.EDA()
package.feature_extraction()
Use to_categorical from keras.utils
package.build_best_model()