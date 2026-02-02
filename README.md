# Excel-Data-Analysis-Dashboard-2
An interactive Excel dashboard that explores e-commerce customer behavior

## Dashboard
<img width="1872" height="976" alt="Image" src="https://github.com/user-attachments/assets/8fbe5805-1eb5-427b-be30-ed30d9cb4796" />
This project presents an interactive E-Commerce Customer Behavior Analysis Dashboard designed to uncover insights into customer purchasing patterns, satisfaction levels, and revenue distribution.
The dashboard enables users to explore customer data dynamically using slicers such as city, gender, activity status, and membership type, supporting data-driven commercial decision-making.

## Datasets used
- <a href="https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset?resource=download">Raw Dataset</a>
- <a href="https://github.com/khinezinthant-DA/Excel-Data-Analysis-Dashboard-2/blob/main/E-commerce%20Customer%20Behavior.xlsx">Processed Dataset and Interactive Dashboard</a>

## Features Overview
#### Total Sales Over Time
Line chart tracking monthly sales (2019–2022) for different coffee types (Arabica, Excelsa, Liberica, Robusta).
#### Sales by Country
Horizontal bar chart ranking revenue from top markets (e.g., United States, Ireland, United Kingdom).
#### Top 5 Customers
Highlights highest-spending customers.
#### Interactive Filters
Order Date: Time range slicer
Roast Type: Dark / Medium / Light
Size: 0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg
Loyalty Card: Yes / No
These visual elements and filters allow users to explore key insights with ease.

## Tools & Tech
- Excel (PivotTables, Charts, Slicers)
- Dashboard design & data visualization techniques

## Documentation / Dashboard Creation Process
### Step 1: Raw Data Preparation
1. Raw Data
- Collected customer data by using XLOOKUP in the Orders sheet.
- Retrieved product data by applying INDEX & MATCH in the Orders sheet.
- Converted coffee type names from short codes to full names using the IFS function.
- Added "kg" to the Size column using Custom Formatting.

2. Data Cleaning
- Removed duplicate records from the finished raw dataset.
- Converted the cleaned raw data into an Excel Table for better data management and analysis.

### Step 2: Data Analysis & Visualization
1. Total Sales Over Time
- Created a Pivot Table to calculate total sales over time by coffee type.
- Visualized the results using a Line Chart.

2. Interactive Controls
- Inserted a Timeline for order date filtering.
- Added Slicers for:
  Roast Type
  Size
  Loyalty Card status

3. Additional Insights
- Created a Sales by Country chart using a Pivot Table.
- Built a Top 5 Customers chart based on total sales value.

## Project Insight
- Coffee sales show noticeable fluctuations across months, indicating seasonal demand patterns and peak sales periods.
- The US market is ~3.7 times larger than the combined total of all European markets.
- Over the years, customers’ coffee preferences have shifted: Excelsa topped the list in 2019, followed by Arabica in 2020 and 2021, before Liberica became the favorite in 2022.

## Final Conclusion:
In conclusion, coffee sales show clear seasonal trends, with certain months consistently driving higher demand. The US remains the largest market by far, about 3.7 times bigger than all of Europe combined. Customer preferences have also changed over time. These insights suggest that businesses need to consider both regional market size and evolving tastes when planning their product offerings.

## Interactive Dashboard Demo
<img width="2351" height="1074" alt="Image" src="https://github.com/user-attachments/assets/67741130-1171-41b2-a3e2-dff047de5f90" />

