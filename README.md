# Yes-Bank-Stock-Closing-Price-Prediction
Supervised Machine Learning Project

In this project, we have tried to predict the possibility of a stock’s closing price of the month based on different factors. It was important to understand all the features ‘High’, ‘Open’, ‘Low’, ‘Date’ which were used for predicting closing price. it might help us make better decisions.

The process of our analysis has the following step: understanding the Datasets, Data preparation, and cleaning, analyzing the data, Modelling, and conclusion. We started with importing some of the useful python libraries like pandas, matplotlib, and seaborn needed for the project. After the basic operations of importing the dataset, seeing at the overview of the dataset we started with cleaning the dataset. We mostly focused on the null values, duplicates, and dropping unnecessary columns like ‘Date’, handling date in cleaning the dataset.

After that, we started Exploratory Data Analysis to analyze the data with the help of inbuilt seaborn and matplotlib libraries, plot various graphs including histogram, bar graph, scatterplot, boxplot, heatmap, line graph, etc. and got some of the following conclusions. We did univariate and bivariate analysis.
The data set contains 4 types of columns which is ‘High’, ‘Open’, ‘Low’ is the independent variable and ‘Close’ column was the dependent variable. Our dataset has 185 rows which were less so we have chanced to did not get accurate results. We have records from 2005 -to 2020.

We applied various types of regression algorithms (‘Linear regression’, ‘Lasso regression’, ‘Elasticnet’, ‘Ridge regression’, ‘KNN regression’, ‘XGBoost’) in our dataset and found the accuracy and evaluation metrics. 

##Here is the conclusion:
The target variable is highly dependent on input variables.

The accuracy for each model is more than 90% and all the metrics values are slightly similar.

There is an increase in the trend of Yes Bank's stock's ‘Close’ and ‘Open’ prices till 2018 then a sudden decrease.

Linear Regression has given the best results with the lowest MAE, MSE, RMSE, and MAPE scores.

Ridge regression shrunk the parameters to reduce complexity and multicollinearity but ended up affecting the evaluation metrics.

Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).

KNN and XGBoost regressor was so similar in all metrics but it’s worst as compared from left algorithm
