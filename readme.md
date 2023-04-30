# Neural Network Model - Fnal Report

## Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With my knowledge of machine learning and neural networks, I have used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organisations that have received funding from Alphabet Soup over the years.

I did the preprocessing of the dataset by removing unnecessary features. 

The data cleaning also included making bins, making dummy variables and scaling the data to get it ready for training and testing.

I used tensorflow keras model for my analysis.

'is_successfull' is the target variable

Feature variables are as follows:
NAME                      
APPLICATION_TYPE             
AFFILIATION                  
CLASSIFICATION               
USE_CASE                   
ORGANIZATION                 
STATUS                      
INCOME_AMT                  
SPECIAL_CONSIDERATIONS       
ASK_AMT                  
IS_SUCCESSFUL                 

I removed "EIN" as it didn't have any impact.

To increase the accuracy, I changed number of layers, neurons and epochs but the accuracy remained unchanged.

To start, I made 2 input layers with 6 neurons each.

Then I increased the layers and changed the activation function.

## Results

To further evaluate, I created a new jupyter notebook and brought back the NAME feature which had a significant impact on the accuracy increase.

## Summary

In this project, I have proved that the features have a significant impact on the accuracy of the model.