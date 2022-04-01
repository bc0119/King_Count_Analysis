# Price Prediction Models for Birkshire Hathaway Real Estate Group

## How To Navigate Through the Repo

## Overview
[1]: https://www.ciclt.net/sn/clt/capitolimpact/gw_ziplist.aspx?FIPS=53033 "ZIP Codes"

This project analyzes the data from `kc_house_data.csv` and [ZIP Codes][1]. The `kc_house_data.csv` data consisted of detailed info of residential properties in King County, WA including sale price (prediction target). ["ZIP Codes][1] data consisted of all the ZIP Codes in King County with associated city.

We are using multiple linear regression modeling to analyze house sale prices and provide suggestions for Birkshire Hathaway Real Estate Group. 

## Business Problem

Washington's Birkshire Hathaway Real Estate Group are looking for efficient ways to refine and streamline the buying & selling process of residential properties in King County, WA for their clients. Our price prediction models aim to provide the company with estimated prices for each city and region based on the clients’ preferences. Consequently, the company can focus more on the targeted area with a pricing reference.

## Data Understanding
The King County House Data (`kc_house_data.csv`) has all the residential property details in King County, WA. We combined with ZIP Code data and organized the property details by each city. Each city data set varies in sizes and average price. So we also grouped the cities into 13 regions based on location proximity, average price, and similiar features. Since some of zipcodes are being shared with multiple towns, we found the center point of each city using latitude and longitude to group the nearby cities with similar prices. 

## Methods
This project uses statiscal analysis, including multiple linear regression. This provides a insightful overview of relationship between the variables. Our prediction model takes in each specified variable the client wants, identifies the variables with high correlations, and returns the predicted property price given those variables. We have built two sets of models based on cities and regions. 

## Conclusions
This model is very large and complex based on the number of variales that we test. Our next step is to incorporate more data to train the model. So that we can find balance between increasing the R-squared and decreasing the error. 

## Next Steps

Further analyses could yield additional insights to improve to our predicition models:

##### Housing Market Data
##### Demographics
##### Cost of Living
##### Education
##### Traffic & Transportation
##### Crime Rate