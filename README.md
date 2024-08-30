# Walmart:Confidence-Interval-and-CLT
## PROBLEM STATEMENT:
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).
## 1. ASK
## Questions:
1. Import the dataset and do usual data analysis steps like checking the structure &
characteristics of the dataset.
 * The data type of all columns in the “customers” table.
 * You can find the number of rows and columns given in the dataset
 * Check for the missing values and find the number of missing values in each column
2. Detect Null values and outliers
 *  Find the outliers for every continuous variable in the dataset.
 *  Remove/clip the data between the 5 percentile and 95 percentile
3. Data Exploration
 * What products are different age groups buying?
 * Is there a relationship between age, marital status, and the amount spent?
 * Are there preferred product categories for different genders?
4. How does gender affect the amount spent?

   From the above calculated CLT answer the following questions.
 * Is the confidence interval computed using the entire dataset wider for one of the genders? Why is this the case?
 * How is the width of the confidence interval affected by the sample size?
 * Do the confidence intervals for different sample sizes overlap?
 * How does the sample size affect the shape of the distributions of the means?
5. How does Marital_Status affect the amount spent?

   From the above calculated CLT answer the following questions.
 *  Is the confidence interval computed using the entire dataset wider for one of the genders? Why is this the case?
 *  How is the width of the confidence interval affected by the sample size?
 *  Do  the confidence intervals for different sample sizes overlap? 
 *  How does the sample size affect the shape of the distributions of the means?
6. How does Age affect the amount spent?

   From the above calculated CLT answer the following questions.
 * Is the confidence interval computed using the entire dataset wider for one of the genders? Why is this the case?
 * How is the width of the confidence interval affected by the sample size?
 * Do the confidence intervals for different sample sizes overlap?
 * How does the sample size affect the shape of the distributions of the
   means?
## 2. PREPARE
## Data Storage:
This public dataset is completely available on the open platform where it stores and consolidates all available datasets for analysis. The specific individual datasets at hand can be obtained at this link below: <a href ="https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/293/original/walmart_data.csv?1641285094" > Click here <a/>
##  Tools Used:
1. Google_Collab
## 3. ACT
## Insights:
  1. With reference to the above data, at a 95% confidence interval:
     * The highest average amount spent by 26- to 35-year-old customers will lie between 944419.9990 and 1034842.9516.
     *  The average amount spent by 36- to 45-year-old customers will lie between 819003.0902 and 940678.8198.
     * The average amount spent by 18- to 25-year-old customers will lie between 799594.4375 and 909664.7362.
     * The average amount spent by 46- to 50-year-old customers will lie between 711215.1004 and 874125.3830.
     * The average amount spent by 51- to 55-year-old customers will lie between 685670.0292 and 840962.3353.
     * The average amount spent by 55+ age group customers will lie between 470454.5225 and 610200.5797.
     * The lowest average amount spent by 0 to 17-year-old customers will lie between 524534.4423 and 714973.3156.
2) From the above data, it is clear that the age group 26 to 35 spends more compared to other age categories.
3) Age groups above 55 and below 0 to 17 spend very little compared to others.
4) Confidence intervals for average 26- to 35-year-old and 36- to 45-year-old spending are not overlapping.
5) With respect to the above data, the company should target the age category between 26 and 35, as they spend more money compared to others

## Recommendations
1) Men spend more money than women, so the company should focus on retaining male customers and getting more male customers.
2) Product Category: 5, 1, and 8 have the highest purchasing frequency. It means the products in these categories are liked more by customers. The company can focus on selling more of these products.
3) Product Category: 11, 2, and 6, 3 have almost close competition in purchasing.The company can focus on selling more of these products.
4) Unmarried customers spend more money compared to married customers. So the company should focus on retaining the unmarried customers and getting more unmarried customers.
5) 86% of purchases are done by customers whose ages are between 18 and 45. So the company should focus on the acquisition of customers who are aged 18–45.
6) Customers living in City_Category C spend more money than other customers living in B or A. Selling more products in City Category C will help the company increase sales.
