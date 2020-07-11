# Energy-Consumption-predict
Given a household_power_consumption dataset publicly available. I have to predict power consumption for next 7 days on which i applied many time series machine learning models.
ARIMA was first of them. Then i preprocessed the dataset and transformed it into a prediction with classification style as shown in ARIMA notebook. Then I used that preprocessed
data for Linear Regressor, Decision Tree and GBT regressor in PySpark to compare the efficiency of simple Python compilation time and distributed compilation time as shown in GBT notebook.
