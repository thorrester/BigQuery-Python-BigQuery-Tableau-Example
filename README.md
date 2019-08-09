# BigQuery --> Python --> ensemble learning --> BigQuery --> Tableau Tutorial notebook to Predict Item Backorder

This repository is part of an ongoing series of tutorials to teach interested individuals simple examples of end-to-end machine learning projects. Each notebook is a different part of the end-to-end project. The focus of this series of notebooks is to predict item backorder.

The notebooks and their descriptions are as follows:
1. Python and GBQ - The 1st notebook shows how to connect to GBQ via python. In this notebook we generate fake data, make it noisey, and upload it to GBQ via 2 methods.
2. The 2nd notebook uses python to perform a SQL query to pull in data from GBQ. The data is then passed through a logistic regression model following oversampling of the uneven distribution in our data.
3. The 3rd notebook shows how we can use a random forest with a simple random search to predict item backorder.
4. In the 4th notebook we use keras and tensorflow to create a deep neural network in order to predict item backorder.
5. In the 5th notebook we build on the previous notebook and create an ensemble model. In the 1st layer of the model, we train a logistic regression, random forest, and deep neural network on our training data. Predicitons are made with a dev set of data and weighted based on their accuracy. In the 2nd layer of the ensemble model, weighted dev predictions are fed into another deep neural network. This notebook also introduces classes.

Future notebooks in this series will focus on sending new backorder predictions to GBQ, which will then be reported in Tableau.

## Getting Started

All of the notebooks list the dependencies you will need for the notebooks. Currenlty, the notebooks are run in a conda venv with python 3.6.8, Tensorflow 1.11, and Keras 2.24


