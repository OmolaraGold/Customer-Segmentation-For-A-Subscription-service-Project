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
#### 1. REGION BY SUM OF REVENUE
- PIVOT TABLE
![image](https://github.com/user-attachments/assets/e750bd24-1c32-4e0b-8d5b-99f1e457aac4)
- CHART
![image](https://github.com/user-attachments/assets/e1420c33-c63d-43f7-8769-dd6d755a9fb9)
![image](https://github.com/user-attachments/assets/520214e1-dc89-47aa-96bb-ea6c9f6618fd)

#### DEDUCTION
The following can be deduce from this data;
Analyzing revenue by region can provide valuable insights into customer behavior and market potential across those regions.
1. EAST (Highest Revenue): High revenue in the Eastern region might result from factors like a larger customer base, higher demand for premium subscription types, or effective marketing strategies. We need to Explore why East outperform other regions considering factors such as customer demographics, preferred subscription types, and marketing effectiveness. And also considering reinvesting in this region to maintain high customer satisfaction and retention rates.
2. SOUTH (Second Highest Revenue):  South might have shown a strong growth potential but it is still be behind East in terms of revenue. We need to focus on strategies that would make the customers to subscribe to higher-tier plans and improve retention. Promotions might be considered in order to drive engagement and revenue growth.
3. WEST (Third Highest Revenue): West with a moderate revenue contribution might indicate a growing market. Customer preferences or lower awareness of premium options might be limiting growth. Incentives and promotions to increase subscription adoption could help this region increase its revenue contribution.
4. NORTH (Lowest Revenue): Low revenue in this region can be as a result of lower customer awareness, few/fewer subscribers or higher churn rates. Growth strategies focusing on customer engagement and preferences could be targeted Explore tailored promotions to drive engagement, boost subscriptions and reduce churn.

#### 2. SUBSCRIPTION TYPES BY REGION
- PIVOT TABLE
  


















