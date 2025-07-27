# 🚕 Uber Fares Dataset Analysis with Power BI

This project involves analyzing the **Uber Fares Dataset** using **Python (Pandas)** for data preparation and **Power BI** for interactive visualizations. It is part of the coursework for *INSY 8413: Introduction to Big Data Analytics* at AUCA.

---

## 📌 Objective

To gain comprehensive insights into Uber fare patterns, ride timings, and operational metrics through:

- Data cleaning and feature engineering in Python
- Interactive dashboard creation in Power BI
- Visual storytelling to support data-driven decisions

---

## 📁 Dataset

- **Source**: [Uber Fares Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- **Records**: Pickup and drop-off data including time, location, distance, and fare amount

---

## 🔧 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib)
- **Power BI Desktop**
- **GitHub** (for project documentation and version control)

---

## 🧪 Methodology

### 1. Data Cleaning & Preprocessing (Python)
- Removed nulls and duplicates
- Converted timestamps to datetime format
- Filtered invalid fare and coordinate values

### 2. Feature Engineering
- Extracted `hour`, `day_of_week`, and `month` from timestamps
- Categorized time as `Peak` or `Off-Peak`
- Added new columns for easier analysis in Power BI

### 3. Visualization & Dashboard (Power BI)
- Imported cleaned CSV
- Created time-based, geographic, and fare-based insights
- Enabled slicers and drill-downs for interactivity

---

## 📊 Dashboard Features

| Visual | Purpose |
|--------|---------|
| Line Chart (by Hour) | Shows busiest times for Uber rides |
| Column Chart (by Day) | Compares ride volumes across weekdays |
| Pie Chart (Peak vs Off-Peak) | Proportional distribution of rides |
| Box Plot (Fare Amounts) | Highlights outliers and fare ranges |
| Map (if location data used) | Displays pickup locations spatially |
| Slicers | Filters by day, hour, peak time, etc. |

---

## 📈 Key Insights

- Highest ride volumes occur between **8–9 AM** and **5–6 PM**.
- **Friday** and **Saturday** have the highest ride counts.
- Fare amounts are generally higher during **peak hours** and **weekends**.
- Outliers in fares may reflect long-distance or special service rides.

---

## 🗂️ Repository Structure

