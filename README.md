# Bike-Sales-and-Customer-Insights-Dashboard-Using-Power-BI
Bike Sales and Customer Insights Dashboard Using Power BI


https://github.com/user-attachments/assets/b0bae963-044c-47ab-a562-e803813a4037


**Project Overview:**
This Project uses Power BI to address significant challenges in sales performance, customer segmentation and operational efficiency. Dashboard developed as a part of this project transform raw sales data into actionable insights  and also enhances decision making for inventory management, targeted marketing and resource allocation.
Interactive dashboard developed as a part of this project does the following:

- Keeps track of total revenue, units sold and profit trends over time.
- Analyzes Purchase behavior, and sales distribution per region for strategic marketing.
- Evaluates return rates, inventory turnover and category sales to increase the profit in long run.

**Data Sources:**

Data used in this project is sales data of bikes ,accessories and clothing of a bike company. Data contains different details like 
- Sales Transactions
- Product Information
- Customer Demographics
- Sales Territories
- Returns Data

**Methodology**

**Data Extraction & Transformation (ETL)**
Connected Power BI to raw CSV files.
Performed data cleansing using Power Query Editor:
- Removed duplicate records.
- Standardized date formats and null values.
- Applied transformations such as column splitting, merging, and calculated fields.

**Data Modeling**
- Implemented a data model using a star and snowflake schema with Fact (Sales) and Dimension (Customers, Products, Territories, Calendar) tables.
- Established relationships using Primary and Foreign Keys.
- Optimized cardinality (one-to-many or many-to-one relationships) for efficient filtering.
- Applied bi-directional filters where necessary to ensure proper data flow.

**Calculated Fields with DAX**
- Created calculated columns for new fields (e.g., extracting SKU categories, categorizing income levels).
- Developed measures for key performance indicators (KPIs) such as:
- Total Sales = SUM(Sales[Total Amount])
- Return Rate = SUM(Returns[Quantity]) / SUM(Sales[Quantity])
- Revenue Per Customer = SUM(Sales[Revenue]) / DISTINCTCOUNT(Customers[CustomerID])
- Used time intelligence functions (e.g., DATESYTD(), PREVIOUSYEAR()) for year-over-year comparisons.
- 
**Designing Interactive Dashboards**
Inserted visualizations, including:
- Bar charts for regional sales performance.
- Line charts for sales trends over time.
- Pie charts for product category distribution.
- KPI cards to highlight revenue, profit, and returns.
- Implemented slicers & filters for dynamic reporting:
- Filtered by year, product category, region, and customer segments.
- Enabled drill-down and drill-through functionalities.

**Optimizing**
Optimized performance by:
- Reducing data size.
- Hiding unnecessary columns in report view.
- Ensuring relationships followed a star schema for efficient queries.

**Tools Used**
- Microsoft Power BI for visualization
- Power Query for ETL processing
- DAX (Data Analysis Expressions) for calculated measures

**Conclusion:**
This project successfully delivers a comprehensive sales analytics dashboard for monitoring business performance. The insights gained will help in decision-making regarding inventory, marketing, and customer engagement strategies.






