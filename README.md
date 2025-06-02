# 🚚 Swiggy Delivery Operations Dashboard

An interactive Power BI dashboard created to visualize and optimize Swiggy’s delivery performance across cities and areas in India. This report provides valuable insights into restaurant distribution, food ratings, delivery patterns, and customer preferences.

---


## 📈 Key Metrics

- **Total Restaurants:** 7,865  
- **Average Rating:** 3.66  
- **Average Price:** ₹348.44  
- **Total Orders:** 8,680  
- **Average Delivery Time:** 53.97 minutes  

---

## 🧩 Features Overview

### ✅ KPI Cards (Top Panel)
- Quick snapshot of key performance indicators (Total Restaurants, Avg. Ratings, Orders, etc.)

### 📊 Visuals Included

- **Count of Restaurants by Area**  
  A bar chart representing the number of restaurants in each locality.

- **Average Ratings by Restaurant**  
  Highlights the top-rated restaurants in the selected areas.

- **Top 5 Rated Food Types (Donut Chart)**  
  Provides the distribution of most-loved food cuisines (Indian, Chinese, South Indian, etc.).

- **Maximum Delivery by City (Bar Chart)**  
  Showcases which cities drive the highest number of deliveries.

- **Geo Map of India (Map Visual)**  
  An interactive map plotting delivery hubs and hotspots across major Indian cities.

---

## 📂 Tech Stack

- **Power BI Desktop** – For designing and publishing the report.
- **Power Query Editor** – For cleaning and transforming raw delivery and restaurant data.
- **DAX (Data Analysis Expressions)** – Used for calculated metrics like average delivery time and ratings.
- **Data Modeling** – Relationships established among tables: `Restaurants`, `Orders`, `Cities`, `Food Types`.

---

## 📊 Business Impact

- 🛵 **Operational Efficiency:** Helps identify bottlenecks in delivery operations.
- ⭐ **Quality Control:** Reveals underperforming restaurants and low-rated cuisines.
- 🌍 **Market Coverage:** Assists in expanding operations to high-demand zones.
- 📍 **Location Intelligence:** Geographic visualization aids regional decision-making.

---

## 📁 File Format

- `.pbix` Power BI file
- `.png` snapshot of dashboard

---

## 📌 Sample Dataset Structure

| Column Name       | Description                         |
|-------------------|-------------------------------------|
| Restaurant Name   | Name of the food outlet             |
| Area              | Locality within the city            |
| City              | Metro location (e.g., Delhi, Pune)  |
| Ratings           | Average customer ratings (1–5)      |
| Orders            | Total orders delivered              |
| Food Type         | Cuisine category                    |
| Delivery Time     | Average time taken per delivery     |
| Price             | Average price per order             |

---

## 🔍 Filtering Options

- **City Filter** – Analyze performance by metro area  
- **Area Filter** – Deep dive into specific localities

![Alt Text]()
