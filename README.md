# Annual-Rainfall-Prediction
This predicts annual rainfall in India, the dataset is from year 1901-2015 and Multi Linear Regression Model is used for prediction.
Dataset can be downloaded from the link https://data.gov.in/resources/subdivision-wise-rainfall-and-its-departure-1901-2015.
I made this project because in India farmers are dependent on rain for their crops.
Moreover, it can be used with forecast of Indian Meterological Department in prediction of rainfall.
It can help to cope up with natural disasters like flood or drought in making prior arrangement to cope up with calamities.
I first uploaded dataset with help of pandas library used for mathematical operations converting dataset to large multidimensional array.
Then I removed all the null values from the given dataset with average values so it cannot create problem.
After Data preprocessing I analyzed data with the help of matplotlib and seaborn libraries making the graphs b/w variables.
Using numpy libraries I worked with dataset and seprated training and testing data with sklearn.train_test_split module.
Then I applied Multi-Linear Regression algorithm to get the actual prediction.
For performance, I checked the root_mean_squared_error, mean_squared_error and r2_score.
r2_score was 0.98 which is a good prediction since it varies from least 0.0 to best 1.0
Then in the last I drew a graph b/w actual and predicted values which I tested to check how data varied during prediction.
