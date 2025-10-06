# umc-301-kaggle-competition-1
Code for Kaggle Competition 1 for UMC 301 

**final-submission** contains code for the highest scoring submissions.\

Scores for the best submission:\
Private Score: 0.58731\
Public Score: 0.57235

- Simple Imputation is performed for missing values.\
- The highest scoring submission has an ensemble of 20 xgboosts each initialized with different seeds in range(100, 120).\
- Other attempts include ensembles of 20 xgboosts with 20 random seeds, 10 xgboosts with different seeds and an ensemble with 3 xgboosts with different seeds and a catboost classifier model.

**other-things-tried** contains other attempts made including
- Initial attempts with 1 xgboost model 
- Tranforming features
- KNN Imputation for handling missing values
- Random Forest Classifier
- Bagged Catboost model
- Imbalance handling
- Light GBM
- Ensembles of catboost and lightgbm
