# Heart Disease Prediction 
## Project for Udacity Data Scientist Nanodegree
![](https://upload.wikimedia.org/wikipedia/commons/3/3b/Udacity_logo.png)

## Installations
```
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.metrics import accuracy_score
from sklearn.linear_model import LogisticRegression
import seaborn as sns
%matplotlib inline
```
[Panda](https://en.wikipedia.org/wiki/Pandas_(software)) is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. <br>
[Matplotlib](https://en.wikipedia.org/wiki/Matplotlib) is a plotting library used to visualize our results. <br>
[SKlearn](https://scikit-learn.org/stable/) is used for predictive data analysis. <br>
[Seaborn](https://seaborn.pydata.org/) is used to visualize the correlation of our features.
## Motivation
As a first project for my Data Science Nanodegree at [Udacity](https://www.udacity.com/school-of-data-science) I am asked to choose a data set and analyze, model and visualize it. For my project I chose a [Heart Failure Prediction Dataset](https://www.kaggle.com/fedesoriano/heart-failure-prediction). <br>
It contains mostly medical data which can be used for a early detection of a heart disease.

## Description
The used model can give you a predicition based on your input and used features and gives you the accuracy of said prediction as well.
As a input you need to define your Feature Matrix with the features you want to use, e.g. 

X = df[["MaxHR", "Oldpeak"]]#Feature Matrix


## Licensing, Authors, Acknowledgements
Acknowledgements<br>
Credits to Jason Brownlee for his [fitting model](https://machinelearningmastery.com/how-to-connect-model-input-data-with-predictions-for-machine-learning/)
