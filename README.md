# House Sales in Northwestern County


![housing](picture/Readme%20image%201.png)

#### Authors:
1. ABIGAEL NYABAGA
2. BEDAN CHEGE
3. BERYL AGAI
4. BRIAN MUTHAMA
5. FARHIYA JARSO
6. IAN KIPTOO
7. JACKSON MUNENE
8. KELSEY MAINA

## Business Understanding.
### 1.1 Overview
As a major sector of the economy, the real estate market is highly dependent on several factors to achieve success, mainly precise house price forecasts. A real estate agency in King County, Washington state is looking for help in determining the primary factors that affect property values within the region. This project uses data from the King County House Sales dataset, which contains past real estate sales data that includes information on a variety of properties such as the previous sale price, the grade of the home and the year of construction. Some of the challenges that affect the real estate market are economic downturns like decrease in demand of property or increase in housing prices causing challenges of affordability and insufficient data that makes it difficult to make a recommendation system. A solution would be to create a combination of several multiple linear regression models in order to identify trends in the data. The project's objective is to create a thorough advice system for the agency that will help homeowners understand how house renovations may affect the estimated worth of their properties.

### 1.2 Stakeholders
The stakeholders in this analysis are: the real estate agency ,real estate developers,potential investors,potential customers and home owners

### 1.3 Business Problem
A King County real estate agency lacks a reliable system for data-driven insights on home prices, hindering stakeholders' ability to make informed decisions about property values.

### 1.4 Objectives
The key objectives for this analysis are as follows;
1.	Predicting home prices: To create a predictive model that estimates increase in market value of home based on renovation factors.

2.	Identifying the most important features: To review which renovation variables have the highest impact on increasing estimated value of a home.
- How much is the likely increase in the sale price by adding an additional floor?
- How much is the likely increase in the sale price by adding an extension to the living space in the home?
- How much is the likely increase in the sale price by adding an additional bedroom?

3.	Monitoring real estate market trends: To learn more about the regions with the highest and lowest average sale price as well as the most in-demand property types.
## DATA UNDERSTANDING
The research retrieves information from King County House Sales dataset which contains the $kc_house_data.csv$ file used to forecast the sales price of homes in King County.

Description: It comprises of 21,597 housing observations and 20 house features along with a column indicating the home id. The data covers homes sold between May 2014 and May 2015

The columns in the dataset are:

Numerical Columns (15)

- date - Date house was sold
- price - Sale price (prediction target)
- bedrooms - Number of bedrooms
- bathrooms - Number of bathrooms
- sqft_living - Square footage of living space in the home
- sqft_lot - Square footage of the lot
- floors - Number of floors (levels) in house
- sqft_above - Square footage of house apart from basement
- sqft_basement - Square footage of the basement
- yr_built - Year when house was built
- yr_renovated - Year when house was renovated
- lat - Latitude coordinate
- long - Longitude coordinate
- sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
- sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors

Categorical Columns (6):id, waterfront,  view, condition, grade, zipcode.
`Key variables:`
> price, bedrooms, sqft living, floors

`Target Variable`: The `"price"` of the properties is the project's target variable. 
>This indicates that other independent variables, such as the attributes of the property (square footage, number of bedrooms, location, etc.), are what predict or explain the outcome or goal variable. The price of a property will be the variable being modeled or projected in statistical modeling and analysis based on the values of other variables.

These variables will be used to answer the data questions and derive actionable insights to the real estate agency on how to make predictions on price based on features affecting sales

### Data Cleaning
### EDA
### Data modeling
### Results
### Conclusion
### link to presentation
