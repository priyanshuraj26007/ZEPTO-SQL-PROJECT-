# Zepto Product Inventory Analysis using SQL

## About the Project

This project explores and analyzes a Zepto product dataset using MySQL. The goal was to understand product pricing, discount strategies, inventory availability, and category-wise business trends through SQL queries.

The dataset contains information about product categories, prices, discounts, stock levels, quantities, and product weights.


## Project Workflow

### 1. Data Exploration

Before performing analysis, the dataset was explored to understand:

- Total number of products
- Available product categories
- Missing or invalid values
- Duplicate product names
- Stock availability status

### 2. Data Cleaning

To improve data quality:

- Removed products with invalid pricing values
- Converted price values from paise to rupees
- Validated important fields before analysis

### 3. Business Analysis

Several analytical queries were performed to answer practical business questions related to inventory and pricing.


## Key Questions Answered

### Top Discounted Products
Identified products offering the highest discounts to customers.

### High-Value Out-of-Stock Products
Found expensive products that were unavailable in inventory.

### Category Revenue Potential
Estimated inventory revenue by combining stock quantity and selling price.

### Discount Trends Across Categories
Compared average discount percentages across different product categories.

### Product Value Analysis
Calculated price per gram to determine products providing better value for money.

### Inventory Distribution
Measured total inventory weight available in each category.

---

## Database Structure

| Column Name | Description |
|------------|-------------|
| sku_id | Unique product identifier |
| category | Product category |
| name | Product name |
| mrp | Maximum retail price |
| discountPercent | Discount percentage |
| availableQuantity | Available stock quantity |
| discountedSellingPrice | Selling price after discount |
| weightInGms | Product weight |
| outOfStock | Stock availability status |
| quantity | Quantity information |

---

## SQL Concepts Demonstrated

- Data Cleaning
- Filtering and Sorting
- Aggregate Functions
- GROUP BY and HAVING
- CASE Statements
- UPDATE and DELETE Operations
- Revenue Calculations
- Inventory Analysis

---

## Technologies Used
- SQL
- GitHub

---

## Future Improvements

- Build interactive dashboards using Power BI
- Add sales transaction data for deeper analysis
- Perform demand forecasting and inventory optimization
- Create automated reporting workflows

## Author
Priyanshu Raj
