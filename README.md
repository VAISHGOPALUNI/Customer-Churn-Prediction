# Customer-Churn-Prediction
Understanding a problem and a final goal
It’s important to understand what insights one needs to get from the analysis. In short, you must decide what question to ask and consequently what type of machine learning problem to solve: classification or regression. Sounds complicated, but bear with us.

Classification. The goal of classification is to determine to which class or category a data point (customer in our case) belongs to. For classification problems, data scientists would use historical data with predefined target variables AKA labels (churner/non-churner) – answers that need to be predicted – to train an algorithm. With classification, businesses can answer the following questions:

Will this customer churn or not?
Will a customer renew their subscription?
Will a user downgrade a pricing plan?
Are there any signs of unusual customer behavior?
We used Python libraries for the analysis of our dataset as well as for training the machine learning models. To import the dataset we used the Pandas library. For visualizing the dataset we used Searborn library and finally to train machine learning algorithms we used Scikit learn library.

The following script imports the libraries that we are going to use to preprocess and analyze our data.

import pandas as pd

import numpy as np

import seaborn as sns

![Screenshot (753)](https://user-images.githubusercontent.com/42315342/88403371-16654b80-cdea-11ea-8779-6152c9011f08.png)
