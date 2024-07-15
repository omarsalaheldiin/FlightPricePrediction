# Flight Price Prediction Using Random Forest Regressor

## Overview
This project aims to predict flight prices using machine learning techniques, specifically employing a Random Forest Regressor model.
 The dataset used contains information about various flight attributes such as airline, source and destination cities, departure and arrival times, duration, and days left for booking.

## Dataset
- [The dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

The dataset consists of:
Features: Airline, source city, departure time, stops, arrival time, destination city, class, duration, days left.
Target: Price of the flight.

## Preprocessing
- Dropping Irrelevant columns (Unnamed: 0, flight).
- Encoding:
    - Binary: class (Economy, Business).
    - Factorization: stops (one, zero, two or more).
    - One-Hot: airline, source_city, departure_time, arrival_time, destination_city.

## Model Training
- Model: Random Forest Regressor.
- Training: Split data into training and testing sets (80/20 split).
- Performance: Achieved R2 score of 0.986 on test data.

## Libraries To run the notebook:
- pandas
- scikit-learn
- matplotlib
