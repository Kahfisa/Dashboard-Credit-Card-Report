# Credit-Card-Report


## Introduction
This dashboard provides a comprehensive overview of customer profiles and financial behavior, highlighting key metrics such as total customers and average satisfaction. It offers customer segmentation by occupation, marital status, and location, while also showcasing sales performance across different occupations and card categories. Furthermore, it visualizes transaction and utilization patterns by occupation, and illustrates the distribution of delinquent accounts across various customer profiles and geographic areas.

## Tools
- Python
- Looker Studio

## Dataset
|Dataset              |Column                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|credit card          |client_num, customer_age, gender, dependent_count, education_level, marital_status, state_cd, zipcode, car_owner, house_owner, personal_loan, contact, customer_job, income, cust_satisfaction_score, card_category, annual_fees, activation_30_days, customer_acq_cost, week_start_date, week_num, qtr, current_year, credit_limit, total_revolving_ba, total_trans_amt, total_trans_vo, avg_utilization_ratio, use_chip, interested_earne, deliquent_acc|

## Business Question
- How are customers distributed by occupation, marital status, and geographic location?
- Which occupation and card types contribute most to total revenue (annual fees)?
- How do average transaction volumes differ across customers occupation?
- Which occupation has the highest average card utilization ratio?
- Which occupations have the highest number of delinquent accounts?
- Which states show higher delinquency accounts?

## Dashboard Preview
<img width="1279" height="997" alt="image" src="https://github.com/user-attachments/assets/5eabf7b8-1627-4aaf-8629-193c8c69c176" />

Logo Source: Image by juicy_fish on Freepik


## Insight
- The majority of credit card users come from the self-employed segment, followed by businessmen and white-collar workers. In terms of marital status, most customers are married. Geographically, the highest concentration of customers is found in New York, California, Texas, and Florida.
- For income derived from annual fees, the self-employed segment is the largest contributor, primarily from the Blue card category, with total revenue reaching 353,340. However, when focusing on income from transaction activities, the businessman segment appears the most promising, with an average transaction frequency of 80 times during the credit card usage period.
- The highest default rates are recorded in New York, California, Texas, and Florida, indicating a significant concentration of credit risk in regions with high economic activity. From a customer profile perspective, groups with a Graduate-level education and occupations as Self-employed, Businessman, and White-collar workers exhibit the highest delinquency rates compared to other segments.
