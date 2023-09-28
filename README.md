# Dubai Real Estate Predictions 
Welcome to the Dubai Housing Price Prediction project! This project aims to predict housing prices in Dubai, UAE, using a dataset containing over 80,000 housing transactions from January to June 2023. Whether you're a data scientist, a real estate enthusiast, or someone interested in predictive modeling, this project offers a valuable opportunity to explore and contribute to the world of housing market analysis.
# Dataset
Our dataset consists of detailed information about housing transactions in Dubai, including property features, location data, transaction dates, and, most importantly, the sale prices. With a substantial number of data points, this dataset provides an ideal foundation for building predictive models to estimate housing prices in Dubai.

Dubai Real Estate Transactions found on [Kaggle.com](https://www.kaggle.com/datasets/austinpowers/dubai-real-estate-transaction-first-semester-2023).
# Project Goals
Our primary objectives for this project include:

* Predictive Modeling: Develop accurate machine learning models that can predict housing prices in Dubai based on various features and historical transaction data.

* Insights and Analysis: Gain valuable insights into the Dubai real estate market, including price trends, factors influencing property values, and regional variations.

* Data Visualization: Create informative visualizations to communicate our findings effectively and help stakeholders better understand the Dubai housing market.
## Our Group Members
  * Jae Zakarauskas
  * Joanna Gromek
  * Zunyan Guo
  * Peter Austin
 

Tableau Dashboard: https://jaezak.github.io/dubai_housing_predictions/

# ORDER OF OPERATIONS
## Data Retrieval and Preprocessing:
* Retrieve the CSV.
* Clean the data: drop "amount" and "transaction size" columns, filter out commercial properties. Bin square footage values.
* Determine outliers such as large amount of bedrooms, high sale prices.
* Normalize and standardize the data to ensure all features are on a similar scale. 

## Data Model Implementation:
* We will be performing a linear regression model and are also interested in exploring support vector regressions.
* Split the data into training and testing sets.
* Initialize, train, and evaluate the model using the training and testing data.
* Measure the model's classification accuracy (for classification) or R-squared (for regression) to ensure meaningful predictive power.

## Data Model Optimization:
* Document the model optimization process by making iterative changes to the model and observing the resulting changes in performance.
* Keep a record of the hyperparameters you experimented with and their corresponding performance metrics (e.g., accuracy, R-squared) in a CSV/Excel table or within the Python script itself.
* Perform techniques like hyperparameter tuning, feature selection, or model selection to improve the model's performance.

## Data Visualization:
Tableau Dashboard can be found [here](https://jaezak.github.io/dubai_housing_predictions/).

