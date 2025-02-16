# Flight Predictions

## **Project Overview**
This Jupyter Notebook focuses on analyzing flight data and preparing it for predictive modeling. The dataset contains flight details, including journey dates, total stops, departure and arrival times, and other travel-related features. The goal is to clean and preprocess the data for machine learning applications, such as flight price prediction.

## **Dataset Overview**
The dataset consists of:
- **Flight Details**: Airline, source, destination, route, and additional flight attributes.
- **Date & Time Information**: Journey date, departure time, arrival time, and total travel duration.
- **Pricing Information**: Ticket prices (available in training data only).
- **Test Data**: Includes similar attributes but without ticket price labels.

##  **Objectives**
- Load and preprocess flight data from Excel files.
- Extract useful features from date and time columns.
- Map categorical variables to numerical values.

- ##  **Key Steps in the Notebook**

### 1 **Data Loading**
- Read flight data from `Data_Train.xlsx` and `Test_set.xlsx`.
- Merge datasets for a unified analysis.

### 2️ **Data Preprocessing**
- Convert `Date_of_Journey` into `Date`, `Month`, and `Year`.
- Extract `Departure Hour` and `Departure Minute` from `Dep_Time`.
- Extract `Arrival Hour` and `Arrival Minute` from `Arrival_Time`.
- Drop redundant columns after feature extraction.

### 3️ **Feature Engineering**
- Map categorical values in `Total_Stops` to numeric values.
- Extract `Duration Hours` from `Duration` column.

