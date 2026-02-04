# Excel-Data-Analysis-Dashboard-2
An interactive Excel dashboard that explores e-commerce customer behavior

## Dashboard
<img width="1872" height="976" alt="Image" src="https://github.com/user-attachments/assets/8fbe5805-1eb5-427b-be30-ed30d9cb4796" />
This project presents an interactive E-Commerce Customer Behavior Analysis Dashboard designed to uncover insights into customer purchasing patterns, satisfaction levels, and revenue distribution.
The dashboard enables users to explore customer data dynamically using slicers such as city, gender, activity status, and membership type, supporting data-driven commercial decision-making.

## Datasets used
- <a href="https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset?resource=download">Raw Dataset</a>
- <a href="https://github.com/khinezinthant-DA/Excel-Data-Analysis-Dashboard-2/blob/main/E-commerce%20Customer%20Behavior.xlsx">Processed Dataset and Interactive Dashboard</a>

## Analytical Questions
- How does spending behavior vary between male and female customers within the same age group?
- What is the recency of customer purchases, and how are customers distributed across active, at-risk, and inactive segments?
- How does membership type impact overall customer satisfaction levels?
- Is there a relationship between product ratings and total customer spending?
- Which cities contribute to approximately 80% of total revenue?
- Does the application of discounts influence total customer spending?

## Features Overview
- KPI Cards showing:
  - Total number of customers
  - Top city by total spend
  - Top age group by spend
- Interactive slicers for:
    - City, Customer activity status, Gender and Membership type
- Customer purchase behavior analysis by:
  - Age group and gender
  - Number of items purchased
- Recency of purchases categorized into Active, Moderately Active, and Inactive customers
- Satisfaction level gauges segmented by membership type (Gold, Silver, Bronze)
- Revenue distribution across major cities with cumulative contribution
- Impact of discounts on total spending
- Correlation analysis between customer ratings and total spend

## Tools & Tech
- Excel (PivotTables, Charts, Slicers)
- Dashboard design & data visualization techniques

## Documentation / Dashboard Creation Process
### 1. Data Cleaning & Formatting
- Standardized raw data to ensure consistency and accuracy
- Converted categorical and logical fields into analysis-ready formats
- Handled missing and inconsistent values prior to visualization

### 2. Feature Engineering Using IFS Logic
#### Discount Applied
- Converted Boolean values (TRUE / FALSE) into categorical labels (Yes / No)
#### Age Group Classification
- Grouped individual ages into defined age ranges for clearer demographic analysis
#### Customer Activity Status
- Customers with purchases within 21 days classified as Active
- Purchases between 21 and 42 days classified as Moderately Active
- Purchases 43 days and above classified as Inactive
#### Satisfaction Score Calculation
- Assigned numerical values to satisfaction responses:
Satisfied = 1
Neutral = 0.5
Unsatisfied = 0
No Response = 0
- Used these scores to calculate overall customer satisfaction for the gauge chart
### 3. Data Visualization
The following visualizations were created to support data exploration and insight generation:
1. Population Pyramid Chart
2. KPI Cards
3. Gauge Charts
4. Scatter Plot
5. Pareto Chart
6. Bar Chart

## Project Insights
### Spending Behavior by Gender and Age Group
Male customers tend to spend more at earlier age ranges, while female customers show higher spending levels in later age groups. Despite these differences, the 30–35 age group emerges as the highest-spending segment overall across both genders.

### Customer Purchase Recency & Activity Segmentation
Inactive customers represent the smallest segment. The majority of customers fall into the Active (45%) and Moderately Active (42%) categories. This indicates an opportunity to convert moderately active customers into active ones through targeted discounts, seasonal promotions, or re-engagement campaigns.

### Membership Type & Customer Satisfaction
Membership-based satisfaction analysis shows that Gold members are generally satisfied, Silver members tend to remain neutral, and Bronze members are close to the unsatisfied range, indicating a need to review factors contributing to dissatisfaction within this tier. 
When filtered by customer activity status, most active customers across all membership types report high satisfaction levels. While this is a positive indicator, it is important to identify early warning signs and potential drivers that may cause dissatisfied customers to be inactive.

### Relationship Between Ratings and Spending
A positive correlation exists between product ratings and total spending. Customers who provide higher ratings tend to spend more, emphasizing the importance of maintaining high satisfaction levels to drive revenue growth.

### Revenue Contribution by City
Approximately 80% of total revenue is generated by four key cities: San Francisco, New York, Los Angeles, and Miami, indicating strong geographic concentration of high-value customers.

### Impact of Discounts on Spending
Customers who do not use discounts tend to generate higher overall spending compared to those who do, suggesting that high-value or loyal customers are less price-sensitive.

## Conclusion
Key findings show that customers aged 30–35 are the highest spenders, active customers are generally more satisfied, and a small number of cities generate the majority of total revenue. Additionally, customer satisfaction is closely linked to spending behavior, reinforcing the importance of delivering positive customer experiences. Overall, the dashboard provides actionable insights that support data-driven decision-making for marketing, retention, and customer experience strategies.

## Recommendation
To boost overall customer engagement and loyalty, businesses should focus on converting moderately active customers into active ones through targeted promotions, limited-time offers, and personalized reminders, helping to prevent churn. At the same time, the Bronze membership experience should be carefully reviewed, including benefits, pricing, and service quality, to address dissatisfaction and reduce the risk of members becoming inactive. Enhancing customer satisfaction initiatives is also crucial, as higher satisfaction ratings are linked to increased spending; this can be achieved by prioritizing product quality, exceptional customer service, and post-purchase engagement. Additionally, discount strategies should be reconsidered—rather than applying discounts broadly, they should be used strategically for reactivating dormant customers, ensuring profitability is maintained.

## Interactive Dashboard Demo
<img width="2351" height="1074" alt="Image" src="https://github.com/user-attachments/assets/c1ec3a67-d5f4-44ae-b6ab-57e847a5f4cf" />

