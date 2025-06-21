# Credit Card Default Classifier 

Supervised machine learning model for classifying if clients will default based on client features and transaction history.

## Preprocessing

EDA is performed and analysis is used for feature engineering.
Preprocessor transformer includes pipelines with StandardScaler, OHE, FunctionTransformer.

## Machine Learning Models

A baseline dummy classifer model is created based on the most frequent target value. 
LogisticRegression, KNN, SVM RBF, and RandomForestClassifier approaches are examined.

## Hyperparameter Optimization

Hyperparameter optimization is performed on models using GridSearchCV and RandomizedSearchCV.

## Feature Importance

Feature importances are examined with RFECV. 

## Testing the Model
The model is tested on classfication metrics and evaluated mainly on f1 score with considerations to precision and recall. 
