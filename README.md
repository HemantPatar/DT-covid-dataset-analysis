# https://nbviewer.jupyter.org/github/HemantPatar/covid-dataset-analysis/blob/main/DT_proj_corona.ipynb
# covid-dataset-analysis

Covid fatality prediction.

Data set size 48316 rows × 5 columns.

Data cleaning & data visualization for model training.

Seprating input and output from dataset.

Standardisation of input & output dataset is done using StandardScaler.

Function created for Train test split.
Function created for cross val score.

Dimensionality reduction done using PCA and variance.

Use(DecisionTreeRegressor,random forest regressor,KNN regressor,SVM regressor)

DecisionTreeRegressor 
find max r2 score for DecisionTreeRegressor

random forest regressor find best parameters (n_estimators) using GridSearchCV 
find max r2 score for random forest regressor

KNN regressor find best parameters (n_neighbors) using GridSearchCV  
find max r2 score for KNN

SVM regressor find best parameters (kernel, C) using GridSearchCV 
find max r2 score for SVM

Find Mean r2 score for DecisionTreeRegressor,random forest regressor,KNN regressor,SVM regressor

Find RMSE and r2 score for SVM and random forest regressor

Use (random forest regressor)

Save model (pickle).
