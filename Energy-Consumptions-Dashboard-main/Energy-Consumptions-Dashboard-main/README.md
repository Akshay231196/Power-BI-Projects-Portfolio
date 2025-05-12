**Energy Consumption Dashboard**: 
This Power BI project aimed to analyze energy usage and cost trends across U.S. cities and buildings over a 4-year period (2016–2019). Below is a breakdown of the step-by-step approach followed in building the dashboard:

**🧾 1. Data Understanding**
Explored the dataset which included energy consumption records categorized by:

City
Building
Consumption Type (Water, Gas, Electricity)
Date
Unit Consumed
Total Cost

**🧹 2. Data Preparation (Power Query)**
Cleaned and transformed raw data in Power BI using Power Query:

Renamed columns for clarity
Converted and split dates into Year, Month, and Quarter
Handled null or missing values
Ensured numeric consistency for cost and unit columns

**🧩 3. Data Modeling**
Established a data model using a star schema:
One fact table (Energy Consumption)
Supporting dimensions (Date, City, Building)
Defined relationships to enable cross-filtering

**🧮 4. Measure Creation (DAX)**
Created custom DAX measures to support key insights:
Total Cost
Total Unit Consumed
Min/Max Cost by City
Percentage Difference
Cost by Utility Type
Designed slicers for interactive filtering by date, city, building, and consumption type

**📊 5. Visualization**
Built a multi-page Power BI report:

**📌 Overview Dashboard**
KPI cards for total metrics
Map for total cost by city
Clustered column chart for cost trend by type
Donut and bar charts for unit distribution
Smart Narrative for automatic insights

**💧 Utility-Specific Dashboards**
Separate views for Water, Gas, and Electricity
Line graphs showing monthly cost changes
Table visual showing detailed breakdowns
City- and building-level cost summaries

**💡 6. Insights Delivered**
New York had the highest total cost: $4.33M
Houston recorded the lowest: $1.44M
Water accounted for 88% of all units consumed
Gas showed notable seasonal cost fluctuations
Building-level performance differences were clearly visualized

**🚀 Tools Used**
Power BI
Power Query
DAX
Smart Narrative Visual
