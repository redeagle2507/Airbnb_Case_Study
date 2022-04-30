# Airbnb_Case_Study
Define the business-relevant metric and aggregate data across different tables to propose an appropriate listing price by using an ML-based approach to arrive at the recommendations on the listing price which will also help the business stakeholders to understand how the ML model works. 

Dataset Details
The dataset is given to you in an sqlite database named airbnb.db. This has the tables listed above. You can use sqlalchemy or sqlite3 and pandas to read data from this database. You can also export the data as csv files from this db and then read it in using pandas. Refer to this link on more details about fetching data

Tasks
Data Understanding and feature creation:
Look at the table Calendar how many rows and unique listing ids are present? Are there any implications when it comes to having more rows and less unique listing ids?

Look at the price column in Calendar table. What transformations you will need to perform so that you can create a column that can be used as a target/response variable?

Look at the tables Listings, Hosts and Reviews to come up with a list of potential transformations needed in order to have predictors that can be used to predict the listing price.

Create an aggregated view of data spread across different tables, containing the target as well as predictor variables.

Data Quality and checks:
Once the aggregated dataset has been created, do a data audit. Create a data quality report which has the following basic structure:

Continuous Variables: (#unique values, percentage_missing_values, min, max, average, 25th percentile, 75th percentile, 90th percentile, 95th percentile)

Categorical Variables: (#Unique values, percentage_missing_values)

Highlight any data anomaly that you find and fix it.

Variable profiling and checking relationships between variables:
Assess the relationship between target and predictor variables. You can compute correlations, plot bivariate relationships.

Based on the above analysis summarize your findings and list down the transformations you will do on different predictors, remove the variables from further analysis.

Modelling and insights:
Explain your approach on creating train/test/validation splits.

Create a comparison matrix to compare different regression models you've run

Experiment with Linear Regression, Regression Trees, Random Forest Regressor and GBM. Not compulsory but you can also experiment with Xgboost, Lightgbm

Explain which model you've finalized and why did you finalize the model.

Explain what are the top 5 most important predictors and also explain the direction of impact of these top 5 predictors on the response variable.
