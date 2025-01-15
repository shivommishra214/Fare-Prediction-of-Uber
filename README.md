# Uber Fare Prediction Project

## **Description**
This project focuses on predicting fare prices for Uber's future transactions. As the world's largest taxi company, Uber delivers services to millions of customers daily, making accurate fare prediction crucial for better data management and new business strategies.

### **Dataset Fields**
The dataset contains the following fields:

- **key**: A unique identifier for each trip
- **fare_amount**: The cost of each trip in USD
- **pickup_datetime**: Date and time when the meter was engaged
- **passenger_count**: The number of passengers in the vehicle (driver-entered value)
- **pickup_longitude**: Longitude where the meter was engaged
- **pickup_latitude**: Latitude where the meter was engaged
- **dropoff_longitude**: Longitude where the meter was disengaged
- **dropoff_latitude**: Latitude where the meter was disengaged

### **Acknowledgment**
The dataset is provided by upGrad.

---

## **Objective**
1. Understand the dataset and perform cleanup (if required).
2. Build regression models to predict Uber ride fare prices.
3. Evaluate the models and compare their respective scores such as R², RMSE, etc.

---

## **Strategic Plan of Action**
To address the problem statement effectively, the following steps were taken:

1. **Data Exploration**
2. **Exploratory Data Analysis (EDA)**
3. **Data Pre-processing**
4. **Data Manipulation**
5. **Feature Selection/Extraction**
6. **Predictive Modelling**

---

## **Project Outcomes & Conclusions**

1. The dataset initially contained 2 million samples. After preprocessing, 18.4% of the samples were removed.
2. Visualizing data distributions and relationships provided valuable insights into the feature set.
3. High multicollinearity among features was addressed using the Variance Inflation Factor (VIF) technique during feature extraction.
4. Testing multiple algorithms with default hyperparameters provided insights into their performance on this specific dataset.
5. Polynomial Regression (Order-5) emerged as the best model for this task. However, multiple regression algorithms also demonstrated competitive performance and generalizability.

---

### **Note**
This project not only highlights the importance of accurate fare prediction but also serves as a comprehensive guide to building and evaluating predictive models efficiently.
