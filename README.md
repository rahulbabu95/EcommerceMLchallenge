# EcommerceMLchallenge

This Repository consists of the predictive model that was designed to predict the prices of products for a E-commerce company that was put out on HackerEarth. 

The dataset consisted of numerical variables of which some of them were skewed. After initial EDA, in the solution I came up with techniques such as square root and log tranformations to handle the skewness in variables. After featurizations, we started from simple models such as Decision Tree regressor, GLM regression models such as ridge regression and elastic regression. Finally we opted powerful sophiticated models such as Random Forests and GBDTs. Our final submission for the challenge was a RF model which received the 99.83 score (Mean Squared Log error was the metric used)  on the test data. 

For a brief about the problem statement: https://www.hackerearth.com/problem/machine-learning/predict-the-lowest-price-8-9ffabe00/ or refer Problem Statement.png in this repository. Train Data (train.csv in this repo) and Test Data have been added in the repository as the data is now not available in the website. I have added the final predictions obtained by my model in Results.csv .
