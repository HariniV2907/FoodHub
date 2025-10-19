# 🍔 FoodHub - Exploratory Data Analysis Project

## 📄 Project Overview
FoodHub is a food delivery aggregator operating in New York, providing customers access to multiple restaurants through a single app. With the number of restaurants and online orders growing rapidly, the company aims to analyze customer and restaurant data to gain business insights.

This project explores key factors influencing customer satisfaction, restaurant performance, and operational efficiency based on FoodHub’s order dataset.

---

## 🎯 Objective
To perform data analysis on FoodHub’s order dataset and derive insights to help:
- Understand customer preferences.
- Identify high-performing restaurants.
- Analyze ratings, order costs, and delivery times.
- Improve customer experience and operational strategy.

---

## 📊 Dataset Description
**File:** `foodhub_order.csv`

| Column Name | Description |
|--------------|-------------|
| `order_id` | Unique ID of each order |
| `customer_id` | Unique customer ID |
| `restaurant_name` | Name of the restaurant |
| `cuisine_type` | Type of cuisine ordered |
| `cost_of_the_order` | Total cost of the order |
| `day_of_the_week` | Day type — Weekday or Weekend |
| `rating` | Rating given by the customer (out of 5) |
| `food_preparation_time` | Time taken (in minutes) by restaurant to prepare food |
| `delivery_time` | Time taken (in minutes) by delivery person to deliver the order |

---

## 🧠 Key Analysis Performed
- Data cleaning and exploration.
- Descriptive statistics and distribution analysis.
- Identification of top cuisines and restaurants.
- Analysis of ratings vs. cost and delivery time.
- Weekday vs. weekend order trends.
- Correlation between preparation and delivery times.

---

## 📈 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Google Colab**
- **HTML Report Generation** (`FoodHub_Week1_Project.html`)

---

## 📂 Project Structure
- foodhub_order.csv # Dataset
- FoodHub_Week1_Project.html # Project Report (exported analysis)

---

## 🔍 Insights Summary

- Top cuisines and restaurants were identified based on order frequency.
- Weekends showed a noticeable increase in order volume.
- Customer ratings were more influenced by delivery time than cost.
- Preparation and delivery times had a moderate positive correlation.

---

## 🏁 Conclusion

**The analysis provides actionable insights for FoodHub to:**
- Partner with top-rated restaurants.
- Optimize delivery operations.
- Enhance overall customer satisfaction.
