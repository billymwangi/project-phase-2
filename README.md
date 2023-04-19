# King County Houses Price Prediction Using Regression Analysis


![Graph](Image_2.jpg)


## Business Overview:
According to the 2020 census, King County was the most populous county in Washington, and the 13th-most populous in the United States. It is in Seattle, the state's most populous city. Given the statistics, Tella Real Estate Agency, based in King County, has undertaken a research to find out the best performing metrics when it comes to house sale prices determination. As such, we went all out to do multiple regression analysis to gain insights into the home sales market and improve the sellers' chances to make sales. By identifying the key factors that affect the sale prices of houses, the agency can develop more effective marketing strategies, help sellers target the right buyers, and make better investment decisions.


## Problem Statement
Tello Real Estate Agency has a dataset of home features collected from the county houses. They include the number of bathrooms, number of bedrooms, number of floors, square footage of living space amongst others, as seen in the dataset attached. The agency wants to understand the relationship between these features and the sale prices of houses in King County, and particularly, which features most affect the prices. 

## Objectives
The following are the questions whose answers we seek in the analysis:
* Are the various features significant predictors of house prices?
* Which features are highly considered in determination of house prices?
* Are some or all of these features related to each other?
* What are the peak house sale seasons?
We used multiple regression analysis to answer the above questions.


## Data Understanding and Analysis

### Source of Data
We used the following data to compute our analysis:
* King County House Sales found https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3/blob/main/data/kc_house_data.csv 

### Data Analysis
* Our data had 21 features that we worked with to come up with the best predictive model.
* We started by analyzing each of the house features individually by looking at their charecteristics and distribution.
* As part of preparing our data for analysis, we cleaned it as outlined stepwise in our notebook.
* Next, we tracked the relationship amongst the individual variables with each other.
* For our data with categorical variables as well as that which wasn't normally distributed, we did some feature engineering for variables we felt would hav an impact in the analysis.
* Finally, we modelled various variables to see how the regression compared to our baseline model in determining the house prices.

### Data Visualization

### Graph of individual variables' distribution:
![Graph](Graph_1.png)

### A look at the price dstribution:
![Graph](price_distribution.png)

### How the various seasons impact house purchase:
![Graph](quarters.png)


## Conclusion
* The variables that have a major influence on the price of the house are; square foot living, age of the house,good condition of the house,if the house is on a waterfront and has an excellent view.
* The variables that has the least influence on the price of the house are; grade,number of bedrooms,sqft lot,sqft basement and sqft lot 15.

We can also see that:

- The highest number of house sales are made in the second quarter of the year (Q2: April 1 - June 30) which fall in the Spring season
- The lowest number of house sales are made in the first quarter of the year (Q1: January 1 - March 31) which fall mostly in the Winter season

## Recommendations
* Revonate their house since this increases the value of the house
* Ensure that the houses are in good condition before putting it into the market for sale
* Increase square footage of living space 
* Put up their houses for sale in peak season-Spring

## Future work
* Reducing noise in the data to improve the accuracy of our model. 
* Additionally investigate certain features, such as constructional/architectural values of the house, to see what trends we could discern from that. 