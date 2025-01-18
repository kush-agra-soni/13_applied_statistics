# Customer Purchase Behavior Analysis using Descriptive Statistics

## Project Overview  
The project focuses on analyzing a dataset of customer information and purchasing behavior to identify patterns and insights. The goal is to help the company optimize marketing efforts and increase offer acceptance rates by understanding customer behavior better.

## Problem Statement  
Analyze the dataset containing customer information and purchasing behavior to derive actionable insights. The primary objective is to identify trends, correlations, and patterns to enhance marketing strategies.

## Dataset Description  
The dataset was gathered during last year's campaign and contains the following columns:

- **Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise  
- **ID**: Unique ID of each customer  
- **Year_Birth**: Age of the customer  
- **Complain**: 1 if the customer complained in the last 2 years  
- **Dt_Customer**: Date of customer's enrollment with the company  
- **Education**: Customer's level of education  
- **Marital**: Customer's marital status  
- **Kidhome**: Number of small children in customer's household  
- **Teenhome**: Number of teenagers in customer's household  
- **Income**: Customer's yearly household income  
- **MntFishProducts**: Amount spent on fish products in the last 2 years  
- **MntMeatProducts**: Amount spent on meat products in the last 2 years  
- **MntFruits**: Amount spent on fruits products in the last 2 years  
- **MntSweetProducts**: Amount spent on sweet products in the last 2 years  
- **MntWines**: Amount spent on wine products in the last 2 years  
- **MntGoldProds**: Amount spent on gold products in the last 2 years  
- **NumDealsPurchases**: Number of purchases made with discounts  
- **NumCatalogPurchases**: Number of purchases made using the catalog  
- **NumStorePurchases**: Number of purchases made in-store  
- **NumWebPurchases**: Number of purchases made through the company's website  
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month  
- **Recency**: Number of days since the last purchase  

### Data Cleaning and Preprocessing  
Key preprocessing steps include:

- **Dt_Customer Column**: Converted to `datetime64[ns]` type, invalid entries replaced with `NaT`. Missing values (916) imputed with the mean date (2013-06-16).  
- **Income Column**: 24 missing values filled with the mean income (52,247.25).  

All other columns were verified for appropriate data types (numerical and categorical) and aligned as necessary.

### Summary of Basic Statistics  
| Column Name            | Mean        | Median      | Variance      | Standard Deviation |  
|-----------------------|-------------|-------------|---------------|--------------------|  
| ID                    | 5592.16      | 5458.5      | 10,540,820.00  | 3246.66            |  
| Year_Birth            | 1968.81      | 1970.0      | 143.62        | 11.98              |  
| Income                | 52,247.25    | 51,741.5    | 626,891,300.00 | 25,037.80          |  
| Kidhome               | 0.44         | 0.0         | 0.29          | 0.54               |  
| Teenhome              | 0.51         | 0.0         | 0.30          | 0.54               |  
| Recency               | 49.11        | 49.0        | 838.82        | 28.96              |  
| MntWines              | 303.94       | 173.5       | 113,297.80    | 336.60             |  
| MntFruits             | 26.30        | 8.0         | 1581.93       | 39.77              |  
| MntMeatProducts       | 166.95       | 67.0        | 50,947.43     | 225.72             |  
| MntFishProducts       | 37.53        | 12.0        | 2984.33       | 54.63              |  
| MntSweetProducts      | 27.06        | 8.0         | 1704.08       | 41.28              |  
| MntGoldProds          | 44.02        | 24.0        | 2721.44       | 52.17              |  
| NumDealsPurchases     | 2.33         | 2.0         | 3.73          | 1.93               |  
| NumWebPurchases       | 4.08         | 4.0         | 7.72          | 2.78               |  
| NumCatalogPurchases   | 2.66         | 2.0         | 8.54          | 2.92               |  
| NumStorePurchases     | 5.79         | 5.0         | 10.57         | 3.25               |  
| NumWebVisitsMonth     | 5.32         | 6.0         | 5.89          | 2.43               |  
| Response              | 0.15         | 0.0         | 0.13          | 0.36               |  
| Complain              | 0.01         | 0.0         | 0.01          | 0.10               |  
| Age                  | 56.19        | 55.0        | 143.62        | 11.98              |  

This concludes the overview and insights for the Customer Purchase Behavior Analysis using descriptive statistics.

## Contributions  
Feel free to contribute by exploring and extending the analysis further, adding new insights, or enhancing data visualizations.

## License  
This project is licensed under the [MIT License](LICENSE).  
