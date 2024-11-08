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
![image](https://github.com/user-attachments/assets/b425cbff-17f3-42af-9187-d266c3445b96)
- CHARTS
![image](https://github.com/user-attachments/assets/1d734fba-8437-43a6-8ca4-7387908ed652)
![image](https://github.com/user-attachments/assets/2aee5465-b41a-4719-b7bf-59f4dce97f79)
- SQL
![CUSTOMER DATA PROJECT SQL QUE 6](https://github.com/user-attachments/assets/fdf54bbb-7bdc-4535-a4c7-ef5d6815f4ec)

#### DEDUCTION
The following where deduce;
1. Basic Subscription Type: The Basic plan is the primary revenue driver, with the highest lifetime value and loyalty potential. The basic subscription plan generates the largest share of overall revenue, indicating that most customers subscribe to this plan and are satisfied. This plan represents a key group to maintain through continous engagement. Given the high revenue from this plan, there may be an opportunity to upsell or cross-sell additional services to Basic subscribers.
2. Premium Subscription Type: The premium plan contributes a moderate portion of the total revenue. Customers in this plan may seek a balance between value and cost, indicating that they might appreciate some basic features but at a more affordable price. This group represents a strong upsell opportunity,with targeted marketing and incentives.
3. Standard Subscription Type: The standard plan generates the smallest portion of total revenue. Many standard customers could be considered for subscribing to the Basic or Premium plans if there needs evolve. Offering tailored upgrade incentives could also help.

#### 3. TOTAL REVENUE BY SUBSCRIPTION TYPE AND CHURN RATE
- PIVOT TABLE
![image](https://github.com/user-attachments/assets/c6c825cd-2d0f-4e8e-8579-be6065630a67)
- CHARTS
![image](https://github.com/user-attachments/assets/bfaebae7-6a54-42f0-9336-1db8f077deac)
![image](https://github.com/user-attachments/assets/ff4a82ee-c0d5-46e8-89ae-739af6405e5f)

#### DEDUCTION
1. BASIC PLAN: This basic subscription plan has high revenue contribution, low churn rate. The basic plan generates the highest revenue among all subscription types and exhibits a relatively low churn rate. This suggests that basic customers are highly engaged and benefits from this offer. The low churn rate implies high customer loyalty, 
and committment to the service over time. This stability helps ensure a reliable revenue stream from this plan. It is crucial to continue enhancing value through exclusive benefits or loyalty rewards in order to keep the customers in this plan.
2. PREMIUM PLAN: This premium subscription plan has moderate revenue contribution, high churn rate. The premium plan generates a substantial share of total revenue but has a higher churn rate compared to the basic plan. This indicates that while many customers find value in this tier, there is room for improvement in retention. To reduce churn rate, consider reinforcing the benefits of the premium plan and offer incentives.
3. STANDRAD PLAN: This standard subscription plan has low revenue contribution, high churn rate. This indicates that many customer do not remain subscribed for this plan for long, likely due to limited features or high price. To reduce churn, consider implementing engagement strategies like educational resources, low-cost upgrade to the standard plan and adding some interesting features  to the standard plan. This could help retain some customers and increase their contribution to total revenue.

### POWERBI VISUALIZATION
Below is powerBI dashboard that visualizes the insights found in excel and SQL.

![CUSTOMER DATA PROJECT VISUALS](https://github.com/user-attachments/assets/86a81ea2-da5e-4ac6-9950-ae2732ce7562)

![CUSTOMER DATA PROJECT VISUALS 2](https://github.com/user-attachments/assets/92aec8cd-b4b8-4874-bc91-035f74b8e0bc)

### SQL TABLE AND QUERY
![CUSTOMER DATA PROJECT SQL TABLE](https://github.com/user-attachments/assets/c64efcd3-be05-4a0a-9b9e-197c05231f24)
![CUSTOMER DATA PROJECT SQL QUERY 1](https://github.com/user-attachments/assets/bebd25ba-251d-49b7-81ba-6fee015b1172)
![CUSTOMER DATA PROJECT SQL QUERY 2](https://github.com/user-attachments/assets/72045a57-0406-4afc-bf98-85275b91fac7)
![CUSTOMER DATA PROJECT SQL QUERY 3](https://github.com/user-attachments/assets/3733e7a4-898a-45dc-ba5f-9ca4ded3774e)

### EXCEL TABLE
![CUSTOMER DATA TABLE PROJECT2](https://github.com/user-attachments/assets/f7864146-6af3-41db-ab33-8e2a27e4859d)
