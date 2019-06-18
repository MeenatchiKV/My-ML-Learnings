# CHAPTER 1

This chapter introduces you to Linear Regression, a basic and one of the most powerful model.

Linear Regression is usually performed on a continuous data.
Say, the fluctuation of stock prices, web traffic on any particular website, predicting the real-estate prices, etc.

There are other types of regressions like - Poisson regression and Logistic regression.
The poisson Regression is used to predict count values, while Logistics Regression is performed on categorical values.
Now Let us continue with linear regression.

## Linear Regression

Any Machine Learning model deals with two parameters - Features and Labels.
Here, features represents the columns or the attributes and labels represents the class or the output value.

Consider the following stock prices dataset. The dataset is available in Quandl.com website and can download the dataset from quandl package available for python.

Given date, open value, close value, volume and other parameters, our goal is to find the closing value of the stock in the near future.

![image](https://user-images.githubusercontent.com/26254731/59670186-1ce1c680-91d9-11e9-860b-a2b25477c61f.png)

Here, Date, Adj .Close, HL_PCT, PCT_change, Adj. Volume are features or the parameters we take in to train the model.

This model will predict the label. In this case, the task is to predict the closing value of the stock.

The values to be predicted are continuous i.e., they lie between a range of values. So, Linear regression is possible in this case.

We also have to visually see the data to ensure that they are linear. The following image shows the above dataset in a graph.

![image](https://user-images.githubusercontent.com/26254731/59670817-2d467100-91da-11e9-918b-8759a23ef8f9.png)

As the data seems to grow exponentially, we can now start applying Linear Regression to the given dataset.

Now, Lets get into the coding part. [StockPrice-LR]










[StockPrice-LR]: https://github.com/MeenatchiKV/LearnML/blob/master/Chapter%201/1.%20Stock%20Prices%20Dataset/LinearRegression-StockPrice.ipynb


