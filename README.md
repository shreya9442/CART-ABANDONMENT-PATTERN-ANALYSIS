# CART-ABANDONMENT-PATTERN-ANALYSIS

## 1. Project Overview

This project is about understanding how customers interact with products on an e-commerce platform. I used SQL to analyze customer events and Power BI to create a dashboard showing patterns in cart activity, purchases, and cart removals.

## 2. Business Problem

Customers often add products to their carts but may remove them or leave without completing a purchase. I wanted to understand how cart behavior changes across product prices, categories, brands, and different times of the day.

The main goal was to find patterns in the data and understand which areas are worth looking at more closely.

## 3. Tools Used

- **MySQL:** To explore the data and write SQL queries for analysis.
- **Power BI Desktop:** To build the dashboard and visualize the results.
- **DAX:** To create measures and calculated columns for the dashboard.
- **Power Query:** To connect and prepare data in Power BI.
- **GitHub:** To document and share the project.

## 4. Dataset

I used a table named `cart_events`, which contains customer activity related to products.

The main columns used in the analysis were:

- `event_time` – When the event happened
- `event_type` – Type of event, such as view, cart, purchase, or remove_from_cart
- `product_id` – Product ID
- `category_code` – Product category
- `brand` – Product brand
- `price` – Product price
- `user_id` – Customer ID
- `user_session` – Session ID

The dataset covers the period from October 1, 2024, to November 30, 2024.

## 5. What I Analyzed

I used SQL to explore the data and calculate different metrics. After that, I created a Power BI dashboard to present the results.

The main analyses include:

- Comparing cart events, purchases, and cart removals.
- Checking purchase rates across different price ranges.
- Comparing purchase rates across product categories.
- Analyzing cart activity and purchases by brand.
- Comparing purchase and cart removal rates across time periods.
- Looking at purchase and non-purchase sessions across weekdays.
- Comparing customer activity and sessions with different numbers of cart events.

I also added bookmarks in Power BI so users can switch between the category and brand views without needing extra space for another chart.

## 6. Key Findings

- The afternoon had the highest purchase rate among the time periods analyzed, while night had the lowest.
- Lower-priced products generally had higher observed purchase rates than higher-priced products.
- Purchase rates differed across product categories and brands.
- Sessions with four to five cart events had a lower purchase rate than sessions with only one cart event.
- Cart removal rates were relatively similar across different times of the day.

These are patterns observed in the dataset and do not necessarily mean that one factor directly causes a purchase or cart abandonment.

## 7. Dashboard

The dashboard includes:

- KPI cards for cart events, purchases, removals, and purchase rate.
- Purchase rate by price range.
- Purchase and non-purchase sessions by weekday.
- Cart events and purchases by brand.
- Purchase rate by category.
- Purchase rate versus cart removal rate by brand.

## 8. What I Learned

While working on this project, I practised writing SQL queries to analyze real-world-style e-commerce data. I also learned how to create measures in DAX, build different types of visuals in Power BI, and use bookmarks to make a dashboard more interactive.

This project helped me understand how raw data can be used to identify patterns in customer behavior and present the findings in a simple visual format.

## 9. Limitations

The analysis covers only two months of data. The results show observed patterns and do not prove the reasons behind customer behavior. Purchase rates based on event counts should also not be treated as actual cart conversion rates.

## 10. Tools and Skills

**Tools:** MySQL, Power BI Desktop, DAX, Power Query

**Skills:** SQL querying, data analysis, KPI creation, data visualization, dashboard development, and e-commerce analytics.
