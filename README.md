# Pizza Restaurant Sales Data Analysis and Report

This project provides a comprehensive analysis of a pizza restaurant's sales performance, focusing on order patterns, revenue trends, and product popularity. It covers the full data analysis workflow, from exploratory data analysis (EDA) to interactive Power BI dashboarding.

---

## 1. Project Overview

The primary objective is to support data-driven insights into restaurant operations by:
*   **Analyzing Sales Trends:** Identifying peak hours, busy days of the week, and seasonal growth patterns.
*   **Product Performance:** Determining which pizza categories and sizes generate the highest revenue and order volume.
*   **Customer Behavior:** Understanding order frequency and purchasing habits.
*   **Data-Driven Insights:** Providing actionable observations to optimize inventory management and staffing.

---

## 2. Dataset Summary

*   **Source:** Kaggle
*   **Description:** The dataset contains transaction-level records of pizza orders, including detailed information about pizza types, sizes, and pricing.

### Key Variables:
*   `order_id`: Unique identifier for each order placed.
*   `order_details_id`: Unique identifier for each pizza placed within each order.
*   `pizza_id`: Unique key identifier connecting the pizza ordered to its specific size and price.
*   `quantity`: Quantity ordered for each pizza type and size.
*   `order_date` & `order_time`: Date and time the order was placed (entered into the system prior to cooking & serving).
*   `unit_price`: Price of the pizza in USD.
*   `total_price`: Total amount for the row (`unit_price` * `quantity`).
*   `pizza_size`: Size of the pizza (Small, Medium, Large, X Large, or XX Large).
*   `pizza_type`: Category of the pizza (e.g., Classic, Chicken, Supreme, Veggie).
*   `pizza_ingredients`: Ingredients used in the pizza as shown on the menu.
*   `pizza_name`: Name of the pizza as shown on the menu.

---

## 3. Methodology

The project follows a structured data analytics workflow:

### 📊 Exploratory Data Analysis (EDA)
*   Analyzed top-selling pizza categories and sizes.
*   Visualized hourly and daily trends using **Python** (`Matplotlib` and `Seaborn`).
*   Conducted time-series analysis to observe revenue fluctuations over time.

### 📉 Interactive Dashboarding
*   Built a **Power BI** dashboard for dynamic and interactive analysis.
*   Included **KPI Cards**: Total Revenue, Total Orders, Average Order Value (AOV), and Total Pizzas Sold.
*   Developed key visualizations:
    *   **Revenue over time** (Trend Analysis).
    *   **Sales distribution** by Category and Size.
    *   **Busiest days/times** of the week (Heatmaps/Bar charts).
*   Added **Slicers** for interactive filtering by Date, Category, and Size.

---

## 4. Key Insights & Recommendations

*   **Overall Performance:** Total revenue indicates consistent demand throughout the week.
*   **Top Product:** Large pizzas are the most popular, driving the majority of revenue.
*   **Category Dominance:** The *Classic* category consistently outperforms others in volume.
*   **Operational Trends:** Peak order times are highly concentrated during weekends and evenings, suggesting a need for optimized staff scheduling.
*   **Inventory Optimization:** Identifying the most popular sizes helps in forecasting dough and ingredient requirements to reduce waste.

---
**Developed by:** Nguyen Pham Hoang Yen
