# ML_model
Task
The objective of this exercise is to do an analysis of the coffee price, ideally to model it. You act like an:
-	Economist: model the different relations to explain / have a long term view on coffee price
-	Trader: use the different variables to determine relations that can be traded successfully
-	Option trader: use the variables to improve a black & scholes approach using endogenous elements
-	Sales: use the variables to prepare a pitch on why it should be a good idea to buy / sell one of your product on Coffee
-	…

The project is to perform a classical analysis, the following points can be used a steps template:

1.	Data Collection and Preparation:
Gather relevant time series data, including the target variable you want to explain and potential explanatory variables.
Ensure the data is clean and consistent by handling missing values, outliers, and any data quality issues.
Convert timestamps to a consistent time format if necessary.

2.	Exploratory Data Analysis (EDA):
Visualize the time series data using plots such as line charts, histograms, and scatter plots.
Calculate basic statistics to understand the central tendency and variability of the variables.
Identify any patterns, trends, seasonality, or cyclical behavior in the time series.

3.	Correlation Analysis:
Calculate correlation coefficients (e.g., Pearson correlation) between the target time series and potential explanatory variables to measure the strength and direction of linear relationships.

4.	Time Lag Analysis:
Investigate whether there are time lags or delays in the relationships between the variables. You can use cross-correlation or autocorrelation functions for this purpose.

5.	Causal Analysis:
Consider causality by examining Granger causality tests or other causal inference methods to determine if changes in the explanatory variables lead to changes in the target variable.

6.	Feature Engineering:
Create lagged variables or moving averages of the explanatory variables to capture potential time dependencies.
Engineer additional features if necessary, such as seasonality indicators or trend components.

7.	Model Selection:
Choose an appropriate modeling technique based on the nature of your data and the relationships discovered during EDA.

8.	Model Training and Validation:
Split the data into training and validation sets to train and evaluate your chosen model.
Use appropriate metrics (e.g., Mean Absolute Error, Root Mean Squared Error) to assess model performance.
Adjust hyperparameters and validate the model's accuracy.

9.	Model Interpretation:
Interpret the model coefficients or feature importance scores to understand how each explanatory variable contributes to the time series changes.

10.	Forecasting and Explanation:
Use the trained model to make predictions on future time points for the target variable.
Explain the forecasted values based on the relationships and insights gained from the analysis.

11.	Reporting and Communication:
Present your analysis results and insights in a clear and understandable manner, using visualizations, charts, and narratives.

Data sources:
-	dxy.txt: Text file containing information about the DXY index.
-	exercise.sqlite: Sqlite database containing variables to be studied, created based on the below schema.

 
The list of variables is:
'coffee_total_consumption_usda'
'china_gdp_yoy_forecast'
'sugar_nearby'
'crude_nearby'
'coffee_nearby'
'vix_index'
'colombia_coffee_exports'
'non_commercial_net_position'
'coffee_inventory'

