# E-Commerce Shopify Sales

## Project Description
This is an **end-to-end Data Analytics project** built to analyze **Shopify sales and customer funnel metrics**.  
The project covers data cleaning in **Excel**, SQL-based exploration (if required), and building an **interactive Power BI dashboard** with hover-enabled tooltips for deep insights.

The dashboard helps track **transaction performance, customer behavior, retention metrics, regional sales, and payment method analysis**.

## Tools & Technologies
- **Excel** → Data cleaning, preprocessing, missing value handling
- **SQL** → Basic queries for validation and exploration (aggregations, grouping, filtering)
- **Power BI** → Dashboard creation, DAX measures, hover-enabled tooltips

## Data Source
- Shopify Sales dataset including orders, customers, payments, product categories, and regional information

## Workflow

### 1. Data Cleaning (Excel)
- Removed duplicates and null values  
- Standardized product categories & payment gateways  
- Converted date columns into proper format  
- Ensured data consistency before loading into Power BI  

### 2. SQL Analysis (Optional)
- Verified KPIs like total sales, customer count, repeat vs new customers  
- Aggregated data by region and product categories  
- Used queries to cross-check retention rates and average order values  

### 3. Dashboard (Power BI)
**Key KPIs:**
- Net Sales: **$4,180,874**  
- Total Quantity: **7,534**  
- Net Avg Order Value: **$562.6**  
- Total Customers: **4,431**  
- Repeat Customers: **2,039** (46% Repeat Rate)  
- Customer Lifetime Value (CLV): **$943.6**  

**Dashboard Features:**
- Net Sales Trend over time  
- Sales by Gateway (Shopify Payments, PayPal, Gift Cards, Others)  
- Regional sales breakdown (Province & City level + Geo maps)  
- Customer funnel (Single-order vs Repeat customers)  
- Product-wise sales distribution (Premium products lead revenue)  
- Hover-enabled tooltips on maps, line charts, and bar charts  

## Key Insights
- Shopify generated **$4.18M in sales** with an avg order value of **$562**  
- Strong **customer retention**: 46% repeat customers  
- **Shopify Payments dominates** with ~58% of all transactions  
- **New York, Washington, Houston** are the top-performing regions  
- Premium products contributed the maximum share of sales  

## How to Use
1. Open the `.pbix` file in Power BI Desktop.  
2. Use slicers for Province, Gateway, and Product Type.  
3. Hover over visuals for additional insights.  
4. (Optional) Run the SQL scripts for raw data validation.  

## Author
Vyshnavi Grandhi
