
## 📊 Project Documentation: Power BI – "Dashboard For Sales Store"

### 🧭 Project Objective
The goal of this project is to build an interactive Power BI dashboard that analyzes sales performance across time, regions, customers, and products. It empowers business stakeholders to make data-driven decisions by visualizing key metrics and trends.

---

### 🗂️ Data Sources
The dashboard is built using a star schema model with the following tables:
- **Dim_Customer**: Contains customer details.
- **Dim_Date**: Includes date-related information.
- **Dim_Product**: Holds product attributes.
-  **Dim_Location**: Includes location-related information.
- **Fact_Superstore**: The central fact table with sales, profit, discount, shipping, and order data.

---


### 🧩 Dashboard Pages & Features

#### 1. **Welcome Page**
- Displays a greeting message: “Welcome Back!”
- Navigation buttons: Time, Region, Customers, Product.
- Tabs at the bottom for easy access to report sections.

#### 2. **Time Analysis**
- **Line Chart**: Sales trends from Jan 2014 to Jul 2017.
- **Bar Chart**: Sales by shipping method (Standard, Second, First, Same Day).
- **Order Placement Duration**: Shows time taken to place orders (0–7 days).
- **KPIs**: Total Customers, Orders, Sales, and Profit.

#### 3. **Regional Analysis**
- **Map Visualization**: Sales distribution across U.S. states.
- **Region Breakdown**: Central, East, South, West.
- **Customer Segment Sales**: Consumer, Corporate, Home Office.


#### 4. **Product Analysis**
- **Bar Chart**: Profit by sub-category (green for profit, red for loss).
- **Category Sales**: Technology, Furniture, Office Supplies.
- **Top Products**: Canon Copiers, Cisco TelePresence, Fellowes Punch, etc.
- **KPIs**: Average Discount (0.16), Total Orders, Sales, Profit.

---

### 📌 Key Performance Indicators (KPIs)
| Metric             | Value     |
|--------------------|-----------|
| Total Customers    | 793       |
| Total Orders       | 9994      |
| Total Sales        | 2.30M     |
| Total Profit       | 286.40K   |
| Average Discount   | 0.16      |

---

### 🛠️ Tools & Technologies
- **Power BI Desktop**: For dashboard creation and data modeling.
- **DAX**: Used for calculated measures and KPIs.
- **Power Query Editor**: Data cleaning and transformation.
- **Interactive Visuals**: Maps, charts, tables, and slicers.

---

### 📈 Business Value
- Identifies top-performing products and customers.
- Highlights regional and seasonal sales trends.
- Supports strategic decisions in pricing, shipping, and inventory.
- Enhances visibility into discount impact and profitability.



