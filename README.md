# 1. Introduction
# PureSip-Beverages
PureSip Beverages is a company specializing in the distribution of popular beverage brands like Coke, Fanta, and Sprite. They supply to major retail chains, including Costco, Walgreens, Target, and Walmart
# 1.1 Overview
PureSip Beverages is a growing beverage distribution company supplying popular brands such as Coke, Fanta, Sprite, and other leading soft drinks to major retailers including Costco, Walgreens, Target, and Walmart. As the organisation expanded, sales reporting became increasingly fragmented due to reliance on separate spreadsheets managed by regional managers. To address challenges related to data consolidation, reporting accuracy, and analytical capability, PureSip implemented a Power BI solution using a centralised folder connection and automated refresh, enabling real-time visibility of performance across all locations.
# 1.2 Aim of the Project
The objective of the project was to modernise PureSip’s reporting infrastructure by replacing manual spreadsheet-based reporting with an automated, scalable, and interactive analytics environment. The project aimed to integrate sales data from all regional managers into a centralised system using Power BI folder connections, improve data consistency and accuracy, and provide an analytical platform capable of delivering actionable insights on sales trends, retailer performance, and product-level contribution.
# 1.3 Data Description
Retailer: The name of the retailer where the beverage products was sold, e.g., "Costco" or
"Walmart.“__
•Contact: Name or contact details of the retailer's representative or point of contact__
• Retailer ID: A unique identifier assigned to each retailer for tracking purposes__
• Order Date: The date on which the order was placed by the retailer__
• Payment Date: The date on which the payment for the order was received or processed__
• Region--State: The geographic location of the retailer, including the region and state,
e.g. South-Texas.__
• Beverage Brand: The brand of the beverage sold, e.g. Coca-Cola, Fanta, Sprite etc.__
• Price per Unit: The price charged per unit of the beverage__
• Units Sold: The quantity of beverage units sold in the transaction__
# 2.Analysis
## 2.1 Problem Statement
The use of independently maintained spreadsheets created a siloed reporting environment that lacked consistency, efficiency, and analytical depth. Consolidating multiple spreadsheets into a unified report required manual intervention, making the process slow, error-prone, and dependent on inconsistent data entry practices. The limitations of spreadsheet-based reporting prevented the business from conducting robust trend analysis, geographic performance tracking, and retailer comparison, restricting the organisation’s ability to make timely and strategic decisions.

## 2.2 Using Power BI Desktop and Folder Connections

<img width="743" height="238" alt="Screenshot 2025-12-07 194920" src="https://github.com/user-attachments/assets/5eca6391-f803-456a-8771-1a990a58691c" />

## 2.2.2 KPI Card: KPI Target | Contact
This visual serves as a performance benchmark indicator, comparing the current achieved revenue (£238,850) against the predefined target of £250,000. The inclusion of a numeric variance of -£11,150 and a percentage variance of -4.46% provides immediate context on progress toward goal attainment. The small trend line beneath enhances interpretability by showing how performance has evolved rather than presenting the number in isolation. This makes the KPI card not only a static indicator but a dynamic measure of progression.

<img width="424" height="238" alt="Screenshot 2025-12-07 195444" src="https://github.com/user-attachments/assets/e2d94e61-1f69-4f3a-9791-1de14450eea7" />


## 2.2.3 KPI Overview: Sales, Retailers, and Quantity Sold
The KPI visuals in the report provide a comprehensive view of PureSip Beverages’ operational and financial performance. The Total Sales card communicates a cumulative revenue of £1,213,018, serving as a high-level financial summary for the entire reporting scope. Its accompanying sparkline trend illustrates month-to-month revenue shifts, enabling users to identify whether total sales are improving, declining, or fluctuating, and anchoring the report by establishing the overall scale of financial activity while providing trend insight without requiring drill-down interaction. The Number of Retailers card, represented as “4,” provides operational clarity regarding the distribution network. This KPI focuses on breadth rather than output, allowing users to evaluate operational reach and later compare performance across customers through segmentation visuals. Its simplicity makes it effective for highlighting potential concentration risks or opportunities for market expansion. Finally, the Total Quantity Sold card reports 2,309,850 units, offering a volume-based perspective that complements the financial indicators. The accompanying sparkline demonstrates movement over time, showing whether the volume pattern mirrors revenue trends. This comparison between units and value enables the evaluation of pricing influence, discounting patterns, or product mix effects, providing a holistic view of both financial and operational performance.



<img width="356" height="631" alt="Screenshot 2025-12-07 200016" src="https://github.com/user-attachments/assets/9a8e7be5-9457-4dfe-b9b3-e3e1312ac7c5" />


## 2.2.4 Sales Trend Over Time
This dual-axis visual offers one of the most informative time-based insights in the report. Each month has a bar representing sales volume, while the overlaid line plot shows variance and continuity across the period. Key seasonal progression is observed, with the lowest turn over in Febuary(78.6K) to an August peak (116K). The slight dip in September, October, and November, followed by recovery in December, suggests potential seasonality or market-cycle behaviour. This visual supports forecasting, demand planning, and promotional strategy decisions.

<img width="1146" height="297" alt="Screenshot 2025-12-07 200438" src="https://github.com/user-attachments/assets/af2d6e29-56eb-45e6-b50f-03e02ce5b1f2" />

## 2.2.5 Map Visual: Sales by State (Geospatial Analysis)
This map visual presents regional performance at the state level across North America. Power BI’s geospatial mapping enables geographic correlation, helping identify where sales concentrations are strong and where gaps or underdeveloped territories exist. Regions with higher colour density indicate stronger performance, offering immediate visual cues for sales coverage analysis, potential market expansion, resource reallocation, or territory-based strategic planning.

<img width="515" height="472" alt="Screenshot 2025-12-07 201317" src="https://github.com/user-attachments/assets/177983ea-6244-4a56-8544-226f8fb169b5" />

## Horizontal Bar Charts: Sales by Beverage Brand and Retailer
This combined analysis uses horizontal bar charts to provide a clear comparative view of both product and retailer performance. The beverage brand chart ranks sales by product, highlighting Dasani Water, Coca-Cola, and Diet Coke as top performers, with Sprite, Powerade, and Fanta following. This ranking helps identify which product lines contribute most to total sales, supporting decisions around stock prioritization, promotional focus, and product lifecycle management. Simultaneously, the retailer chart shows the contribution of each customer, with Walmart leading at 391.8K, followed by Costco, Walgreens, and Target. Understanding this hierarchy aids in assessing dependency risk, optimizing partnership strategies, and, when combined with margin data, evaluating profitability across accounts. Power BI’s drill-down capabilities further allow exploration by region, month, or retailer for more granular insights.

<img width="1055" height="467" alt="Screenshot 2025-12-07 201520" src="https://github.com/user-attachments/assets/9b2d78e7-5eda-401e-a4dd-1c99facd42eb" />

## Report
The dashboard provides a comprehensive, filter-driven sales analysis for Pure Sip, incorporating slicers for Beverage Brand and Contact to allow users to tailor the view to specific product lines or customer groups. The KPI panel shows current performance against targets, with sales of £238,850, which is £11,150 below the £250,000 goal (–4.46%). Total sales amount to £1,213,018, supported by 2,309,850 units sold across four retailers. The sales trend visual illustrates month-by-month performance, rising from £82.1K in January to a peak of £116K in August, before stabilising around £115K in December. Below, regional analysis maps sales across key North American states, while brand performance charts identify Dasani Water, Coca-Cola, and Diet Coke as the leading contributors. Retailer analysis highlights Walmart as the top performer with £391.8K, followed by Costco, Walgreens, and Target. Together with the interactive slicers, the dashboard enables dynamic exploration of trends, channel contributions, and performance variations, supporting informed decision-making and targeted strategy refinement.

<img width="1441" height="811" alt="Screenshot 2025-12-07 191117" src="https://github.com/user-attachments/assets/ebcfe365-430a-410e-8c7b-78a211432c1a" />

