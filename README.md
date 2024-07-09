# NYC Taxi Trip Duration Prediction using Machine Learning

**Introduction:**

Predicting taxi trip durations is a significant challenge with practical implications for urban planning, traffic management, and customer satisfaction. By leveraging machine learning techniques, we can create models that accurately estimate the duration of taxi trips based on historical trip data. This project focuses on using the NYC taxi trip duration dataset to develop a predictive model that can provide reliable trip duration estimates, thereby helping taxi companies optimize their operations and improve service quality.

**Problem Statement:**

The goal of this project is to develop a machine learning model that accurately predicts the duration of taxi trips in New York City. Using features such as trip start and end times, pickup and dropoff locations, passenger count, and vendor information, the model aims to capture the underlying patterns influencing trip durations.

**Dataset:**

The dataset used for this project 7,29,322has records and includes the following variables:

• id: A unique identifier for each trip

• vendor_id: A code indicating the provider associated with the trip record

• pickup_datetime: Date and time when the meter was engaged

• dropoff_datetime: Date and time when the meter was disengaged

• passenger_count: The number of passengers in the vehicle (driver entered value)

• pickup_longitude: The longitude where the meter was engaged

• pickup_latitude: The latitude where the meter was engaged

• dropoff_longitude: The longitude where the meter was disengaged

• dropoff_latitude: The latitude where the meter was disengaged

• store_and_fwd_flag: Indicates whether the trip record was held in vehicle memory before sending to the vendor due to lack of connection to the server (Y=store and forward; N=not a store and forward trip)

• trip_duration: Duration of the trip in seconds (target variable)

**Project Description:**

• Performed in-depth exploration of the NYC taxi dataset, identifying key patterns and relationships to understand factors influencing trip durations.

• Developed Machine Learning models such as Linear Regression and Decision Tree to predict taxi trip durations.

• Performed Cross Validation to improve the model performance

• Analyzed and compared the performance of different models to determine the most efficient one for predicting NYC Taxi-Trip Duration

**Observation:**

• Achieved an Root Mean Square Error (RMSE) of 0.42 with the Decision Tree Model.

• Decision Tree Model performs better when compared to Linear Regression Model due to it's ability to capture non-linear relationships and interactions between features in the data, which are inherently handled by the tree structure of the model.

**Skills:** Feature Engineering · Linear Regression · Decision Tree · Exploratory Data Analysis · Machine Learning
