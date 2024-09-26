# Company XYZ Analysis (2021-2022)

Interactive PowerBI report can be found [here.](https://app.powerbi.com/reportEmbed?reportId=1ce41015-0fc1-43a9-9e53-20da460e1f4a&autoAuth=true&ctid=7da8c524-48b4-4a3d-b1fb-7e8b1c7c73a5)
![Report GIF](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/2ae51923ed44d157510a3698db5bb428bd2d605d/Report2.gif)

# Table of Contents
- [Introduction](#company-xyz-introduction)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Backend Overview](#backend-overview)
## Company XYZ Introduction

Company XYZ, based in North Carolina, is a retail company that offers a diverse range of consumer products across multiple locations on both the east and west coasts. The company has a strong membership program that distinguishes between members and non-members, providing exclusive offers and promotional benefits to its loyal customers.


# Key Insights

## 1. Product Performance

- **Top-Performing Products:**
  - **Product D** stands out as the most profitable product, generating **$54M** in profit from **$112M** in revenue. It has a strong customer base, with a total of **1.4M** customers.
  - **Product C** also shows strong performance, contributing **$34M** in profit from **$80M** in revenue.

- **Underperforming Products:**
  - **Product B** is significantly underperforming, with a negative profit of **-$5M**. The primary cause of this underperformance seems to be linked to west-coast locations, where the majority of the losses are concentrated. This regional impact appears to be the key factor driving Product B’s overall negative performance.
  - **Product A** is generating minimal profit of **$1M**. The positive profit is primarily driven by east-coast locations, while west-coast locations are contributing to the overall performance with negative profit.
  - **Product E** is also yielding minimal profit, with only **$270K** in total. Like Product A, the positive profit is coming from east-coast locations, while west-coast locations are dragging down overall performance with negative profit contributions.

## 2. Regional Performance

- **Top-Performing Location:**
  - **Location 1** is the most profitable, contributing **$39M** in profit from **$73M** in revenue. This location has the highest number of buyers (**1.2M**), indicating home-state advantage.

- **Underperforming Location:**
  - **Location 5** generates the lowest profit, with **$4M** from **$52M** in revenue, despite serving a moderate customer base of **877K**. This may indicate higher operational costs or less favorable market conditions, likely influenced by the location's distance from Company XYZ’s home state of North Carolina.

## 3. Customer Segment Performance

- **Members vs. Non-Members:**
  - **Members** contribute significantly more to the company’s profitability, with a total profit of **$72M** from **$201M** in revenue. They account for **3.4M** customers.
  - **Non-Members** generate a lower profit of **$29M** from **$81M** in revenue, with **1.4M** customers. This shows that member loyalty programs are effective and that members have a higher lifetime value.

## 4. Performance Over Time

- **Seasonal Trends:** Both years exhibit a consistent uptick in customers during the summer months (June-August), leading to increased revenue and profit.
- **Daily Revenue Trends:** Monday generates the lowest average revenue, while Friday, Saturday, and Sunday see significant revenue increases.
- **Critical Periods:** February and November have been identified as potential risk months due to a noticeable decline in customer numbers, impacting revenue and profit.

# Recommendations

## 1. Product Strategy

- **Reevaluate Product B:**
  - Given its significant negative impact on profitability, consider either revising the pricing strategy, reducing costs, or discontinuing the product altogether. A detailed cost-benefit analysis should be conducted to determine the best course of action.

- **Monitor Products A and E:**
  - Although these products are profitable, it's essential to evaluate if additional investment is warranted. Take regional performance into account and explore potential growth opportunities. Track their performance closely over the next few quarters. By year-end, decide whether to launch a new product and phase these out or to significantly invest in them to drive growth.

- **Focus on High-Performing Products:**
  - Increase investment in marketing and inventory for Products C, D, and F as they are driving substantial profits. Consider expanding these product lines or increasing promotional efforts to capitalize on their success.

## 2. Regional Strategy

- **East-Coast Expansion:**
  - Given the strong performance of east-coast locations, consider allocating more resources to expand operations in this region. This could include opening new locations or increasing inventory levels to meet demand.

- **West-Coast Strategy:**
  - For underperforming west-coast locations, conduct a detailed analysis to identify specific factors contributing to lower performance. Potential strategies include targeted marketing campaigns, adjusting product offerings, or revising pricing strategies to better match local market conditions.

## 3. Seasonal Marketing Campaigns

- **Summer Focus:**
  - Capitalize on the observed uptick in customers during the summer months (June-August) by launching targeted marketing campaigns, seasonal promotions, and product launches. This is also an ideal time to introduce new products or services.

- **February and November Risk Mitigation:**
  - As February and November show lower customer engagement, consider implementing strategies to drive traffic during these months. This could include special promotions, bundling products, or increasing advertising spend to counteract the downturn.

## 4. Customer Engagement

- **Enhance Member Programs:**
  - Given the higher profitability of members, consider enhancing loyalty programs, offering exclusive benefits, and running targeted campaigns to increase member engagement. This could further boost revenue and profit.

- **Convert Non-Members to Members:**
  - Develop strategies to convert non-members into members, such as offering membership discounts, showcasing the value of membership, or running limited-time membership drives. Increasing the member base would significantly impact profitability.

## 5. Operational Efficiency

- **Monitor Cost Structures:**
  - Regularly review the cost structures associated with each product and location to identify opportunities for cost savings. Focus on improving operational efficiency in underperforming areas.

- **Weekend Promotions:**
  - With Friday, Saturday, and Sunday showing significant revenue increases, consider implementing special promotions or extended hours during these days to maximize revenue.

- **Monday Optimization:**
  - Explore strategies to boost Monday sales, such as offering Monday-only discounts, promotions, or loyalty rewards, to improve overall weekly performance. If no viable strategies are identified, consider closing all locations on Mondays and converting to online transactions.

## 6. Data-Driven Decision Making

- **Continuous Monitoring:**
  - Implement regular performance reviews and data analysis to ensure that strategies are responsive to evolving market conditions. Use the insights gained to make timely adjustments to operations, marketing, and product management.

- **Customer Feedback:**
  - Gather and analyze customer feedback, especially in underperforming regions or product lines, to inform decisions and improve offerings.

# Backend Overview

### Data Overview

The data provided for Company XYZ covers a two-year period and includes detailed transactional records, cost structures, and performance metrics across various products and locations. This data was sourced from the Finance and Accounting department through NetSuite, transformed using Microsoft SQL Server Management Studio, and then loaded into PowerBI Desktop for analysis. The datasets consist of:

1. **Transactional Data for 2021 and 2022:**
   - **Details:** Includes daily sales data broken down by product type, customer type (Member or Non-Member), and location. This data also captures seasonal trends, weekday performance, and hourly sales.
   
2. **Product Cost Data:**
   - **Details:** Provides insights into the pricing, cost of goods sold (COGS), and associated profitability for each product type sold by Company XYZ.

3. **Location-Specific Operational Costs:**
   - **Details:** Includes fixed costs such as rent and utilities for each store location, which are essential for understanding the overall profitability of each geographical area.

[Project Year 1 CSV](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/10e2ca03f7ca028e81e6103ca85cae7d33b8a2d3/Project_year_1.csv)

| dteday    | season | yr | mnth | hr | holiday | weekday | workingday | buyer_type  | Product_Type | buyers | Location   |
|-----------|--------|----|------|----|---------|---------|------------|-------------|--------------|--------|------------|
| 1/1/2021  | 1      | 0  | 1    | 0  | 0       | 6       | 0          | Non-Member  | D            | 87     | Location 1 |
| 1/1/2021  | 1      | 0  | 1    | 1  | 0       | 6       | 0          | Member      | D            | 6      | Location 3 |
| 1/1/2021  | 1      | 0  | 1    | 2  | 0       | 6       | 0          | Member      | F            | 121    | Location 5 |

[Project Year 2 CSV](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/10e2ca03f7ca028e81e6103ca85cae7d33b8a2d3/Project_year_2.csv)

| dteday    | season | yr | mnth | hr | holiday | weekday | workingday | buyer_type | product_type | buyers | Location   |
|-----------|--------|----|------|----|---------|---------|------------|------------|--------------|--------|------------|
| 1/1/2022  | 1      | 1  | 1    | 0  | 0       | 0       | 0          | Member     | D            | 125    | Location 4 |
| 1/1/2022  | 1      | 1  | 1    | 1  | 0       | 0       | 0          | Member     | E            | 96     | Location 1 |
| 1/1/2022  | 1      | 1  | 1    | 2  | 0       | 0       | 0          | Member     | F            | 48     | Location 5 |

[Project Cost Table 1](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/10e2ca03f7ca028e81e6103ca85cae7d33b8a2d3/Project_cost_table_1.csv)

| product_type | price | COGS  |
|--------------|-------|-------|
| A            | 37.29 | 12.41 |
| B            | 15.68 |  5.29 |
| C            | 84.00 | 26.73 |
| D            | 77.82 | 19.52 |
| E            | 28.90 |  6.92 |
| F            | 53.46 | 15.64 |

[Project Cost Table 2](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/10e2ca03f7ca028e81e6103ca85cae7d33b8a2d3/Project_cost_table_2.csv)

| Location   | Rent | Utilities |
|------------|------|-----------|
| Location 2 | 1400 | 751       |
| Location 4 | 2500 | 1009      |
| Location 3 | 1350 | 772       |
| Location 1 | 1250 | 703       |
| Location 5 | 3500 | 1321      |

[SQL Query](https://github.com/jjguatno/CompanyXYZ_Analysis/blob/10e2ca03f7ca028e81e6103ca85cae7d33b8a2d3/Project_Query.sql)

```sql
WITH cte AS (
    SELECT dteday, weekday, yr, hr, buyer_type, product_type, buyers, Location
    FROM [Project_year_1]
    UNION ALL
    SELECT dteday, weekday, yr, hr, buyer_type, product_type, buyers, Location
    FROM [Project_year_2]
)
SELECT 
    CASE
        WHEN weekday = 0 THEN 'Monday'
        WHEN weekday = 1 THEN 'Tuesday'
        WHEN weekday = 2 THEN 'Wednesday'
        WHEN weekday = 3 THEN 'Thursday'
        WHEN weekday = 4 THEN 'Friday'
        WHEN weekday = 5 THEN 'Saturday'
        WHEN weekday = 6 THEN 'Sunday'
    END AS DayName,
    CASE    
        WHEN yr = 0 THEN '2021'
        WHEN yr = 1 THEN '2022'
    END AS YrFormatted,
    CASE
        WHEN hr = 0 THEN '12 AM'
        WHEN hr < 12 THEN CONCAT(hr, ' AM')
        WHEN hr = 12 THEN '12 PM'
        WHEN hr > 12 THEN CONCAT(hr - 12, ' PM')
    END AS HrFormatted,
    hr,
    weekday,
    dteday,
    buyer_type,
    a.product_type,
    buyers,
    a.Location,
    ROUND(a.buyers * b.price, 2) AS revenue,
    ROUND(a.buyers * b.price - b.COGS * a.buyers - c.Rent - c.Utilities, 2) AS profit
FROM 
    cte a
LEFT JOIN 
    Project_cost_table_1 b ON a.product_type = b.product_type
LEFT JOIN
    Project_cost_table_2 c ON a.Location = c.Location;





