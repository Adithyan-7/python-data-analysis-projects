# 🚗 Uber Ride Analysis

Exploratory data analysis on 1,000 Uber rides to uncover patterns in trip categories, purposes, distances, and time-of-day demand.

---

## 📊 Dataset Overview

| Feature | Details |
|---|---|
| Records | 1,000 rides |
| Columns | 7 (START DATE, END DATE, CATEGORY, START, STOP, MILES, PURPOSE) |
| Source | Uber ride history dataset |

---

## 🔍 Key Findings

- **Business vs Personal split** is nearly even — 51% Personal, 49% Business
- **Airport and Commute** are the most frequent ride purposes (~13% each)
- **Average trip distance** is 18.6 miles, ranging from 1.5 to 35 miles
- Ride demand varies significantly by time of day — segmented into Morning, Afternoon, Evening, and Night buckets
- Business rides are concentrated around Meeting, Customer Visit, and Office purposes

---

## 🛠️ Steps Performed

1. **Data Loading & Inspection** — loaded CSV, checked shape, dtypes, and null values
2. **Data Cleaning** — filled missing PURPOSE values, removed duplicates, handled nulls
3. **Feature Engineering** — parsed STARTDATE into date and hour; created a `day-night` time segment feature
4. **EDA & Visualization**
   - Category and Purpose distribution (countplots)
   - Time-of-day ride demand (Morning / Afternoon / Evening / Night)
   - Purpose breakdown by Category (Business vs Personal)
   - Correlation heatmap of numeric features

---

## 📁 Files

| File | Description |
|---|---|
| `UberRideAnalysis.ipynb` | Main analysis notebook |
| `UberDataset.csv` | Raw dataset |

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 👤 Author

**Adithyan** — [GitHub](https://github.com/Adithyan-7) | [LinkedIn](https://linkedin.com/in/Adithyan-7)
