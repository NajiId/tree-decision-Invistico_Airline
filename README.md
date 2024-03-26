# User Satisfaction Prediction with Decision Trees

This repository contains Python code for predicting user satisfaction using decision tree classifiers. The dataset used in this analysis is "Invistico Airline Customer Satisfaction Dataset".

## Prerequisites

Make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Install the required libraries:

2. Run the Jupyter Notebook or Python script to see the analysis and predictions.

## Contents

- `User_Satisfaction_Prediction.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and feature importance analysis.
- `requirements.txt`: File containing the required libraries for this project.
- `Invistico_Airline.csv`: Dataset used for analysis.

## Dataset

The dataset contains the following columns:

- satisfaction
- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- Seat comfort
- Departure/Arrival time convenient
- Food and drink
- Gate location
- Inflight wifi service
- Inflight entertainment
- Online support
- Ease of Online booking
- On-board service
- Leg room service
- Baggage handling
- Checkin service
- Cleanliness
- Online boarding
- Departure Delay in Minutes
- Arrival Delay in Minutes

## Results

The decision tree classifier achieved the following performance metrics on the test set:

- Accuracy: 93.54%
- Precision: 94.29%
- Recall: 93.90%
- F1 Score: 94.09%

Tuning the decision tree model improved the F1 score to 94.54%. The most important features identified for predicting user satisfaction are 'Inflight entertainment', 'Seat comfort', and 'Ease of Online booking'.

Feel free to explore the notebook for a detailed analysis and visualization of the results.

**Note:** This README provides an overview of the project. For detailed code implementation and analysis, refer to the Jupyter Notebook.
