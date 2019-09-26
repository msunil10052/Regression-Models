# Regression Models

This is the Repository for Machine Learning and Deep Learning Models to predict a continuous-valued attribute associated with an object. The objective of case study is to compare various models with minimal feature engineering techniques.

Here we will address the problem using Linear Regression, Generalized Linear Models (ridge/lasso regression), Tree based algorithms, Ensemble Methods and Neural Network based Methods

## Problem Statement
Your client is the city council of Boston, MA.  The council shared with you the attached data set and a data dictionary. The Boston city council leadership is interested in understanding the drivers behind the value of houses in Boston and are looking for data-driven recommendations on how they can increase the value of housing.

## Data Description
This dataset contains information collected by the US Census Service concerning housing in the area of Boston Massachusetts. It was obtained from the StatLib archive (http://lib.stat.cmu.edu). The dataset has 506 cases and each of the 506 entries represents aggregate information about 14 features of homes from various suburbs located in Boston.

The data was originally published by Harrison, D. and Rubinfeld, D.L. `Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978. 

The 14 attributes are:

1. CRIM      - per capita crime rate by town
2. ZN        - proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS     - proportion of non-retail business acres per town
4. CHAS      - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX       - nitric oxides concentration (parts per 10 million)
6. RM        - average number of rooms per dwelling
7. AGE       - proportion of owner-occupied units built prior to 1940
8. DIS       - weighted distances to five Boston employment centres
9. RAD       - index of accessibility to radial highways
10. TAX      - full-value property-tax rate per \$10\,000
11. PTRATIO  - pupil-teacher ratio by town
12. B        - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13. LSTAT    - % lower status of the population
14. MEDV     - Median value of owner-occupied homes in \$1000's

## Code

The solution is split into Exploratory data analysis and Model Building. 

Exploratory data analysis results are stored in below notebook.

1. `Exploratory data analysis.ipynb`

Below are the notebooks for Models:

1. `Machine Learning - Model 1.ipynb` for Generalized Linear Models
2. `Deep Learning - Model 1.ipyb` for Keras based linear regression

You need to have [Jupyter Notebook](http://ipython.org/notebook.html) installed to run the file

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

Before running the file, first install all necessary dependencies:

```
pip3 install -r requirements.txt
```

## Run

To run the notebook, open terminal or command window, navigate to the top-level project directory `Regression-Models/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Exploratory data analysis.ipynb
```  
or
```bash
jupyter notebook Exploratory data analysis.ipynb
```

