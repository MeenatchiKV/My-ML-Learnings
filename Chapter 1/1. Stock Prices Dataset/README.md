# LinearRegression
A Linear Regression performed on the stock prices data set available on Quandl - "WIKI/GOOGL".

To perform LinearRegression on the dataset - WIKI/GOOGL, the following python packages are required.

sklearn, quandl, pandas, math, numpy, matplotlib, datetime

Use the following commands to install the above packages.

    $ pip install sklearn quandl pandas numpy matplotlib
	
I have used Jupyter notebook 

	$ pip install jupyter
    
A linear regression on a set of data points is to find the best fit line.
A straight line that passes through most of the data points.
  which is in the for y = mx + b
  
Here x and y are the features and labels of the dataset respectively.

The file LinearRegression-StockPrice.ipynb runs on a jupyter notebook.

To convert the ipython file to a regular python file, use the following commands. 

    $ ipython nbconvert --to python LinearRegression-StockPrice.ipynb
    
You might need to install ipython inorder to convert .ipynb file to .py, so use the following command.

    $ pip install ipython
