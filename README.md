# Predicting New York City Real Estate Sales Price

This project uses NYC properties dataset retrieved from Kaggle to build various regression models to predict the sale price. 

Link to dataset: https://www.kaggle.com/new-york-city/nyc-property-sales?fbclid=IwAR2Y9KIsAVRDRJHosE5iOcIeiee8OZMlWSsoZZ33Nl9lVcsf-XhDYKVvVMM

## Description of the Dataset

The dataset is a combination of five different datasets containing real estate properties information from New York’s five Boroughs. Each row contain information on the a property sold during a 12-month period from September 2016 to September 2017. Each row contains information about an individual property such as:
* Borough
* Neighborhood
* Building Class
* Tax Class
* Block
* Lot
* Building Class
* Address
* Number of Residential Units
* Number of Commercial Units
* Size of Land in $`ft^2`$
* Gross Squared Feet
* Year Built
* Sale Price
* Sale Date
The dataset contains missing values in important feature such as the sales price and year built. Initial analysis indicates that year built also has input errors. Please refer to our Jupyter Notebook named "ALY6140-final-report.ipynb" for more detailed data preperation and cleaning. 

## Methodologies
We will built five regression models to predict sale price namely:
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. Decision Tree Regression
5. Random Forest Regression
6. XGboost


## Authors

Yu-Sen Miao
Duy Nguyen
Shiting Chen


