# 🚕 Uber Fares Dataset Analysis with Power BI

This project involves analyzing the **Uber Fares Dataset** using **Python (Pandas)** for data preparation and **Power BI** for interactive visualizations. It is part of the coursework for *INSY 8413: Introduction to Big Data Analytics* at AUCA.

---

## 📌 Objective

To gain comprehensive insights into Uber fare patterns, ride timings, and operational metrics through:

- Data cleaning and feature engineering in Python
- Interactive dashboard creation in Power BI
- Visual storytelling to support data-driven decisions

- 

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

## Screenshot
<img width="865" height="461" alt="dashboard" src="https://github.com/user-attachments/assets/cadb1b93-8513-494c-ba66-8a79fde234e8" />

<img width="1013" height="476" alt="ccccc" src="https://github.com/user-attachments/assets/8ad7f23c-6297-437c-8f4d-30477f673af7" />
<img width="1056" height="691" alt="sdsd" src="https://github.com/user-attachments/assets/09a2ad16-2a1a-41c8-93eb-a137a6f3a17a" />
<img width="1040" height="698" alt="linechart" src="https://github.com/user-attachments/assets/12f6b27a-ac2c-47fc-8966-33e1d042b2b3" />
<img width="1032" height="692" alt="dot" src="https://github.com/user-attachments/assets/745a6990-6727-41c5-94dd-5d6ad68effcd" />



