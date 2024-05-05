# Weather_Prediction_ml_model

Project Overview:
This machine learning project seeks to accurately predict the daily high temperatures at several key locations including Central Park in New York, Midway International Airport in Chicago, Bergstrom International Airport in Austin, and Miami, Florida. Conducted over a month from February 26, 2024, to March 25, 2024, this project demonstrates the application of advanced data science techniques in weather forecasting and financial trading.

Phases:

Manual Prediction:
Setup and utilization of a demo trading account on the Kalshi platform.
Initial temperature predictions were made using a blend of data from the Apple iPhone weather app and the National Weather Service, setting a baseline for model accuracy.
Data Collection and Model Training:
Extensive data collection from five different weather APIs, each chosen for their reliability and data granularity.
Python scripts were employed for data harmonization and integration into a cohesive dataset, which was then used to train a GradientBoostingRegressor model.
Automated Prediction:
Implementation of automated trading strategies on the Kalshi platform, leveraging the predictive power of the trained machine learning model.
The system automatically places trades based on predicted temperature ranges, showcasing real-time application in predictive trading.
Technologies and Tools:

Programming Languages: Python
Development Environment: Jupyter Notebooks
Key Libraries: Pandas, Scikit-learn
APIs Used:
Meteostat: Historical weather data collection.
Open-meteo: Access to historical weather data via an open-source API.
NOAA: Climate data from the National Oceanic and Atmospheric Administration.
SC-ACIS: Data retrieval from specific weather stations.
Visual Crossing: Weather data for model testing and predictions.
Trading Platform: Kalshi
Key Achievements:

Developed a robust temperature prediction model that integrates diverse data sources.
Automated the process of trading based on predictive analytics, illustrating the intersection of machine learning and financial strategies.
Enhanced understanding of model tuning and optimization to reduce overfitting and improve prediction accuracy.
Results:

The project achieved significant predictive accuracy with an improved Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) after tuning the model parameters.
Demonstrated practical application of machine learning models in predicting daily climate events and their potential impact on market trading.
