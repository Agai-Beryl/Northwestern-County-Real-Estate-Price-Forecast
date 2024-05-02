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

>**The stakeholders** in this analysis are:the real estate agency,home owners,potential investors and potential customers
>**Business Problem**
A King County real estate agency lacks a reliable system for data-driven insights on home prices, hindering stakeholders' ability to make informed decisions about property values.
>**Objectives**
The key objectives for this analysis are as follows;
The key objectives for this analysis are as follows;
>* Predicting home prices: To create a predictive model that estimates increase in market value of home based on renovation factors.
>* Identifying the most important features: To review which renovation variables have the highest impact on increasing estimated value of a home.We investigated how adding: *additional bathroom,an extension to the living space in the home,an additional bedroom and extension to the lot in the home* have an impact on change in house prices.
>* Monitoring real estate market trends: Real estate trends are used by investors to help them decide where and when to make investments by learning more about the regions with the highest and lowest average sale price as well as the most in-demand property types.
## DATA UNDERSTANDING
The research retrieves information from King County House Sales dataset which contains the $kc_house_data.csv$ file used to forecast the sales price of homes in King County.It comprises of 21,597 housing observations and 20 house features along with a column indicating the home id. The data covers homes sold between May 2014 and May 2015
The columns in the dataset are:
**Numerical Columns**15):date,price,bedrooms,bathrooms,sqft_living,sqft_lot,floors,sqft_above,sqft_basement,yr_built,yr_renovated,lat,long,sqft_living15,sqft_lot15 
**Categorical Columns** (6):id, waterfront,  view, condition, grade, zipcode.
`Key variables:`
> price, bedrooms,bathrooms, sqft living, sqft_lot.
`Target Variable`: The `"price"` of the properties is the project's target variable. 
>This indicates that other independent variables, such as the attributes of the property (square footage, number of bedrooms, location, etc.), are what predict or explain the outcome or goal variable. The price of a property will be the variable being modeled or projected in statistical modeling and analysis based on the values of other variables.

These variables will be used to answer the data questions and derive actionable insights to the real estate agency on how to make predictions on price based on features affecting sales

### Data Cleaning
we identified outliers in our dataset using boxplots and we removed the neccesary outliers .
![housing](picture/Identifying%20outliers.png)
we also identified the missing values in our dataset and eliminated them accordingly.For the waterfall feature we replaced the null values with "UNVERIFIED".This is because this feature had a high value count and we considered it a significant feature in our data analysis.For the view feature we opted to drop it since it had a low value count and was not considered significant in our analysis.For the year renovated,we droped the feature as it was not a significant feature in our analysis.
We then checked for duplicate values and there is no appearance of duplicate values in our data.
### EDA
We compared the number of bathrooms, bedrooms, and floors in the dataset with the aimed to provide insights into the typical configuration of homes in the area.The visualization below provides a clear comparison of the most common configurations of these features in the dataset.
![housing]()
The analysis reveals that the majority of homes in the dataset have at least 3 bedrooms, 2 bathrooms, and 1 floor.
We then did a correlation to identify which features have the highest correlation to price.This helped us identify the factors affecting the price of houses.
![housing]()
We analized the price trends of house sales over the months.Notably, February records the lowest average price, contrasting with April, which demonstrates the highest.This will inform the house buyers on the correct time to buy a home.
![housing]()
### Data modeling

### Results
### Conclusion
### link to presentation
> **Link:**[presentation link]()