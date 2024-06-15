
# Flight Data Analysis Project (1999-2008)

## Overview
This project involves the analysis of commercial flight data from 1999 to 2008 to uncover trends and patterns in flight delays and predict diverted flights. The analysis was conducted using Python, R, and SQL.
Flight data was retrieved from Havard Database (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7)

## Objectives
- Analyze flight delay patterns to identify key contributing factors.
- Predict diverted flights using machine learning techniques.

## Technologies Used
- **Python**: Data exploration, machine learning.
- **R**: Statistical analysis.
- **SQL**: Data extraction and cleaning.

## Key Contributions
### Data Preparation
- Extracted and cleaned flight data from 1999 to 2008 using SQL.
- Created a column named "significant delay" to identify flights with arrival and departure delays greater than 15 minutes.

### Exploratory Data Analysis (EDA)
- Utilized Python for initial data exploration, visualizing delay distributions, and identifying outliers.
- Conducted detailed statistical analysis in R to understand the impact of different factors on flight delays.

### Machine Learning
- Implemented logistic regression models in Python to predict diverted flights.
- Trained and evaluated models, achieving high accuracy in predictions.
- Used feature engineering to enhance model performance, identifying critical factors influencing flight diversions.

## Results
- Identified key factors contributing to flight delays, providing actionable insights for reducing delays.
- Improved understanding of delay patterns, aiding in better decision-making for flight operations.
- Successfully predicted diverted flights, enhancing operational efficiency and decision-making.

## How to Use
1. Clone the repository: `git clone https://github.com/yourusername/flight-data-analysis.git`
2. Navigate to the project directory: `cd flight-data-analysis`
3. Install the necessary dependencies: `pip install -r requirements.txt`
4. Run the analysis scripts: `python analysis_script.py`

