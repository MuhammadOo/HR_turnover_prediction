# HR_turnover_prediction
You are data scientist working in HR Department. Based on employee statistics, you
have to build Machine Learning model which will predict employee turnover by applying the following
steps:
1. Split data into train and test sets using seed=123 within h2o framework;
2. Build classification model with h2o.automl();
3. Find threshold by max f1 score;
4. Extract confusion matrix in tibble format;
5. Calculate AUC score both for train and test sets;
6. Check overfitting.
Note: dataset name is “HR_turnover.csv”, predicted variable name is “left”
