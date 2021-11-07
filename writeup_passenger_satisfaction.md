# Predicting of Airline Passenger Satisfaction using Classification Models

## Overview

This project worked on a dataset that contains an airline passenger satisfaction survey. The project aimed to build classification models to predict passenger satisfaction and identify which model is outperformed based on accuracy. We have trained our data on eight models which are: KNN models, Descion Tree model, Logistic regression model, Random forest model, Gradient boosting model, XGradient boosting model, Naive bayes model and Support vector machain model. The best accuracy among these algorithms is 95.93% % of Polynomial degree 2 with Random Forest Classifier.

## Goals

- Build a classification model to predict passenger satisfaction.
- Choose the model that give us the best accuracy.

## Methodology


1- Loading the dataset.

2- EDA (cleaning and visualizing the data).

3- Building different classification Models.

4- choosing the model based on given best accuracy to prediction.

## Dataset

We used a dataset of airline passenger satisfaction survey from https://www.kaggle.com.
- The dataset contains 129880 rows and 25 columns.


Our EDA steps :
- Handling null values.
- Dropped all duplicated and unneeded rows and columns
- Strip all columns name.
- Remove outliers .
- Converted categorical data into numeric.
- Numeric and categorical data visualization.

After cleaning the data set the rows became 116885 and columns are 28

### Dataset Columns:


- **Gender:** Gender of the passengers (Female, Male)
- **Customer Type:** The customer type (Loyal customer, disloyal customer)
- **Age:** The age of the passengers
- **Type of Travel:** Purpose of the flight of the passengers (Personal Travel, Business Travel)
- **Class:** Travel class in the plane of the passengers (Business, Eco, Eco Plus)
- **Flight distance:** The flight distance of this journey
- **Inflight wifi service:** Satisfaction level of the inflight wifi service (1-5)
- **Departure/Arrival time convenient:** Satisfaction level of Departure/Arrival time convenient
- **Ease of Online booking:** Satisfaction level of online booking
- **Gate location:** Satisfaction level of Gate location
- **Food and drink:** Satisfaction level of Food and drink
- **Online boarding:** Satisfaction level of online boarding
- **Seat comfort:** Satisfaction level of Seat comfort
- **Inflight entertainment:** Satisfaction level of inflight entertainment
- **On-board service:** Satisfaction level of On-board service
- **Leg room service:** Satisfaction level of Leg room service
- **Baggage handling:** Satisfaction level of baggage handling
- **Check-in service:** Satisfaction level of Check-in service
- **Inflight service:** Satisfaction level of inflight service
- **Cleanliness:** Satisfaction level of Cleanliness
- **Departure Delay in Minutes:** Minutes delayed when departure
- **Arrival Delay in Minutes:** Minutes delayed when Arrival

**Target:**
- **Satisfaction:** Airline satisfaction level(Satisfaction, neutral or dissatisfaction)








## Classification Algorithms:

**On this dataset we used different methods of classification :**

- KNN models.
- Descion Tree model.
- Logistic regression model.
- Random forest model.
- Gradient boosting model.
- XGradient boosting model.
- Naive bayes model (NB).
- Support vector machain model (SVM).

## Tools

- Python
- Jupyter notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Sklean

