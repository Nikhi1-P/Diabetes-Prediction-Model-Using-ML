# Diabetes-Prediction-Model-Using-ML



In this project I have gathered the data from Kaggle website in the form of csv file. With the help of python pandas I have imported the data into python dataframe, and with the help of numpy module I have cleaned the data and the data was ready for pre-processing and model selection. The dataset has been split into two datasets namely training dataset and testing dataset. With the help of training dataset the classification models are trained and with the testing data set the accuracy has been tested for all the classification models with the help of pipeline module. Random forest model has produced highest accuracy among them. So I have created a joblib model using random forest. So in the future when I have to test for new data I don’t have to run the whole project again, just the joblib model will provide me the predicted data.
