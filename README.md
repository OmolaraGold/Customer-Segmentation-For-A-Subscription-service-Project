# Customer-Segmentation-For-A-Subscription-service-Project

### PROJECT TITLE: CUSTOMER DATA ANALYSIS FOR A SUBSCRIPTION SERVICE

### PROJECT OVERVIEW
To analyze and segment customers of a subscription service in order to better understand customer behavior, improve retention, and inform targeted marketing strategies. The segmentation will focus on identifying patterns across various customer attributes, including subscription type, revenue, cancellation and region. The insights will help the company enhance its customer experience, and optimize revenue generation.

### DATA OVERVIEW
The customer data used in this analysis includes:
1. Customer ID/Name: This is a unique identifier for each customer to differentiate their individual data record.
2. Region: This is the geographical area where the customer is based. Which helps to identify regional trends and preferences.
3. Subscription Type: This is the category of subscription such as Basic, Premium, and stahdard. This reflects the service tier each customer has opted for and this would help in understanding customer distribution across product tiers.
4. Subscription Start: This is the date when the customer started their subscription. This allows us to analyze customer tenure and identify lifecycle patterns.
5. Subscription End: This is the termination date. This data helps in understanding subscription duration.
6. Canceled Status: This indicate whether a customer has canceled their subscription. This will enable us to know the number of customer that are active versus churned customers.
7. Revenue: The total revenue generated from each customer over the subscription period. This information allows for segmentation based on revenue contribution.

### KEY METRICS
- Revenue By Subscription Type: This is the total revenue generated for each subscription type (for example Basic, Premium and standard). This enable us to be able to compare revenue contribution from different product tiers.
- Revenue By Region: This is the total revenue generated from each region.This helps to identify the region that contribute most to revenue and potential region for expansion.
- Average Duration By Subscription Type: This helps us to know average subscription lenght within each subscription type. It helps us to determine which subscription type has the most loyal customers.
- Renytention Rate: This is the percentage of customer who maintain their subscription over a specific period. It Indicate customer loyalty and satisfaction.

### TOOLS USED
- Microsoft Excel [DOWNLOAD HERE](https://www.microsoft.com): This is for cleaning,analysing and visualization of data. Pivot tables was use to summarize the data for easy interpretation. Charts were also created for virtual representation.
- SQL: Structured Query Language use for Data Quering.
- POWERBI: This is used for Data Visualisation

### FORMULAR USED
``` EXCEL
Subscription duration=(subscription end - subscription start)
```
```SQL
Select * from [dbo].[customersegmentation_project2]
```

### VISUALIZATION
#### REGION BY SUM OF REVENUE
- PIVOT TABLE
  










