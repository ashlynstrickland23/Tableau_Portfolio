# Order Priority Analysis Dashboard in Tableau

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-1E90FF?style=for-the-badge)
![Dashboard Design](https://img.shields.io/badge/Dashboard_Design-228B22?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-4B0082?style=for-the-badge)
![Order Analysis](https://img.shields.io/badge/Order_Analysis-FF8C00?style=for-the-badge)
![Trend Analysis](https://img.shields.io/badge/Trend_Analysis-6A0DAD?style=for-the-badge)
![Interactive Filters](https://img.shields.io/badge/Interactive_Filters-008080?style=for-the-badge)

This Tableau project analyzes sales, profit, monthly trends, and category performance by order priority.

---

## Business Problem

Operations and sales leaders need to understand how order priority affects sales volume, profitability, category performance, and monthly demand patterns.

This dashboard answers:

* Which order priority groups contribute the most sales?
* How do sales and profit vary across order priority levels?
* Which categories drive sales within each priority group?
* How does monthly sales performance change by priority level?
* Are high priority orders producing meaningfully higher revenue?
* Are lower priority orders still important to category performance?

---

## Project Preview and Analysis

### All Order Priorities

<img src="images/order_priority_all.png" width="900">

This view shows the full order priority dashboard across all priorities and all years. Medium and High priority orders appear to drive the largest share of sales activity, while Critical and Low priority orders are much smaller by comparison.

The category bar chart shows Technology as the strongest category overall, followed by Furniture and Office Supplies. The monthly sales trend shows that sales generally increase over time, with stronger performance toward the later years.

The scatter plot shows many orders clustered around lower sales values, but it also shows several outliers. Some orders generate high sales and profit, while others show negative profit. This reinforces that order priority analysis should include both sales volume and profitability.

---

### Low Priority Orders in 2020

<img src="images/order_priority_low_2020.png" width="900">

This filtered view focuses on Low priority orders in 2020. The overall sales volume is much smaller than the High priority view, but Low priority orders still contribute across all three major categories.

Approximate category sales in this view are:

| Category | Approximate Sales |
|---|---:|
| Office Supplies | About $70K |
| Furniture | About $65K |
| Technology | About $62K |

The monthly trend shows sales fluctuating through the year, with a dip around July and stronger activity later in the year. This suggests that Low priority orders may be less predictable but still contribute meaningful category sales.

---

### High Priority Orders in 2020

<img src="images/order_priority_high_2020.png" width="900">

This filtered view focuses on High priority orders in 2020. Sales are much higher than the Low priority view, especially across Technology and Furniture.

Approximate category sales in this view are:

| Category | Approximate Sales |
|---|---:|
| Technology | About $500K |
| Furniture | About $455K |
| Office Supplies | About $380K |

The monthly sales line shows stronger growth in the second half of 2020, with November reaching about **$156K**. This suggests that High priority orders became especially important later in the year.

This view shows that high priority orders require close operational attention because they represent much larger sales volume and may drive fulfillment pressure.

---

## Key Insights

| Insight | Business Meaning |
|---|---|
| Medium and High priority orders dominate total sales | These groups likely require the most operational focus |
| High priority orders produce much higher sales than Low priority orders | Priority level is strongly tied to sales volume |
| Technology leads High priority sales | Technology orders may require stronger fulfillment planning |
| Low priority orders still contribute across major categories | Lower priority orders still matter for total category performance |
| Some orders show negative profit | Pricing, discounts, or fulfillment costs may need review |
| November 2020 was strong for High priority sales | Seasonal or operational demand patterns may exist |

---

## Dashboard Features

| Feature | Description |
|---|---|
| Order priority filter | Lets users focus on Critical, High, Medium, or Low priority orders |
| Year filter | Allows users to analyze order priority performance by year |
| Sales and profit scatter plot | Shows relationship between sales and profit per order |
| Sales by order priority | Compares category sales across priority groups |
| Monthly sales trend | Shows how sales change over time |
| Interactive highlighting | Lets users select a priority group from the legend to highlight related marks |

---

## Tableau Features Used

* Interactive filters
* Priority based filtering
* Sales and profit scatter plot
* Category bar chart
* Monthly sales line chart
* Tooltips
* Legend based highlighting
* Dashboard layout design
* Color encoding by priority group

---

## Skills Demonstrated

![Interactive Dashboard](https://img.shields.io/badge/Interactive_Dashboard-228B22?style=for-the-badge)
![Sales Analysis](https://img.shields.io/badge/Sales_Analysis-1E90FF?style=for-the-badge)
![Profit Analysis](https://img.shields.io/badge/Profit_Analysis-DC143C?style=for-the-badge)
![Trend Analysis](https://img.shields.io/badge/Trend_Analysis-6A0DAD?style=for-the-badge)
![Filtering](https://img.shields.io/badge/Filtering-008080?style=for-the-badge)
![Data Storytelling](https://img.shields.io/badge/Data_Storytelling-8A2BE2?style=for-the-badge)

* Tableau dashboard design
* Order priority analysis
* Sales and profit analysis
* Category performance comparison
* Monthly trend analysis
* Interactive filtering
* Tooltip design
* Business intelligence storytelling

---

## Business Recommendations

Based on the dashboard analysis, business leaders could:

* Monitor High and Medium priority orders closely because they drive the largest sales volume
* Review negative profit orders to understand whether discounts or fulfillment costs are reducing margin
* Plan capacity around High priority orders because they show larger monthly sales patterns
* Review Technology order trends because Technology appears to lead sales in High priority orders
* Continue tracking Low priority orders because they still contribute across all major categories

---

## Files Included

| Folder or File | Description |
|---|---|
| `images/order_priority_all.png` | Dashboard view showing all order priorities |
| `images/order_priority_low_2020.png` | Dashboard filtered to Low priority orders in 2020 |
| `images/order_priority_high_2020.png` | Dashboard filtered to High priority orders in 2020 |
| `data/` | Sample data folder if included |
| `README.md` | Project documentation |

---

## Portfolio Note

This project is part of my Tableau Portfolio and supports my broader work in business intelligence, data visualization, dashboard development, SQL, Python, R, and Power BI.

[Back to Tableau Portfolio](../README.md)
