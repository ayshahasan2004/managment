## Machine Learning–Based Software Effort Estimation

This project applies machine learning models to predict software development effort using a dataset of 81 historical projects.  
We compare multiple regression models including Linear Regression, KNN, SVR, and Random Forest against a baseline estimator.  

To ensure reliable results, we use nested cross-validation (10 outer folds, 5 inner folds) with hyperparameter tuning.  
Models are evaluated using standard metrics (MAE, RMSE, R²) and effort-specific metrics (MMRE, PRED(25)).  

Results show that Random Forest achieves the best overall performance, capturing nonlinear relationships effectively.  
The predictions are further interpreted for real-world project management decisions such as budgeting, scheduling, and staffing.  

This project highlights how data-driven estimation can improve planning accuracy and reduce cost and schedule risks.# managment
