# Titanic Kaggle Challenge

This is a dataset that was on the site kaggle.com. It was presented as a part of educational data science contest. I was given a set of parameters on the passangeres aboard the titanic, and I was supposed to predict whether they will survive the sinkage or not. In order to do so, I have used python libraries: Numpy, Pandas, Seaborn, and scikit-learn package. 
[See the challenge](https://www.kaggle.com/c/titanic)

## Prerequisites

I needed to install [Jupyter Notebook](https://jupyter.org/) and [Python 3.6 or higher](https://www.python.org/). I have also used the following libraries:
1. [Numpy](https://numpy.org/) - Library which makes faster mathematical calculations, espacially when it comes to linear algebra.
2. [Pandas](https://pandas.pydata.org/) - Library for data manipulation and analysis.
3. [matplotlib](https://matplotlib.org/index.html) - Used to plotting data in Python.
4. [seaborn](https://seaborn.pydata.org/) - Used on top of matplotlib to have nicer and easier-defined plots.
5. [scikit-learn](https://scikit-learn.org/) - Free software machine learning library which contains implementations to most known algorithms.

## Files

### train.csv

This is the dataset used for training the algorithm. It contains classified samples so that I could use supervised learning algorithms.

### test.csv

This is the dataset on which I was supposed to generate predictions. Afterwards, I would submit these results to kaggle, and it would give me an accuracy rate accordingly.

### Data Exploration.ipynb

Jupyter Notebook which is built in order to do data exploration based on the train.csv dataset, and to define the feature engineering needed before initiating the algorithms.

### Logistic Regression.ipynb

Jupyter Notebook which contains my own version of logistic regression in comparison to scikit-learn's offering. 

### Support Vector Machine.ipynb

Jupyter Notebook which contains several types of SVM's.

### Test Pipeline.ipynb

Given the selected algorithm, this notebook contains pipeline for submitting the predictions for test.csv dataset.
