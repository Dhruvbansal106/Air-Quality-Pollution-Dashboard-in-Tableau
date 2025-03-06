# # 🌍 Air Quality & Pollution Dashboard in Tableau

## 📌 Project Overview
This project aims to visualize **Air Quality Index (AQI) levels** across various Indian cities over a **five-year period (2015–2020)**. By analyzing pollution trends and sources, we provide interactive insights through a **Tableau dashboard** that enables data-driven decision-making.

---

## 🛠️ Tools Used
💻 **Tableau Public/Desktop** – For dashboard visualization.
📂 **Excel/CSV Files** – Dataset storage & preprocessing.
🐍 **Python (Pandas, NumPy)** – Data cleaning & transformation.

---

## 🔹 Steps to Build the Dashboard

### 1️⃣ Data Collection 📊
We utilized the **Indian Air Quality Dataset (2015–2020)** from Kaggle, which includes:
- 📍 **Cities Covered:** Delhi, Mumbai, Kolkata, Chennai, Hyderabad, and more.
- 📄 **Key Columns:**
  - 🏙️ `City`: Name of the city
  - 📅 `Date`: Recorded AQI date
  - 🌫️ `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `O3`: Pollutant levels
  - 📊 `AQI`: Overall Air Quality Index
  - ✅ `AQI_Bucket`: Air quality category (**Good, Moderate, Poor, etc.**)

---

### 2️⃣ Data Cleaning & Preprocessing 🛠️
1. **Handling Missing Values:** Used interpolation or removal techniques to fill or eliminate gaps in data.
2. **Removing Duplicates:** Eliminated redundant entries to maintain data integrity.
3. **Standardizing Date Formats:** Ensured uniformity in the `Date` column for accurate time-series analysis.
4. **Filtering Outliers:** Removed extreme values that could skew the analysis.
5. **Converting Units:** Ensured pollutant values were in a common unit for consistency.
6. **Data Aggregation:** Summarized AQI levels **by city, time period, and pollutant type** for better visualization.

---

### 3️⃣ Data Visualization in Tableau 📈
#### 🔹 Key Visualizations:
✅ **📊 Heatmap:** AQI levels by **city and date** (hourly, daily, monthly).
✅ **🗺️ Geospatial Map:** AQI distribution across cities **using color-coded intensity**.
✅ **📈 Line Chart:** AQI **trends over time** for different cities.
✅ **📉 Bar Chart:** Comparison of **pollutant levels** across locations.
✅ **🎛️ Interactive Filters:**
   - 📌 **City selection** (Dropdown)
   - 📌 **Date range filter**
   - 📌 **Pollutant type filter**
   - 📌 **Multi-city comparison**

---

### 4️⃣ Insights & Analysis 📢
🔍 **Most Polluted & Least Polluted Cities:** Identified trends over time.
🔍 **Seasonal Pollution Trends:** Compared winter vs. summer AQI levels.
🔍 **Impact of Major Events:** Evaluated changes before & after lockdowns.
🔍 **Correlation with Weather Conditions:** Assessed effects of temperature, humidity, and wind speed.

---

## 🚀 Dashboard Features
🎯 **User-Friendly Layout:** Organized, clear, and engaging visualizations.
🎯 **Interactivity:** Filters for city, date range, and pollutant type.
🎯 **Key Performance Indicators (KPIs):**
   - 🔴 **Average AQI**
   - 🌆 **Most Polluted City**
   - 🌿 **Least Polluted City**
   - ☣ **Dominant Pollutant**

---
End of the Project

