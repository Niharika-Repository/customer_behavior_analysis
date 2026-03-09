# Customer Shopping Behavior Analysis

## 1. Executive Summary
This is an End-to-End project analyzes customer shopping behavior using 3,900 retail transactions.  
The objective is to identify patterns in purchasing behavior, customer segments, and product performance.

The workflow simulates a real-world analytics pipeline:
- Data preparation in Python
- Data analysis in PostgreSQL using SQL
- Data visualization in Power BI using DAX

The final output is an interactive dashboard and business insights for decision making.

---

## 2. Business Problem
A retail company wants to understand customer shopping behavior and purchasing trends.

Management wants to identify:
- Key revenue drivers
- Customer segments
- Impact of discounts and promotions
- Product performance
- Subscription impact on spending

The goal is to use data to improve marketing strategies, customer engagement, and product positioning.

---

## 3. Methodology

### Data Preparation (Python)
- Loaded dataset using Pandas
- Performed exploratory data analysis
- Checked missing values
- Imputed missing values in `review_rating` using median by category
- Standardized column names to snake_case
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column `promo_code_used`

### Data Analysis (PostgreSQL)
The cleaned dataset was loaded into PostgreSQL.

SQL queries were used to analyze:
- Revenue by gender
- Average purchase amount
- Top rated products
- Discount usage patterns
- Customer segmentation
- Revenue by age group
- Shipping type impact
- Subscription vs non-subscription behavior

### Visualization (Power BI)
An interactive dashboard was created in Power BI.

Key features:
- KPI cards
- Category analysis
- Customer segmentation
- Revenue trends

DAX was used to create calculated measures such as:
- Total Revenue
- Average Purchase Value
- Customer Segment Metrics

---

## 4. Skills

**Programming**
- Python
- Pandas

**Database**
- PostgreSQL
- SQL (joins, aggregations, CTEs)

**Visualization**
- Power BI
- DAX

**Data Analysis**
- Exploratory Data Analysis
- Customer Segmentation
- Business Insight Generation

---

## 5. Results

Key findings from the analysis:

- Loyal customers generate a large share of revenue
- Subscribers have higher average spending
- Some products rely heavily on discounts
- Express shipping customers spend more on average
- Certain age groups contribute more revenue

These insights highlight opportunities for targeted marketing and customer retention.

---

## 6. Business Recommendations

- Expand subscription benefits to increase loyalty
- Implement customer loyalty programs
- Optimize discount strategies
- Promote high-rated products in marketing campaigns
- Target high-spending customer segments

---

## 7. Next Steps

Possible extensions of the project:

- Build customer lifetime value (CLV) models
- Implement product recommendation systems
- Apply machine learning for purchase prediction
- Integrate real-time data pipelines

---

## Tools Used

- Python
- PostgreSQL
- SQL
- Power BI
- DAX
- GitHub

