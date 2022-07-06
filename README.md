# Thesis
This GitHub repository contains the data and code I have used in my thesis project for the MSc in Applied Data Science at Utrecht University, titled 
"Using LSTM and XGBoost for streamflow prediction based on meteorological time series data" supervised by Dr. Edwin Sutanudjaja, Prof. dr. Derek Karssenberg and Youchen Shen. 

# Notebooks
In this project, we used different ML methods including LSTM, XGBoost, and Multiple Linear Regression (MLR) for two gauging stations including Basel and Lobith. The notebook was named after the model and station.

# Data
Data is available in the directory called "data" with the following files for each station 
 * observed discharge (m^3/s) obtained from the Global Runoff Data Center (GRDC)  plus meteorological driving variables averaged over the upstream grids of the gauging station in CSV format
 * simulated discharge (m^3/s) from the PCR-GLOBWB plus its residuals and observed discharge (m^3/s) in flies which states with q in CSV format

# Visualizing results
 
 visualization related to each model can be seen within the related notebook. Visualization related to comparing all models is done in Visualization notebook.
 
 # Output
 
 The folder output contains the outputs resulted from running different LSTM with diffrent time windows.  


