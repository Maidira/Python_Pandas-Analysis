# E-commerce Data Analysis Project

## Overview
This project focuses on analyzing an e-commerce dataset to extract meaningful business insights.  
It includes **data cleaning, transformation, exploratory data analysis (EDA), and advanced analytics** to understand customer behavior, product performance, and business operations.

---

## Dataset Features
The dataset contains the following key fields:

- **Customer Info**: name, email, age, city, country  
- **Order Details**: order_id, quantity, unit_price, discount_pct, order_total  
- **Product Info**: product_category  
- **Delivery Info**: order_date, delivery_date, delivery_days  
- **Status & Feedback**: order_status, customer_rating  
- **Payment**: payment_method  

---

## Data Cleaning Steps
- Standardized categorical values (country, product category, payment method)
- Cleaned and validated email formats
- Converted columns to correct data types (dates, numeric)
- Handled missing and invalid values
- Recalculated `order_total` for consistency

---

## 📈 Analysis Performed

### Sales & Revenue Analysis
- Total Revenue and Average Order Value (AOV)
- Revenue by country, city, and product category
- Monthly sales trends

### Customer Analysis
- Customer distribution by location
- Spending behavior by age group
- Top customers (Customer Lifetime Value)

### Product Analysis
- Most popular product categories
- Revenue and ratings by category
- Product performance matrix

### Payment & Order Status
- Payment method distribution
- Cancellation and return rates

### Delivery & Logistics
- Average delivery time
- Delivery performance by country
- Late delivery analysis

### Advanced Analysis
- RFM (Recency, Frequency, Monetary) analysis
- Customer segmentation

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
