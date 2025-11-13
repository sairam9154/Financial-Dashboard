# Financial-Dashboard
This project presents an interactive Power BI dashboard designed to visualize company profit performance across multiple dimensions — products, countries, and segments. It provides executives and analysts with actionable insights into profitability distribution and trends.


# Project Overview
  Goal: To analyze and visualize key financial metrics, specifically Sales and Profit, across different products, countries, and market segments for the years 2013 and 2014.
  Key Deliverables: Interactive Sales Dashboard and Profit Dashboard (as shown in screenshots).
  Tool: [Specify the tool you used, e.g., Power BI, Tableau, Excel]


# Key Findings & Insights
  
 1.Data Source and Methodology
Data: [Describe the dataset, e.g., Sample Superstore Data, Mock Financial Records].
Data Preparation: [Briefly mention steps, e.g., Data cleaning, creating calculated columns for profit margin, aggregating to annual/segment level].
Calculations/Measures Used (Examples): Sum of Sales, Sum of 
Profit, Profit Margin (Profit / Sales), Percentage of Total Sales/Profit.

##2.Setup & Usage
   Prerequisites: [List any software needed, e.g., Power BI Desktop, Python 3.x, specific libraries].

## 3.Steps to Run Locally:
Clone this repository: git clone [repository link]
Open the project file ([your-file-name].pbix or similar) in [Your Tool].
Refresh the data source if needed.

## 4. Future Enhancements
Add time-series analysis (e.g., month-over-month or quarter-over-quarter trends).
Incorporate cost of goods sold (COGS) to calculate Gross Profit more accurately.
Implement 'What-If' scenario analysis.

# HOW TO CREATE REPORT
1. load the data set into power bi and extract the data
2. create some charts ,pie ,slicers,donut  using data fields like(sales,profit,category,segments)
3. next  create measures  using dax functions  like gross sales , growth% .
4. IN single dashboard contain 2 reports using (bookmarks , selectivity(hide or show).
5. final  I add image to link the  website using website url.

# REPORTS

<img width="1305" height="726" alt="Screenshot 2025-11-12 191530" src="https://github.com/user-attachments/assets/b021ebb8-818c-4352-8eb9-661af905a4c8" />

<img width="1819" height="980" alt="Screenshot 2025-11-12 183917" src="https://github.com/user-attachments/assets/ba83dd72-120a-4a91-837f-bda3b55aef91" />




## Primary Insights
Overall Sales vs. Profit: A high sales volume ($118.73M) yields a relatively low total profit ($16.89M), indicating a low overall Profit Margin (approx. 14.2%).

Product Performance:
Paseo is the Top Selling Product by volume ($33M), and also the Top Profitable Product ($4.8M).
Carretera is the Lowest Selling Product by volume ($14M), and also the Lowest Profitable Product ($1.8M).
VTT, Velo, and Amarilla have high sales volume but lower profit compared to Paseo, suggesting lower margins or higher operating costs for these lines.

Country Performance:
USA has the Highest Sales ($25M) but is only the 4th most profitable ($3.0M).
France has the 3rd highest sales ($24M) but is the Most Profitable ($3.8M), suggesting French sales are made at significantly higher margins.

Segment Performance:
The Small Business segment dominates Sales (44.22% or $52.5M) but the Government segment dominates Profit (65.04% or $11.39M). This suggests that Government contracts are extremely profitable, despite representing a much smaller share of the total sales volume.

Product & Segment Mix:
The highest absolute profit is likely coming from Paseo sold to the Government segment ($3.1M) or a combination of products in the dominant Government segment.


# Questions 
Which product (e.g., Paseo, VTT, Velo) is the most crucial for total Sales volume?
Which product generates the highest total Profit and provides the best profit margin?
Why does Carretera have the lowest sales ($14M) and profit ($1.8M)? Are there specific geographic or segment factors driving this underperformance?
How can the high sales volume of products like VTT and Velo be converted into higher profit margins?

# Conclusion
The business is successful at driving high sales volumes, with Paseo being the clear flagship product. However, there is a significant disparity between sales volume and profitability across different geographies and market segments. The Government segment and the French market are disproportionately critical to the company's profitability. Future strategy should focus on:
Investigating and replicating the high-margin success factors of the Government Segment and the France market to other segments and countries.
Analyzing the cost structure of high-sales, low-margin products like VTT and Velo to identify opportunities for profit improvement.

