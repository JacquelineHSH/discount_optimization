# discount_optimization
To maximize the revenue of a B2B company by optimizing the discount.

## Data
B2B Data from a firm selling a marketing automation software. 
https://raw.githubusercontent.com/ormarketing/b2b/master/data.csv

## Context 
Two main channels are used to sell, i.e., (1) directly after lead generation efforts (e.g., trade-shows, email marketing campaign, website of the company) and (2) indirectly through "partners".

The company has two types of "products", i.e., (1) cloud products and (2) "on-premise" products

The data set has information about:
1.   Dates at which each lead was generated and closed
2.   Whether it's a "new logo" or not
3.   Type of product sought
4.   Deal was won or lost
5.   Billing plan (e.g., one year vs. three years)
6.   Annual Contract Value (ACV)
7.   Amount
8.   Discount
9.   Net Amount (i.e., amoumt - discount)

## Main approach 
1. EDA 
2. Train and test logit models 
3. Repeat and compare 
4. Find the relationship between possibility of win/lose contract and discount of the model with high R square 
5. Optimize the revenue against discount using the above possbility relationship 
6. Get the optimized revenue vs. original revenue
