# Pizza Restaurant Sales Data Analysis and Report

This project provides a comprehensive analysis of a pizza restaurant's sales performance, focusing on order patterns, revenue trends, and product popularity. It covers the full data analysis workflow, from exploratory data analysis (EDA) to interactive Power BI dashboarding.

## 1. Project Overview
The primary objective is to support data-driven insights into restaurant operations by:
* **Analyzing Sales Trends:** Identifying peak hours, busy days of the week and seasonal growth patterns.
* **Product Performance:** Determining which pizza categories and sizes generate the highest revenue and order volume.
* **Customer Behavior:** Understanding order frequency and purchasing habits.
* **Data-Driven Insights:** Providing actionable observations to optimize inventory management and staffing.

## 2. Dataset Summary
Source: [Kaggle](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)

The dataset contains transaction-level records of pizza orders, including detailed information about pizza types, sizes, and pricing.

**Key Variables:**
* `order_id`: Unique identifier for each order placed by a table
* `order_details_id`: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
* `pizza_id`: Unique key identifier that ties the pizza ordered to its details, like size and price
* `quantity`: Quantity ordered for each pizza of the same type and size
* `order_date`: Date the order was placed (entered into the system prior to cooking & serving)
* `order_time`: Time the order was placed (entered into the system prior to cooking & serving)
* `unit_price`: Price of the pizza in USD
* `total_price`: unit_price * quantity
* `pizza_size`: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
* `pizza_type`: Unique key identifier that ties the pizza ordered to its details, like size and price
* `pizza_ingredients`: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
* `pizza_name`: Name of the pizza as shown in the menu

## 3. Methodology
The project follows a structured data analytics workflow:

### **Exploratory Data Analysis (EDA)**
* Analyzed top-selling pizza categories and sizes.
* Visualized hourly and daily trends using Matplotlib and Seaborn.
* Conducted time-series analysis to observe revenue fluctuations over time.

### **Interactive Dashboarding**
* Built a **Power BI** dashboard for interactive analysis.
* Included KPI cards (Total Revenue, Total Orders, Average Order Value, Total Pizzas Sold).
* Developed visualizations for:
  * Revenue over time (Trends).
  * Sales distribution by Category and Size.
  * Busiest days/times of the week.
* Added slicers for filtering by Date, Category, and Size.

## 4. Dashboard Proposal: Revenue & Inventory Efficiency
Key Insights:
* **Overall Performance:** Total revenue indicates consistent demand throughout the week.
* **Top Product:** Large pizzas are the most popular, driving the majority of revenue.
* **Category Dominance:** The Classic category consistently outperforms others in volume.
* **Operational Trends:** Peak order times are concentrated during weekends and evenings, suggesting a need for optimized staff scheduling.
* **Inventory Optimization:** Identifying the most popular sizes helps in forecasting dough and ingredient requirements.

---
**Developed by:** Nguyen Pham Hoang Yen
