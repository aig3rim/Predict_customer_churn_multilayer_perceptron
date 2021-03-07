# Predict_customer_churn_multilayer_perceptron

## Introduction
This is a source code for my Medium blog post on Predict Customer Churn with Neural Network.

### Motivation
As a data scientist, I quite often start solving a business problem with a simple and an easy to implement algorithm such as linear and logistic regressions.
In this notebook, I decided to try a different approach and apply sequential neural network, which is more complicated and difficult to explain to non-technical people. I think it is always fun to try different algorithms :-)

### Customer churn 
Customer churn is when a customer decides to stop using services, content, or products from a company. Reasons for customer churn can be various anf the most typical one are poor customer service, not finding enough value in a product or service, lack of customer loyalty and lack of communications.

### Data
I am using Telco customer churn dataset, which I downloaded from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California. It indicates which customers have left, stayed, or signed up for their service.

## Getting started
You need an installation of Python, plus the following libraries:

* numpy
* pandas
* matplotlib.pyplot
* seaborn
* sklearn
* keras

## Summary and key findings
* We trained an MLP model and got AUC for the test set=0.87, which can help to predict customers who are planning to churn
* Usually, ANNs take time to train a model, which can be difficult for a real-world situation. Therefore, it is better to start with a benchmark model like logistic regression and then, if a high accuracy is needed to train other more complicated models
