30 / 10 / 2023

# Price-Forecast-System-Based-On-Retail-Data
You can see the database from this connection which we will use for this project. 
https://www.kaggle.com/datasets/sakhawatalilarik/adidas-us-sales-data

Project Name: Adidas Product Price Estimation.

Project Purpose:  To develop a machine learning model to predict future prices of Adidas products in the United States.

Project Goals:  Improving the accuracy of the model to be over 90%.

06 / 11 / 2023

Project scope:
Collecting and pre-processing the data to be trained on the model.
Creating new features for the model or improving existing features.
Evaluating different machine learning models and choosing the best performing model.
Training the model and evaluating its accuracy.

Project Risks:
Data is missing or inconsistent.
The accuracy of the model is lower than the targeted value.

Project Updates:
To inform those who follow the project about updates every week. 

Updates of 27 / 11 / 2023

A New dataset link which we will be using on our project:

https://1drv.ms/x/s!Aplzq74_6bixsSxfgWkHSNQ05N4-?e=8DAtm1

As we begin the code-containing part of the project, we load our libraries.

Then, we turn our data set into a dataframe so that we can use it in Google Collaborate.

Since our data in our project belongs to the United States of America and we can make accurate future predictions, 
we turn the inflation rate determined by state into a dataframe to add it to our target value as a result of noise.

We use numpy arrays to process our State and InflationRate (IR) values from our dataset containing our inflation data.

We carry out the normalization process in order to prevent deviation and possible misdirection in our inflation values.


Then, in order to use the Linear Regression model, which is a machine learning method with which we can make our price prediction in the most ideal way,
we take various attributes from our data set as numpy arrays to use.

We apply our normalization processes to reduce misdirection in this data.

Then, we match the states in our inflation data set with their inflation values, so we can change shoe prices depending on how much inflation there is in each state.

We make price changes in our target value according to inflation values in the states.
