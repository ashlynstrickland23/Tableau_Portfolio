# Superstore Sales and Profitability Dashboard in Tableau

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-1E90FF?style=for-the-badge)
![Dashboard Design](https://img.shields.io/badge/Dashboard_Design-228B22?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-4B0082?style=for-the-badge)
![KPI Reporting](https://img.shields.io/badge/KPI_Reporting-DC143C?style=for-the-badge)
![Geographic Analysis](https://img.shields.io/badge/Geographic_Analysis-4682B4?style=for-the-badge)
![Profitability Analysis](https://img.shields.io/badge/Profitability_Analysis-FF8C00?style=for-the-badge)
![Trend Analysis](https://img.shields.io/badge/Trend_Analysis-6A0DAD?style=for-the-badge)

This Tableau project analyzes sales performance, profitability, discounts, customer profitability, subcategory performance, and geographic sales trends using Tableau Superstore sample data.

The dashboard was designed to help business users identify where sales are strong, where profit is weak, which customers are most valuable, and where discounting may be affecting profitability.

> **Data Note:** This project uses Tableau Superstore sample data for portfolio demonstration purposes. It does not contain private client data or real customer personal data.

---

## Project Preview

### Profits by Location Dashboard

<img src="images/profits_by_location.png" width="900">

### Key Metric Trends Dashboard

<img src="images/key_metric_trends.png" width="900">

### Sales vs Profit Analysis

<img src="images/sales_vs_profit.png" width="900">

---

## Business Problem

Sales leaders need more than total revenue. They need to understand whether sales are profitable, which regions are contributing the most, which customers are driving profit, and whether discounts are helping or hurting the business.

This dashboard answers:

* Where are sales and profit strongest geographically?
* Which customers generate the most profit?
* Which categories and subcategories are contributing to profit?
* Are sales and profit increasing over time?
* Are discounts affecting profit ratio?
* Where do high sales not convert into strong profit?

---

## Dashboard Analysis

### 1. Geographic profitability

The location dashboard shows that profit is not evenly distributed across the United States. Large profitable markets appear in states such as California and New York, while other states show weaker or negative profit performance.

The map makes it easy to identify where the business is generating strong returns and where leadership may need to review pricing, discounts, or product mix.

A key insight from the New York tooltip is that New York generated:

| Metric | Value |
|---|---:|
| Profit | $74,039 |
| Sales | $310,876 |
| Profit Ratio | 23.82% |

This shows that New York is not only generating high sales, but also converting those sales into strong profit.

---

### 2. Sales versus profit relationship

The sales versus profit scatter plot compares sales and profit across states, categories, and segments.

Most marks cluster near the lower sales and lower profit area, which means many locations or segments produce smaller order volume. A few outliers have much higher sales and profit, which may represent high value states, categories, or customer groups.

The scatter plot also shows that higher sales do not always guarantee higher profit. Some marks with strong sales still fall near or below the zero profit line, which suggests that discounting, product mix, or cost structure may be reducing margin.

---

### 3. Customer profitability

The customer profitability view ranks customers by profit and sales. This makes it easy to identify the customers that are most valuable to the business.

Top customers shown in the dashboard include:

| Customer | Profit | Sales |
|---|---:|---:|
| Tamara Chand | $8,981 | $19,052 |
| Raymond Buch | $6,976 | $15,117 |
| Sanjit Chand | $5,757 | $14,142 |
| Hunter Lopez | $5,622 | $12,873 |
| Adrian Barton | $5,445 | $14,474 |

This view helps sales teams prioritize high value customers and understand which accounts are driving meaningful profit, not just revenue.

---

### 4. Key metric trends

The key metric trends dashboard shows overall performance across sales, profit, average discount, median discount, and profit ratio.

The dashboard shows:

| Metric | Value |
|---|---:|
| Total Sales | $2.3M |
| Total Profit | $286.4K |
| Average Discount | 15.62% |
| Median Discount | 20.00% |
| Profit Ratio | 12.47% |

The trend charts show that sales increased over time, especially toward the end of the period. Profit also fluctuates by category, with Technology and Office Supplies appearing stronger than Furniture in several periods.

The profit ratio chart helps show that revenue growth alone is not enough. The business also needs to monitor margin quality and discount behavior.

---

### 5. Subcategory profitability

The subcategory profitability view highlights where product level performance differs. Some subcategories contribute positively to profit, while others show negative profit.

This is important because a business may see strong category sales overall but still have specific subcategories that are reducing margin. These areas may need pricing review, discount review, or product strategy changes.

---

## Key Insights

| Insight | Business Meaning |
|---|---|
| New York shows strong profit and a high profit ratio | This state appears to be a high value market |
| Sales and profit are positively related but not perfectly aligned | Higher revenue does not always mean stronger profitability |
| Several customers generate large profit contributions | Customer level ranking can support account prioritization |
| Total sales reached $2.3M and total profit reached $286.4K | The business has strong revenue volume but should monitor margin quality |
| Median discount is 20.00% | Discounting is a meaningful part of the sales strategy |
| Some subcategories appear unprofitable | Product level margin review may be needed |

---

## Tableau Features Used

* Interactive dashboard layout
* Map visualization
* Sales and profit scatter plot
* Customer profitability table
* Subcategory profitability chart
* KPI cards
* Trend charts
* Filters by region and year
* Tooltips
* Category and segment color encoding
* Dashboard actions and highlighting

---

## Skills Demonstrated

![Interactive Dashboards](https://img.shields.io/badge/Interactive_Dashboards-228B22?style=for-the-badge)
![Map Visualization](https://img.shields.io/badge/Map_Visualization-4682B4?style=for-the-badge)
![Scatter Plot Analysis](https://img.shields.io/badge/Scatter_Plot_Analysis-6A0DAD?style=for-the-badge)
![KPI Cards](https://img.shields.io/badge/KPI_Cards-DC143C?style=for-the-badge)
![Customer Profitability](https://img.shields.io/badge/Customer_Profitability-FF8C00?style=for-the-badge)
![Trend Analysis](https://img.shields.io/badge/Trend_Analysis-008080?style=for-the-badge)

This project demonstrates:

* Tableau dashboard design
* Geographic sales and profit analysis
* Customer profitability analysis
* Subcategory profitability analysis
* KPI reporting
* Discount and profit ratio analysis
* Trend analysis over time
* Interactive filtering
* Business intelligence storytelling

---

## Business Recommendations

Based on the dashboard analysis, business leaders could:

* Review low profit or negative profit states
* Study high performing markets such as New York to understand what is working
* Prioritize top profit customers for retention and account management
* Review subcategories with negative profit
* Monitor discounting because the median discount is 20.00%
* Use profit ratio alongside sales to avoid rewarding revenue that does not generate margin

---

## Files Included

| Folder or File | Description |
|---|---|
| `images/profits_by_location.png` | Main dashboard showing geographic profit, sales versus profit, and customer profitability |
| `images/key_metric_trends.png` | KPI and trend dashboard showing sales, profit, discounts, and profit ratio |
| `images/sales_vs_profit.png` | Scatter plot showing sales versus profit by category, segment, and state |
| `workbook/superstore_sales_profitability_dashboard.twbx` | Packaged Tableau workbook file |
| `data/` | Sample data folder if included |
| `README.md` | Project documentation |

---

## Portfolio Note

This project is part of my Tableau Portfolio and supports my broader work in business intelligence, data visualization, dashboard development, SQL, Python, R, and Power BI.

[Back to Tableau Portfolio](../README.md)
