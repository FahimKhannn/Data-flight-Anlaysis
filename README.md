
# Flight Data Analysis Project (1999-2008)

## Overview
This project involves the analysis of commercial flight data from 1999 to 2008 to uncover trends and patterns in flight delays and predict diverted flights. The analysis was conducted using Python, R, and SQL.
Flight data was retrieved from Havard Database : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

## Objectives
- Analyze flight delay patterns to identify best times and days of the week to minimise delays each year
- Analyze whether older planes led to a higher probability of flights being delayed
- Predict diverted flights using logistic regression using features from the dataset like departure date, the scheduled departure and arrival times, the coordinates and distance between departure
  and planned arrival airports, and the carrier


## Technologies Used
- **Python (Jupyter notebook) **: Data exploration, machine learning.
- **R**: Data exploration, machine learning.
- **SQL**: Data extraction, cleaning and data manipulation

## Key Contributions
### Data Preparation
- Extracted and cleaned flight data from 1999 to 2008 using SQL.
- Created a column named "significant delay" to identify flights with arrival and departure delays greater than 15 minutes.

### Exploratory Data Analysis (EDA)
- Utilized Python and R for initial data exploration, visualizing delay distributions, and identifying outliers.
- Conducted detailed statistical analysis to understand the impact of different factors on flight delays.

### Machine Learning
- Implemented logistic regression models to predict diverted flights.
- Trained and evaluated models, achieving high accuracy in predictions.
- Utilized AUC/ROC , Precison, Recall, F1, Support scores to evaluate problems
- Used oversampling techqniues to give more precedence to minority class ("Diverted flights") due to class imbalance issue
- Used feature engineering to enhance model performance, identifying critical factors influencing flight diversions.
- Visualized the coefficients from the model across the 10 years of flight data

## Results
- Identified key factors contributing to flight delays, providing actionable insights for reducing delays.
- Improved understanding of delay patterns, aiding in better decision-making for time and days of week to fly.
- Successfully predicted diverted flights, enhancing operational efficiency and decision-making.


