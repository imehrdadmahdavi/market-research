## Predicting Housing Prices

### Description

Building and optimizing a machine learning model to predict housing prices statistical analysis sklearn cross validation grid search machine learning

### Install

This project implemented on **Python 3.7** and the following Python libraries installed:


- [Jupyter Notebook (IPython) 4.10.0](https://ipython.org/)
- [NumPy 1.16.4](http://www.numpy.org/)
- [Pandas 0.24.2](http://pandas.pydata.org/)
- [matplotlib 2.2.4](http://matplotlib.org/)
- [scikit-learn 0.17](http://scikit-learn.org/stable/)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

### Code

Template code is provided in the `predicting_housing_pricesg.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `predicting-housing-prices/` (that contains this README) and run one of the following commands:

```bash
ipython notebook predicting_housing_prices.ipynb
```  
or
```bash
jupyter notebook predicting_housing_prices.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
