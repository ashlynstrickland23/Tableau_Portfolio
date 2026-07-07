# LATAM RM Performance Dashboard in Tableau

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-1E90FF?style=for-the-badge)
![Dashboard Design](https://img.shields.io/badge/Dashboard_Design-228B22?style=for-the-badge)
![Sales Analysis](https://img.shields.io/badge/Sales_Analysis-FF8C00?style=for-the-badge)
![Performance Management](https://img.shields.io/badge/Performance_Management-6A0DAD?style=for-the-badge)
![KPI Reporting](https://img.shields.io/badge/KPI_Reporting-DC143C?style=for-the-badge)
![Goal Tracking](https://img.shields.io/badge/Goal_Tracking-228B22?style=for-the-badge)
![Profitability Analysis](https://img.shields.io/badge/Profitability_Analysis-4682B4?style=for-the-badge)

This Tableau dashboard analyzes LATAM relationship manager performance across yearly sales, sales goals, bonus outcomes, profit ratio, and profits versus discounts.

The dashboard helps sales leaders compare RM performance, evaluate goal attainment, identify bonus outcomes, review profit ratio by category and subcategory, and understand whether discounting is affecting profitability.

> **Data Note:** This project uses sample data for portfolio demonstration purposes only. It does not contain private business data, client data, or real personal data.

---

## Project Preview

### LATAM RM Performance Overview

<img src="images/latam_rm_performance_overview.png" width="900">

### LATAM RM Performance Filtered to Technology

<img src="images/latam_rm_performance_technology.png" width="900">

### LATAM RM Performance Full Dashboard View

<img src="images/latam_rm_performance_full_dashboard.png" width="900">

---

## Business Problem

Sales leaders need to evaluate relationship manager performance in a way that balances sales growth, goal achievement, bonus eligibility, discount behavior, and profitability.

This dashboard answers:

* Which relationship managers are driving the most sales?
* Which relationship managers met or missed 2020 sales goals?
* Who earned a bonus based on performance?
* Which RM has the strongest profit ratio?
* Which product categories and subcategories have weak profitability?
* Are discounts reducing profit outcomes?
* How does performance change when filtering by category and segment?

---

## Dashboard Analysis

### 1. Yearly sales trend

The yearly sales chart compares sales performance by RM from 2017 through 2020.

The overall view shows that Chuck Magee, Jack Lebron, and Anna Andreadi all reached similar sales levels by 2020, while Giulietta Dortch remained lower than the other RMs.

Chuck Magee shows strong growth over time, increasing from under $100K in 2017 to more than $200K in 2020. Jack Lebron also shows strong growth and reaches nearly $200K by 2020.

This trend view helps leadership see both year end results and sales trajectory.

---

### 2. 2020 sales goal and bonus performance

The 2020 RM Bonus table shows that Chuck Magee and Jack Lebron exceeded their sales goals and earned bonuses.

| RM | 2020 Sales | 2020 Sales Goal | Delta | 2020 Bonus |
|---|---:|---:|---:|---:|
| Chuck Magee | $211,618 | $197,918 | 6.9% | $21,162 |
| Jack Lebron | $195,480 | $181,015 | 8.0% | $19,548 |
| Giulietta Dortch | $105,492 | $111,262 | -5.2% | $0 |
| Anna Andreadi | $194,043 | $203,086 | -4.5% | $0 |

The sales goal chart confirms that Chuck and Jack met their goals, while Anna and Giulietta missed theirs.

A key business insight is that Anna had sales close to Jack, but missed goal because her target was higher. This shows why sales goal context matters when evaluating performance.

---

### 3. Profit ratio by RM and subcategory

The 2020 RM Profit Ratio heatmap shows profitability by RM, category, and subcategory.

In the full view, Jack Lebron has the strongest grand total profit ratio at 16.0%, followed by Giulietta Dortch at 11.9%, Anna Andreadi at 8.6%, and Chuck Magee at 6.0%.

| RM | Grand Total Profit Ratio |
|---|---:|
| Jack Lebron | 16.0% |
| Giulietta Dortch | 11.9% |
| Anna Andreadi | 8.6% |
| Chuck Magee | 6.0% |

This creates an important performance tradeoff. Chuck had the highest 2020 sales and earned the largest bonus, but Jack had the strongest overall profit ratio. Leadership may want to evaluate both sales volume and profitability, not just sales goal attainment.

---

### 4. Technology category analysis

When filtered to Technology, Chuck Magee leads 2020 Technology sales with $79,074 against a goal of $59,393, exceeding goal by 33.1% and earning a $7,907 bonus.

| RM | Technology 2020 Sales | Technology Goal | Delta | Bonus |
|---|---:|---:|---:|---:|
| Chuck Magee | $79,074 | $59,393 | 33.1% | $7,907 |
| Jack Lebron | $70,254 | $72,151 | -2.6% | $0 |
| Giulietta Dortch | $36,452 | $40,423 | -9.8% | $0 |
| Anna Andreadi | $65,002 | $75,130 | -13.5% | $0 |

The Technology profit ratio heatmap shows Jack Lebron with the strongest Technology profit ratio at 22.6%, while Chuck Magee has 8.0%.

This suggests Chuck drove the most Technology sales, but Jack achieved better profitability.

---

### 5. Profits versus discounts

The profits versus discounts scatter plot shows the relationship between discount percentage and profit.

Many marks at higher discounts appear near or below zero profit. This suggests that heavier discounting may be reducing profitability, especially at discount levels around 40% to 70%.

This is important because an RM can still generate strong sales while discounting too heavily and weakening margin.

---

## Key Insights

| Insight | Business Meaning |
|---|---|
| Chuck Magee had the highest 2020 sales and largest bonus | Strong sales performance and goal achievement |
| Jack Lebron had the strongest overall profit ratio at 16.0% | Strong margin performance despite slightly lower sales than Chuck |
| Anna Andreadi had high sales but missed goal | Goal context matters when evaluating performance |
| Giulietta Dortch had the lowest 2020 sales and missed goal | May need sales coaching or pipeline review |
| Technology sales were strongest for Chuck | Chuck performed especially well in Technology volume |
| Jack had the strongest Technology profit ratio | Jack may be selling with stronger pricing or margin discipline |
| Higher discounts appear connected to weaker profit outcomes | Discounting strategy should be reviewed |

---

## Dashboard Features

| Feature | Description |
|---|---|
| Category filter | Lets users focus on a specific product category or view all categories |
| Segment filter | Lets users analyze performance by customer segment |
| Yearly sales trend | Compares sales growth by RM across years |
| 2020 RM profit ratio heatmap | Shows profit ratio performance by subcategory and RM |
| 2020 RM bonus table | Compares 2020 sales, goals, delta, and bonus by RM |
| 2020 sales goal chart | Highlights whether each RM met or missed goal |
| 2020 profits vs discounts scatter plot | Shows the relationship between discount level and profit |
| Legend highlight action | Allows the user to highlight an RM across the dashboard |

---

## Tableau Features Used

* Interactive filters
* Highlight actions
* Multi view dashboard layout
* Sales trend line chart
* Heatmap style profit ratio matrix
* Performance summary table
* Goal comparison bar chart
* Scatter plot analysis
* KPI oriented dashboard storytelling
* Custom formatting
* Dark dashboard theme

---

## Skills Demonstrated

![Dashboard Development](https://img.shields.io/badge/Dashboard_Development-228B22?style=for-the-badge)
![Sales Performance Analysis](https://img.shields.io/badge/Sales_Performance_Analysis-1E90FF?style=for-the-badge)
![Goal Tracking](https://img.shields.io/badge/Goal_Tracking-DC143C?style=for-the-badge)
![Bonus Analysis](https://img.shields.io/badge/Bonus_Analysis-FF8C00?style=for-the-badge)
![Profitability Analysis](https://img.shields.io/badge/Profitability_Analysis-6A0DAD?style=for-the-badge)
![Discount Analysis](https://img.shields.io/badge/Discount_Analysis-4682B4?style=for-the-badge)
![Data Storytelling](https://img.shields.io/badge/Data_Storytelling-8A2BE2?style=for-the-badge)

This project demonstrates:

* Tableau dashboard design
* Sales performance analysis
* RM performance reporting
* Goal attainment tracking
* Bonus analysis
* Profit ratio analysis
* Discount impact analysis
* Interactive filtering
* Heatmap style performance comparison
* Scatter plot analysis
* Comparative business reporting
* Visual business storytelling

---

## Business Recommendations

Based on the dashboard analysis, leadership could:

* Recognize Chuck Magee and Jack Lebron for meeting sales goals
* Review Jack Lebron’s approach because he had the strongest profit ratio
* Coach Anna Andreadi on goal attainment since sales were high but below target
* Review Giulietta Dortch’s pipeline and sales strategy
* Investigate subcategories with negative or weak profit ratios
* Review discounting practices where high discounts appear connected to low or negative profit
* Balance bonus decisions with both sales attainment and profit quality

---

## Files Included

| Folder or File | Description |
|---|---|
| `images/latam_rm_performance_overview.png` | Overview dashboard screenshot |
| `images/latam_rm_performance_technology.png` | Dashboard filtered to Technology |
| `images/latam_rm_performance_full_dashboard.png` | Full dashboard screenshot |
| `data/` | Sample data folder if included |
| `README.md` | Project documentation |

---

## Portfolio Note

This project is part of my Tableau Portfolio and supports my broader work in business intelligence, dashboard development, data visualization, SQL, Python, R, and Power BI.

[Back to Tableau Portfolio](../README.md)
