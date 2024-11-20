# **AtliQ Business Insights 360**

## **Project Overview**

**AtliQ Hardware** is a fast-growing company expanding globally. It specializes in selling computers and accessories through three key sales channels: **retailers**, **direct sales**, and **distributors**. 

Despite its impressive growth, the company experienced unexpected losses after opening a store in the United States. These setbacks were initially identified through basic surveys, intuition, and rudimentary Excel analysis. As its competitors leveraged advanced analytics teams, AtliQ recognized the importance of improving its own data analytics capabilities.

To address this, **AtliQ Hardware** decided to implement **Power BI** to support decision-making through data-driven insights across multiple business functions, such as **finance**, **sales**, **marketing**, **supply chain** and  **Executive**.

In this project, I followed the **Codebasics Power BI Course** to learn Power BI fundamentals and apply them to real-world business data.

**Project Links:**
- **[Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMjViOGQ3ZTMtMGUxNS00MDQxLWJmZTEtOTM3YWY5Yjc4NWQ1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**  

---

## **Datasets**

The datasets used in this project are crucial for generating insights that can drive business decisions. Two main types of data tables were used:

### **1. Dimension Tables** (Static Data)
These tables contain fixed information that helps to categorize and describe facts:

- **dim_customer**: Contains customer details, such as name, location, and other demographic information.
- **dim_market**: Provides data about different market regions and segments.
- **dim_product**: Includes details on the products offered by AtliQ Hardware.

### **2. Fact Tables** (Transactional Data)
These tables represent business transactions and metrics:

- **fact_forecast_monthly**: Forecasts the quantity of products that customers will need in the future. This is used to optimize inventory levels and warehouse storage, leading to **higher customer satisfaction** and **reduced storage costs**.
- **fact_sales_monthly**: Similar to the forecast table but captures actual sales data—used to compare against forecasts for performance evaluation.

Additionally, data from **gdb056** included more specific financials:

- **freight_cost**: The transportation costs associated with product delivery.
- **gross_price**: The sales price of products before deductions.
- **manufacturing_cost**: The cost of manufacturing products.
- **Pre_invoice_deductions**: Discounts applied before invoicing.
- **Post_invoice_deductions**: Discounts applied after invoicing.

---

## **Data Importing and Data Modeling**

### **Why Data Modeling is Essential**

Data modeling is a fundamental step in the analytics process. It involves structuring the data so that it can be efficiently queried and visualized. Without proper data modeling, analysis can be inaccurate and difficult to scale.

**Steps in Data Analysis:**
1. **Data Extraction**: Collecting data from various sources (in this case, MySQL).
2. **Data Cleaning**: Preparing data by removing inconsistencies and irrelevant entries.
3. **Data Modeling**: Creating relationships between tables to enable efficient querying and reporting.
4. **Data Analysis**: Using the structured data to generate meaningful insights.

In this project, the **Snowflake schema** was employed, which is a normalized method of organizing data that helps reduce redundancy and improve query performance.

![data model](https://github.com/Akashsingh1916/Business-Insights-360/assets/146354971/2285afcc-e8f4-4b94-abae-ea1d89e6cba9)
---

## **Power BI Dashboard Overview**

The Power BI dashboard created for this project consists of **six main pages**, each designed to focus on a specific area of business analysis:

### **1. Home Page**
- This is the starting point for the dashboard, with buttons that allow users to navigate to other pages.
- **Purpose**: Centralized access to the various business insights available.


![Home Page](Home%20Page.png "Home Page View")

### **2. Finance Page**
- This page provides insights into **financial planning**, **budgeting**, and **cost control**. It includes key financial metrics like:
  - **Profit & Loss Statements**: A summary of revenues, costs, and profits.
  - **Top and Bottom Products/Customers by Net Sales**: Identifies which products and customers contribute the most to the revenue.

![Finance View](Finance%20View.png "Finance View Page")

### **3. Sales Page**
- This page helps to identify strategies for increasing **sales revenue** and expanding market share. Key metrics include:
  - **Customer Performance by Net Sales**: Tracks customer sales trends.
  - **Gross Margin and Gross Margin %**: Measures the profitability of products sold.

![Sales View](Sales%20Customer%20View.png "Sales View Page")
![Sales View](Sales%20Product%20View.png "Sales View Page")

### **4. Marketing Page**
- The Marketing page focuses on improving **brand visibility** and **customer engagement**. Key insights include:
  - **Segment Performance by Gross Margin % and Net Profit %**: Analyzes the effectiveness of marketing efforts across different customer segments.

![Market View](Market%20Page.png "Market View Page")

### **5. Supply Chain Page**
- This page is geared towards optimizing **inventory management** and improving supplier relationships. Metrics on this page include:
  - **Forecast Accuracy**: Measures how well forecasts match actual sales.
  - **Net Error**: Tracks forecasting errors to improve future predictions.

![Supply Chain View](Supply%20Chain%20View.png "Supply Chain View Page")
### **6. Executive Page**
- This page is intended for high-level stakeholders, providing an overall view of company performance. Key metrics include:
  - **Net Sales**, **Gross Margin %**, **Net Profit %**
  - **Revenue Contribution by Channel**: Identifies which sales channels (retailers, direct, distributors) are performing best.
  - **Top 5 Customers/Products**: Lists the top-performing customers and products.

![Executive View](Executive%20View%20Page.png "Executive View Page")

---

## **Skills Learned**

Through the **Codebasics Bootcamp** course and this project, I gained proficiency in:
- **Power BI Fundamentals**: Building interactive reports and dashboards.
- **DAX Language**: Writing measures and calculated columns to perform advanced calculations.
- **Data Modeling**: Structuring data for efficient querying.
- **Data Cleaning**: Ensuring data integrity by handling missing values, errors, and duplicates.
- **Power BI Features**: Utilizing Bookmarks, Conditional Formatting, Dynamic Titles, and Custom Tooltips for enhanced interactivity.

---

## **Tools Used**
- **SQL**: Used for extracting data from the MySQL database.
- **Power BI Desktop**: The primary tool used for data modeling, visualization, and report creation.
- **DAX Studio**: Optimized Power BI reports by reducing file sizes and improving performance.
- **Project Charter**: Used as a planning tool to define the project's goals, deliverables, and timeline.

---

## **Business Terms Learned**

Throughout this project, I became familiar with key **business terms** related to finance, sales, and inventory management:
- **Gross Margin, Gross Margin %, Net Sales, Net Profit**
- **Cost of Goods Sold (COGS)**, **Pre-Invoice Deductions**, **Post-Invoice Deductions**
- **YTD (Year-to-Date)**, **YTG (Year-to-Go)**, **Gross Sales**
- **Sales Channels**: **Direct**, **Retailer**, **Consumer**, **Distributors**

---

## **Conclusion**

The **AtliQ Business Insights 360** project empowers business leaders and stakeholders to make informed, data-driven decisions. The interactive dashboard created in Power BI serves as an essential tool for exploring various business metrics across **finance**, **sales**, **marketing**, and **supply chain**. By leveraging **data analysis**, AtliQ Hardware can enhance its profitability and strategically address key business challenges.
