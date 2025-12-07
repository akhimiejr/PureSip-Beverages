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


