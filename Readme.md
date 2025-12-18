 # E-commerce Sales Analysis (Excel)
---


## Project Overview

This project demonstrates an end-to-end data analysis workflow using Microsoft Excel and Power Query.  

The objective was to clean messy real-world e-commerce data, build a proper data model, and deliver an interactive dashboard that supports business decision-making.



The dataset contained inconsistent country names, messy product categories, mixed date formats, and duplicate records.






## Data Cleaning \& Preparation

All data preparation was performed in Power Query, including:

\- Standardizing country names using a mapping (dimension) table

\- Cleaning and categorizing product categories

\- Handling inconsistent date formats

\- Creating Year and Month attributes from order dates

\- Removing duplicates and enforcing data consistency



## Dimension tables created:

\- Country Dimension

\- Product Category Dimension

\- Date attributes (Year, Month)





## Data Model

A star-schema-style data model was implemented using Excel’s Data Model:

\- Fact Table: Orders

\- Dimension Tables: Customers, Products, Countries, Categories



Relationships were configured to enable cross-filtering across all visuals.






## Dashboard Features

The Excel dashboard includes:

\- Year slicer for temporal analysis

\- Country slicer for geographic drill-down

\- Monthly sales trends by year

\- Top-performing product SKUs by revenue

\- Customer purchase volume by country

\- Product category performance by revenue



All visuals update dynamically based on slicer selections.




## Key Insights

\- The United States consistently generates the highest sales volume.

\- Furniture is the top-performing product category by revenue.

\- Product SKU P007 is the highest revenue-generating product.

\- Monthly sales show seasonal patterns with noticeable peaks in specific months.






## Business Recommendations

\- Prioritize inventory and marketing investments in the United States.

\- Expand and optimize high-performing Furniture product lines.

\- Leverage top-performing SKUs to drive bundled promotions and upsell strategies.

\- Use seasonal sales trends to improve demand forecasting and stock planning.





## Tools Used

\- Microsoft Excel

\- Power Query

\- Pivot Tables \& Pivot Charts

\- Excel Data Model (Power Pivot)



## Dashboard Preview



![Dashboard](/screenshots/dashboard-overview.png)






## Files

\- Messy_Ecommerce_Dataset_2022_2025.xlsx – Interactive dashboard and data model

\- /screenshots – Dashboard visuals



