# Kaggle 2020 fall
Yu Yingyi
rachelyingyi@gmail.com

In general, we use XGBoost (eXtreme Gradient Boosting) to build the model and fit the Road Speed Data.
1)We import libraries including numpy, pandas, matplotlib, holidays, datetime to preprocess data, and import packages including xgboost, sklearn for model setting, validation and hyper parameters tuning.
2)After loading train data and test data, we firstly examine the statistics of the dataset and check if any missing values.
3)We define a function called create_features() to extract the time information from the dataset. 
4)We use sklearn train_test_split function to obtain 80/20 training/validation dataset.
5)Then we build XGBoost model to fit the training data, and obtain predictions for both training data and validation data. We calculate MSE of training set and validation set.
6)We use sklearn GridSearch function to tune parameters and then update model with new parameters. We re-calculate the predictions and MSE of both training data and validation data.
7)After preprocessing test data, we obtain the prediction results of test data, by using the trained model.

This github repo contains 1)train.csv, test.csv, sampleSubmission.csv and final_result.csv; 2)python notebook for coding; 3)README 

 
