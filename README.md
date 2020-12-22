# Optimized-Warehouse-Management-of-Perishable-Goods
Freshness of products and timeliness of delivery are two critical factors which have impact on customers in terminal delivery of perishable goods. This project investigates how to make a favourable inventory in the warehouse so that there is no wastage and shortage of perishable goods for a food delivery company. Thus, we develop functional machine learning model to forecast the need of goods for the next future time-periods with proper front-end.

Technology stack:
      
Front-end technologies include:
1.	HTML
2.	CSS
3.	JavaScript

Back-end technologies include:
1.	Python 3

Technology/Tools used:
1.	Jupyter notebook: for python programming.
2.	jQuery: cross-platform JavaScript library designed to simplify the client-side scripting of HTML.
3.	Bootstrap 3: front-end library for designing websites and web applications.
4.	IBM Cloud: for deployment.

Scope of work:
We defined the following steps to be followed to develop the functional ML model:

1.	Data collection: The respective dataset will be downloaded from the website (Kaggle etc.).

2.	Data Preparation: Pre-processing the data (replacing the missing values, standardization etc)

3.	Choose the model: 
We will fit the following regression algorithm:
●	Linear regression
●	Bayesian linear regression
●	Neural network regression
●	Decision forest regression
●	Boosted decisions tree regression
Use the SciKit learning (predefined package in python) to import regression models.

4.	Cross-validation and training the data: Split the dataset into training set (80%) and testing set (20%). Then select the label data and target data. After that train the model (using training set).

5.	Evaluate the model: Uses some metric or combination of metrics to "measure" objective performance of model (Mean square error etc).We selected the best regression model which gives least error and high accuracy.

6.	Parameter Tuning: Once the evaluation is done, to see if we can further improve the training in any possible ways to get better model.

7.	Predict the model: Finally, we predict the demand of goods for future time-periods. 
      Modules used in python:
1.	Pandas
2.	Numpy
3.	SciKit
4.	Matplot
5.	Pickle
6.	OS
   
Expose this model as a web service with the help of JavaScript.
Configure the application deployment using the Cloud Foundry Python runtime.
Deploy the created application on IBM cloud or run locally (using Docker).


