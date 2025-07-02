📊 Blinkit Data Analysis Dashboard
This project provides a detailed analysis of sales data from Blinkit, a quick-commerce grocery delivery platform. Built using Microsoft Power BI, the dashboard offers insights into product performance, outlet characteristics, and sales trends to support data-driven decision-making.

🧾 Project Objective
To design a comprehensive Power BI dashboard that enables business stakeholders to:

Understand product-level and outlet-level sales performance

Identify sales trends and patterns across various dimensions

Make data-backed decisions to optimize inventory and operations

📁 Dataset Overview
The dataset includes the following fields:

Column	Description
Item_Identifier	Unique ID for each product
Item_Weight	Weight of the item (in kilograms)
Item_Fat_Content	Type of fat content (e.g., Low Fat, Regular)
Item_Visibility	Percentage visibility of the item in stores
Item_Type	Category/type of the item
Item_MRP	Maximum Retail Price of the item
Outlet_Identifier	Unique ID for each outlet
Outlet_Establishment_Year	Year of establishment of the outlet
Outlet_Size	Size of the store (Small, Medium, High)
Outlet_Location_Type	Location category (Tier 1, Tier 2, Tier 3)
Outlet_Type	Type of outlet (Grocery Store, Supermarket, etc.)
Item_Outlet_Sales	Sales value of the item at the outlet

📈 Key Dashboard Features
🔹 Sheet 1: Overview Dashboard
Total Sales KPI

Total Outlets KPI

Total Products KPI

Sales by Item Type (Bar Chart)

Outlet Type vs Sales (Column Chart)

🔹 Sheet 2: Outlet Performance
Year-wise establishment comparison

Outlet Size vs Sales

Location-wise outlet count

🔹 Sheet 3: Product Insights
Fat Content distribution

Item Visibility analysis

Item Type vs MRP

🔹 Sheet 4: MRP vs Sales Scatter Plot
X-Axis: Item_MRP

Y-Axis: Item_Outlet_Sales

Detail: Item_Identifier

Tooltip: Custom tooltip with MRP, Sales, and ID

📌 Business Insights
High-MRP items do not always correlate with higher sales

Medium-sized outlets contribute most to total sales

Supermarket Type 1 stores dominate sales across locations

Item visibility has a moderate effect on sales

🛠️ Tools & Technologies
Microsoft Power BI – Data modeling, visualizations, and dashboarding

DAX (Data Analysis Expressions) – For calculated fields and KPIs

Power Query Editor – For data cleaning and transformation

🚀 Getting Started
Open the .pbix file using Power BI Desktop.

Refresh the dataset if connected to a live source (not required for static data).

Explore the pre-built visuals across all sheets.

Customize the dashboard as needed for additional insights.

