# Sales Order Analysis Dashboard

## TABLE OF CONTENT
- [PROJECT OVERVIEW](# Sales Order Analysis -overview)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [OBJECTIVES/KEY PERFORMANCE INDICATORS](#objectives/key-performance-indicators)
- [DATA PREPROCESSING](#data-preprocessing)
- [DATA ANALYSIS](#data-analysis)
- [DASHBOARD](#dashboard)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

### Sales Order Analysis OVERVIEW
This dashboard provides a detailed analysis of sales performance across years, sales reasons, salespeople and countries. By tracking key metrics such as total sales, YoY growth and average order value. it highlights performance patterns, sales reason effectiveness and regional contributions. The goal is to equip stakeholders with actionable insights that support strategic decision-making, improve sales efficiency and identify area for growth.


### DATA SOURCE & EXTRACTION PROCESS
The dataset was gotten as a project for my internship.(https://docs.google.com/document/d/1gCicL0xMZH1mhm2fDjx0T2ZEwOttLUw9hWLpqQPiSkQ/edit?usp=sharing)

### TOOLS
  The tools used for this project are:
  - Microsoft PowerBi
  - Microsoft Powerpoint

  
### OBJECTIVES/KEY PERFORMANCE INDICATORS
- OBJECTIVES:
To analyze sales trends and customer behavior to uncover growth opportunities and improve business outcomes.


### DATA PREPROCESSING
- Cleaning of the dataset by handling null values.
- Calculation of Average Order value by dividing total sales by order count.
- Calculation of average days to ship by using dated if to get the interval between order date & ship date.
- Sales type breakdown : using if statement to categorize 0 or No salesperson to online and salesperson id to offline.

### Key Performance Indicators (KPIs):
- Total Sales: $140.71M
- Order Count: 31k	
- Average Order Value:4.47k
- Avg days to ship: 7
- Yoy Growth: 29.67%


### DASHBOARD
<img width="1099" height="739" alt="Screenshot 2025-08-20 131939" src="https://github.com/user-attachments/assets/5d25e5f4-da8e-44b7-a1a6-6c2aa1722068" />
<img width="1103" height="744" alt="Screenshot 2025-08-22 111727" src="https://github.com/user-attachments/assets/f78344d1-28da-4884-8aa4-c0a2725130aa" />
<img width="1098" height="742" alt="Screenshot 2025-08-21 141047" src="https://github.com/user-attachments/assets/c472c5dd-737e-422f-997f-bd2a008e4396" />
<img width="1095" height="744" alt="Screenshot 2025-08-20 133524" src="https://github.com/user-attachments/assets/1caf1ead-fdbe-4a0b-b24e-cb527eb5fff5" />
<img width="1103" height="740" alt="Screenshot 2025-08-21 124605" src="https://github.com/user-attachments/assets/25ee36f2-a079-4869-9271-629b4e980927" />


### INSIGHTS
1. Monthly Sales Trend:
-	Aug – sept are peak months in both 2002 & 2003.
-	Oct usually dips, but Nov- Dec performance varies( weak in 2002, stronger in 2003)
- Jan- Apr shows unstable sales, moving up and down.
- Overall, August – September drive the highest revenue making them the most consistent strong period.
       N.B: Analysis is based on fiscal year(July - June)


2. Yearly Sales Trend:
- 2001: $14M , order - 1379 from July- dec.
- 2002: $40m, order – 3692 from Jan – dec.
-	2003: $54m, order – 12,433 from Jan – dec showing our peak year.
- 2004: $32m, order- 13,951 from Jan to July which suggests  a higher growth rate by the end of the year


3. Total Sales by Customer Type:
- Stores contributed $108M(77%), making them the primary driver of overall sales.
- individuals contributed $32M(23%), showing they play a much smaller role in total sales.
- CLV: Store customers generate a high lifetime value than individual  while Individual contributes smaller value but more frequent sales.


4. Total Sales by Customer Type & Products:
  - Stores :
45% of total sales came from bikes, followed by components (23%) and clothing (22%).
- Individual:
67% of total sales came from bikes, then Accessories (25%) but no sales for components.

5. Total Sales by Country:
-	Canada made the highest revenue($21M) with 4,067 orders. 
-	Australia sold more items (6,843 orders) but made $12M. 
-	The UK and France each made about $9M, but the UK had more orders(3219). 
- Germany had the lowest sales at $5M from 2,623 orders.

6.Total Sales by Country & Customer Type:
-	US made the highest sales:
        Stores lead with $72M sales (2,474 orders) the highest revenue.
        Individuals placed the highest orders (9,567) but a lower sales($10.3M).
- Canada is the next strongest market:
          Stores: $19.3M from 692 orders.
          Individuals: 3,375 orders but only $2.1M sales (lowest revenue per order across all markets).
Other countries (AU, FR, GB, DE) shows similar pattern of store(high revenue) and individual(high sales).

### RECOMMENDATIONS
-	Online channels generate higher orders but lower sales value, focus on upselling and bundling to boost purchase volume.
-	Improve data categorization for sales reason and focus more on marketing reason since it generated the lowest sales.
-	Individual customers have lower lifetime value compared to stores, build loyalty programs and offers to improve retention and purchase volume.
-	High performing regions like U.S should remain a priority but also invest in strategies to boost lower-performing regions such as Germany.
-	Prioritize marketing more in August and September to generate more sales.

