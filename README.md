# FetalHealthPrediction

### Summary
Classification Problem
Accuracy: 93% - 96% (different cv methods)

Code File : 
https://github.com/LijiAlex/FetalHealthPrediction/blob/main/notebook/experiments.ipynb

Output File:
https://github.com/LijiAlex/FetalHealthPrediction/blob/main/notebook/output.csv

### Strategy

* Classification Problem
* Duplicate rows ignored since percentage is low.
* Feature Selection done with SelectKBest and score>150.
* Fine tuning done using GridSearchCV
* Features scaled using StandardScalar

### Model Creation
* Algorithms Used: LogisticRegression, GradientBoostingClassifier, RandomForestClassifier, KNeighboursClassifier

### Model Selection
1. Models created with all features and selected features.
2. Compared the scores and selected top two models.
3. Used GridSearchCV to fine tune these models.
4. Used KFoldCrossValidation to make sure final model is having best score.

