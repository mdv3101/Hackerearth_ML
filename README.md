# Hackerearth_ML
Codes of Hackerearth Machine Learning Competitions 
The model used in prediction is xgboost. Here i did not done parameter tuning.
The steps followed are as follows:
1. Load the data
2. Then check the datatypes
3. Then check any missing values
4. map the 'DetectedCamera' feature to suitable numerical values
5. Rename SignFacing(Target) to Target
6. Map 'Target' values to numerical values
7. Train the model
8. First i use Random Forest and then XGBoost. The accuracy of submission file is more in XGBoost, so i use that model for final prediction.
