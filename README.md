# E-Commerce Sales, Customer & Payment Analytics Dashboard

## 1. Introduction

The **E-Commerce Sales, Customer & Payment Analytics Dashboard** is a data analysis and visualization project developed using Microsoft Power BI. It uses a synthetic Indian e-commerce dataset covering **1 January 2023 to 31 December 2025**.

The project presents business information through interactive charts, KPI cards, tables, and slicers. It helps explore sales and revenue trends, customer behavior, regional performance, product categories, payment operations, refunds, and inventory availability.

## 2. Objectives

- Analyze e-commerce sales and order performance over time.
- Monitor total revenue, total orders, and average order value.
- Compare revenue across product categories, states, and cities.
- Explore shipping methods and delivery success.
- Analyze total customers, active customers, churned customers, and average customer spend.
- Examine customer age groups, gender, retention status, and acquisition channels.
- Review payment success, refunds, transaction fees, and payment methods.
- Explore product catalog distribution, product types, pricing, and customer ratings.
- Use report filters to investigate different years, quarters, categories, and payment statuses.
- Present business metrics in a clear, interactive Power BI report.

## 3. Tools and Technologies Used

- **Microsoft Power BI Desktop:** For data modeling, DAX measures, visualizations, and dashboard design.
- **CSV datasets:** For storing and importing synthetic e-commerce data.
- **Power Query Editor:** For data cleaning and transformation.
- **DAX (Data Analysis Expressions):** For calculating measures and key performance indicators.
- **Power BI Model View:** For managing relationships between data tables.
- **GitHub:** For version control and sharing the project and dashboard previews.

## 4. Dataset Description

The project uses a synthetic dataset designed to simulate an Indian e-commerce marketplace. The data covers **2023–2025** and includes customers, products, orders, order items, payments, shipments, returns, reviews, and marketing campaigns.

### Dataset Files

- **`customers.csv`:** Customer demographics, geography, segments, acquisition details, and customer-level aggregates.
- **`products.csv`:** Product catalog details, categories, brands, prices, costs, and product attributes.
- **`orders.csv`:** Order dates, order status, totals, shipping details, discounts, and sales-channel information.
- **`payments.csv`:** Payment methods, payment statuses, amounts paid, transaction fees, and refunds.

The dataset contains **synthetic records only**. It does not represent real customers, transactions, or the performance of an actual company.

## 5. Methodology

- Imported the relevant CSV datasets into Power BI.
- Reviewed columns and data types and performed data cleaning and transformation where required.
- Built data-model relationships using the available keys between related tables.
- Created DAX measures for headline metrics and dashboard analysis.
- Designed three report pages covering executive sales, customer and regional insights, and payments and product catalog insights.
- Added slicers to support interactive filtering, including year, quarter, payment status, category, and other page-specific fields.
- Used KPI cards, line charts, bar charts, donut charts, a treemap, a scatter chart, and a transaction table to communicate the data.
- Reviewed the report visuals and filters for readability and interactive exploration.

## 6. Dashboard Visualizations

The Power BI report contains three main pages.

### Page 1: Executive Sales & Profit Overview

- **Total Revenue:** Displays the revenue KPI.
- **Total Orders:** Shows the number of orders.
- **Average Order Value:** Shows the average order value KPI.
- **Delivery Success:** Summarizes delivery performance.
- **Total Revenue by Year Month:** Displays the monthly revenue trend from 2023 to 2025.
- **Sum of Price by Category:** Compares product-category values.
- **Total Orders by Shipping Method:** Shows the distribution of orders across shipping methods.
- **Total Revenue by State:** Compares revenue across Indian states.
- **Slicers:** Year and quarter filters.

### Page 2: Customer Insights & Regional Analysis

- **Total Customer:** Displays the overall customer count.
- **Active Customers:** Shows the active customer count.
- **Churned Customer:** Displays the churned customer count.
- **Average Customer Spend:** Summarizes average customer spend.
- **Active Customers by Delivery State:** Compares customer activity across states.
- **Active Customers and Delivery Success Rate by State:** Compares customer counts with delivery success rate.
- **Total Revenue by City:** Compares revenue across cities.
- **Customer Table:** Displays customer IDs, cities, and order counts.
- **Total Customer by Age Group and Gender:** Compares customer groups by age and gender.
- **Customer Retention Status:** Shows the distribution of customer statuses.
- **Acquisition Channels:** Shows customer acquisition-channel distribution.
- **Slicers:** Includes payment-method and year filters.

### Page 3: Payments Settlement & Product Catalog Insights

- **Net Revenue Collected:** Displays the collected-revenue KPI.
- **Payment Success Rate:** Summarizes payment success performance.
- **Total Refunds:** Displays the refund total.
- **Total Stock Available:** Shows the stock-availability KPI.
- **Product Catalog & Margin Health:** Visualizes the product catalog across categories and subcategories.
- **Margin vs Customer Rating:** Explores the relationship between product price and average customer rating, segmented by product type.
- **Assortment Type Distribution:** Compares the distribution of product types.
- **Payment Operations (Financial Health):** Compares payment statuses by payment method.
- **Transaction Fees & Settlement:** Summarizes paid amounts, refunded amounts, and transaction fees by payment method.
- **Slicers:** Payment status, category, and discount range filters.

## 7. Results and Insights

The dashboard brings sales, customer, regional, payment, and product information into one interactive report. The displayed KPI cards and charts provide a starting point for exploring business performance.

Examples of the information visible in the report include:

- The executive page displays approximately **2.08bn** in total revenue and **81K** total orders for the selected report context.
- The customer page displays **25K** total customers, **7K** active customers, and **13K** churned customers.
- The payment and product page displays a payment success rate of **82.14%** and total refunds of **268.74M**.
- Monthly revenue, state and city comparisons, shipping methods, customer retention, acquisition channels, payment methods, and product categories can be explored through the visuals and filters.

These figures reflect the displayed dashboard and its current filter context. Because the source data is synthetic, they should be treated as project-analysis outputs rather than real-world market statistics. Further analysis can identify the most profitable products and categories, investigate churn, and examine payment or delivery issues.

## 8. Conclusion

The **E-Commerce Sales, Customer & Payment Analytics Dashboard** demonstrates how Microsoft Power BI can transform related e-commerce datasets into interactive business reports. Across its three pages, the project supports analysis of revenue trends, order activity, regional performance, customer retention, acquisition channels, payment outcomes, refunds, transaction fees, and product catalog information.

Building this project provides practical experience with CSV data import, Power Query transformations, data modeling, DAX measures, KPI design, and visual storytelling. It can be used as a portfolio project to demonstrate foundational data analytics and Power BI skills. Since the dataset is synthetic, conclusions should be validated against real business data before being used for operational decisions.

## 9. Project Files

The repository can include the following project assets, depending on what you choose to publish:

- Power BI report file (**`.pbix`**)
- Dataset CSV files, such as `customers.csv`, `products.csv`, `orders.csv`, and `payments.csv`
- **`README.md`** — project overview and dashboard documentation
- **`dashboard_screenshots/`** — dashboard preview images

### Suggested Repository Structure

```text
E-Commerce-Analytics/
├── README.md
├── dashboard_screenshots/
│   ├── sales_profit_overview.png
│   ├── customer_regional_analysis.png
│   └── payments_product_insights.png
├── your_power_bi_report.pbix
└── data/
    └── *.csv
```

## 📊 Dashboard Preview

### 1. Executive Sales & Profit Overview

<img width="1333" height="747" alt="1_Sales   Profit Overview" src="https://github.com/user-attachments/assets/0f88ccc1-e76e-4a09-96a2-1b259ac84587" />


### 2. Customer Insights & Regional Analysis

![Customer Insights and Regional Analysis](dashboard_screenshots/customer_regional_analysis.png)

### 3. Payments Settlement & Product Catalog Insights

![Payments Settlement and Product Catalog Insights](dashboard_screenshots/payments_product_insights.png)

## 10. References

- Microsoft Power BI: https://powerbi.microsoft.com/
- Microsoft Power Query documentation: https://learn.microsoft.com/power-query/
- Microsoft DAX documentation: https://learn.microsoft.com/dax/
- GitHub documentation: https://docs.github.com/
