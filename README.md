Core Product, Inventory & Warehouse Analytics

Project Overview

As part of the Heavy Supplier, Inventory & Warehouse Analytics project, this module focuses on analyzing product performance, inventory movement, stock turnover, stock health, warehouse space utilization, and inventory throughput using PostgreSQL.

The analysis uses the core_product_inventory_warehouse_analytics dataset to generate meaningful insights into product profitability, fast- and slow-moving products, inventory availability, warehouse capacity, and stock movement across branches.

Objectives

Evaluate product performance and profitability.

Identify fast-moving, moderate-moving, and slow-moving products.

Analyze inventory turnover and stock coverage.

Monitor stock health and identify replenishment requirements.

Measure warehouse space and capacity utilization.

Analyze inventory throughput across products and branches.

Support data-driven inventory and warehouse management decisions.

Key Analysis Areas

1. Product Performance Analysis

Evaluates product pricing, costs, profit margins, inventory value, and potential sales value.

Key Metrics:

Product Cost and Selling Price

Profit per Unit

Profit Margin Percentage

Current Inventory Value

Potential Sales Value

Potential Gross Profit

Product Profitability Status

Business Insights:

Identify profitable and loss-making products.

Compare product profitability across categories.

Evaluate inventory value and potential revenue opportunities.

Support product portfolio and pricing decisions.

2. Fast/Slow-Moving Product Analysis

Classifies products based on stock-out quantities and inventory movement indicators.

Key Metrics:

Total Stock In

Total Stock Out

Inventory Movement Count

Current Stock

Last Stock Movement Date

Product Movement Category

Business Insights:

Identify fast-moving and slow-moving products.

Highlight products with no recorded movement.

Understand inventory movement patterns.

Support stock allocation and replenishment planning.

3. Inventory Turnover Analysis

Examines inventory turnover indicators and estimated stock coverage to understand how efficiently inventory moves through the business.

Key Metrics:

Stock Turnover Indicator

Estimated Stock Coverage Days

Opening Stock

Current Stock

Total Stock Out

Current Inventory Value

Business Insights:

Identify products with high or low turnover indicators.

Monitor stock coverage and potential excess inventory.

Identify products that may require replenishment.

Support inventory optimization and working capital management.

4. Stock Health Analysis

Evaluates inventory levels against reorder points, safety stock, and maximum stock limits.

Key Metrics:

Current Stock

Reorder Level

Safety Stock

Maximum Stock Level

Stock vs. Reorder Percentage

Safety Stock Gap

Suggested Reorder Quantity

Inventory Risk

Stock Health Status

Business Insights:

Identify out-of-stock and critical-stock products.

Detect products requiring replenishment.

Highlight potential overstocking.

Improve inventory availability and stock control.

Reduce the risk of stockouts and excess inventory.

5. Warehouse Space Utilization Analysis

Measures warehouse utilization across branches to support storage capacity planning.

Key Metrics:

Warehouse Capacity

Warehouse Stock Utilization Percentage

Warehouse Capacity Utilization Percentage

Warehouse Type

Warehouse Bin

Branch and Regional Information

Business Insights:

Identify warehouses operating near full capacity.

Compare warehouse utilization across branches.

Identify locations with available storage capacity.

Support warehouse space allocation and optimization.

6. Inventory Throughput Analysis

Measures inventory movement based on quantities received into and dispatched from warehouses.

Key Metrics:

Total Stock In

Total Stock Out

Total Inventory Throughput

Total Stock Adjustments

Movement Count

Last Stock Movement Date

Branch-Wise Inventory Movement

Business Insights:

Measure overall inventory movement.

Compare stock receipts and dispatches across branches.

Identify products with high and low throughput.

Monitor warehouse operational activity.

Support inventory flow and distribution planning.

Dataset

Source: core_product_inventory_warehouse_analytics

The dataset contains product, pricing, inventory, warehouse, branch, stock movement, purchase, demand, and utilization information.

Tools & Technologies

Database: PostgreSQL

Query Language: SQL

Data Analysis: Product Performance, Inventory Analysis, Stock Movement Analysis, Warehouse Analytics

Visualization: Microsoft Power BI

Key Techniques: SQL Views, Conditional Logic, Aggregation, KPI Calculation, Inventory Classification

SQL Implementation

Separate PostgreSQL queries were developed to analyze:

1. Product Performance

2. Fast/Slow-Moving Products

3. Inventory Turnover

4. Stock Health

5. Warehouse Space Utilization

6. Inventory Throughput

7. Branch-Wise Inventory Throughput

Expected Business Outcomes

Improved visibility into product profitability and inventory value.

Better identification of fast- and slow-moving products.

Improved monitoring of inventory turnover and stock coverage.

Early identification of stock shortages and excess inventory.

Better understanding of warehouse capacity utilization.

Improved visibility into inventory movement across branches.

More informed inventory replenishment and warehouse planning decisions.

Future Enhancements

Develop an interactive Power BI dashboard with key inventory KPIs.

Calculate time-based product movement using 30-day and 90-day periods.

Implement accurate inventory turnover calculations using cost of goods sold and average inventory value.

Introduce demand forecasting and predictive reorder recommendations.

Add warehouse utilization alerts and stockout risk monitoring.

Integrate supplier delivery performance and purchase lead-time analysis.

Conclusion

The Core Product, Inventory & Warehouse Analytics module is an integral part of the Heavy Supplier, Inventory & Warehouse Analytics project. By combining PostgreSQL-based product performance analysis, inventory movement classification, turnover monitoring, stock health evaluation, warehouse utilization, and throughput analysis, this module supports data-driven decisions for improving inventory efficiency and warehouse operations.
<img width="849" height="5738" alt="image" src="https://github.com/user-attachments/assets/9ab3fbba-4923-4273-955d-e06727f3f9af" />
