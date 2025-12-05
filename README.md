📦 Retail Inventory & Delivery Performance Dashboard – Power BI Project
📌 Overview

This project delivers a complete end-to-end Power BI analysis of a Retail Inventory & Shipment dataset. It covers data cleaning, transformation, modeling, DAX calculations, and the creation of an interactive dashboard that provides insights into warehouse performance, shipment modes, customer satisfaction, product importance, and delivery efficiency.

The objective of this project is to help understand operational patterns, identify delay drivers, optimize warehouse processes, and support decision-making related to logistics and inventory management.

🧹 Data Cleaning & Preparation (Power Query)

Before building the dashboard, the dataset required significant preparation. Key steps included:

Fixing incorrect data types (Whole Number, Text, Currency).

Removing blanks, invalid entries, or irrelevant rows.

Standardizing Product Importance, Shipment Mode, and Warehouse Block fields.

Extracting clean numerical columns for aggregation.

Creating consistent structure for delivery analysis and performance comparison.

🧮 DAX Measures Used

Several DAX measures were created to calculate KPIs and support advanced insights:

Total Revenue

Average Revenue per Order

Average Customer Rating

Total Quantity Shipped

Quantity by Shipment Mode

Quantity by Warehouse Block

% On-Time Delivery

Delayed Shipment Count

Product Importance Wise Quantity

These DAX measures enabled deeper analysis of shipping performance, warehouse workload, and product-level contribution.

📈 Dashboard Features
⭐ KPI Cards

Total Revenue

Average Revenue

Average Customer Rating

Total Quantity

On-Time Delivery Percentage

📊 Visualizations

The dashboard includes a variety of visuals:

Sum of Quantity by Mode of Shipment

Quantity by Product Importance

Quantity by Warehouse Block

Summary table for all warehouse blocks

Donut chart of On-Time vs Late Deliveries

Quantity distribution by categories (Mode, Importance, Warehouse)

Filters/Slicers: Shipment Mode, Warehouse Block, Product Importance

These visuals allow stakeholders to analyze performance across logistics, warehouse efficiency, and customer-related metrics.

🛠 Tools & Technologies

Power BI Desktop

Power Query for cleaning & transformation

DAX (Data Analysis Expressions)

Retail Inventory CSV Dataset

🎯 Project Outcomes

This project demonstrates strong capabilities in:

Business Intelligence & Visualization

Data Cleaning and Shaping

Data Modeling

DAX Measure Creation

Operational & Logistics Insight Generation

Dashboard Design & Performance Tracking

The report highlights operator bottlenecks, identifies delivery delays, and reveals product-driven and warehouse-driven performance patterns.

📢 Impact & Key Insights (Story of the Dashboard)

This dashboard presents several impactful insights that clearly explain how the business is performing at both the warehouse and shipment levels.

1️⃣ Ship Mode Handles the Most Quantity but Causes Most Delays

Ship is the largest shipment mode, but it contributes significantly to late deliveries.
This indicates dependency on slower transportation types.

Impact: Faster alternative modes (Road/Flight) should be preferred for urgent or high-value orders.

2️⃣ Low and Medium Importance Products Drive Majority of the Sales

Low-importance products contribute the highest shipment quantity, followed by medium.
High-importance items have the least volume.

Impact: Inventory planning must prioritize low- and medium-importance products to reduce stockouts.

3️⃣ Warehouse Block F Handles Nearly Double the Load

While A–D blocks distribute workload evenly, Warehouse F handles the highest number of orders.

Impact: Overloaded warehouse → higher stress, delays, and potential inefficiencies. Redistribution is recommended.

4️⃣ Delivery Delays Are Significantly High (~40%)

A substantial percentage of shipments do not reach on time.

Impact:
Delivery process improvements are necessary to increase customer trust and reduce operational losses.

5️⃣ Customer Ratings Are Below Average (≈2.99)

Despite large shipment volumes, customer satisfaction remains poor.

Impact:
Improving delivery consistency and reducing customer care interactions can improve ratings.

6️⃣ Product Importance Strongly Influences Delivery Time

High-importance items are shipped less but tend to reach on time more frequently.
Low-importance items show the worst delivery consistency.

Impact:
Better prioritization rules could improve overall service levels.

🧵 Overall Story of the Data

The data reveals a business that ships large volumes of products consistently, but struggles with delivery efficiency, customer satisfaction, and warehouse balance.

Ship mode dominates quantity, but also causes delays.

Low-importance products drive most sales but are handled inefficiently.

Warehouse F is overburdened, affecting timely delivery.

Customer ratings reflect dissatisfaction caused by delays or product issues.

The dataset tells a clear operational story:
Optimize warehouse distribution, improve logistics planning, reduce delays, and redesign prioritization for shipments.

📂 Files Included

Power BI Report (.pbix)

Dataset (retail_inventory.csv)

README Documentation

Dashboard Screenshots


📘 How to Use

Download Retail_Inventory.pbix

Open with Power BI Desktop (Free)

View insights or connect your own dataset for further analysis

✔ Conclusion

The Retail Inventory & Delivery Performance Analysis project shows how raw shipment and warehouse data can be transformed into a meaningful, operational intelligence report. The dashboard provides deep insights into warehouse efficiency, delivery delays, shipment strategy, customer satisfaction, and prioritization of products.

The insights support key decisions in logistics optimization, warehouse management, and customer experience improvement.
