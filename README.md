# NDVI Trend Analysis for Indian Cities (2010–2023)

## 🌱 Introduction to NDVI

**NDVI (Normalized Difference Vegetation Index)** is a satellite-derived index that quantifies the presence and health of vegetation. It is calculated using the difference between near-infrared (which vegetation strongly reflects) and red light (which vegetation absorbs):

NDVI = (NIR - RED) / (NIR + RED)

NDVI values range from -1 to +1:
- Values close to **+1** indicate **dense, healthy vegetation**.
- Values near **0** suggest **barren areas** (rock, sand, urban land).
- Negative values usually indicate **water bodies** or clouds.

This makes NDVI an essential metric for tracking green cover trends in urban landscapes, especially over time and across seasons.

---

## 📊 Project Overview

This project offers a detailed visual and statistical analysis of urban green cover trends in **ten major Indian cities** from **2010 to 2023**, based on monthly NDVI values. The centerpiece is an interactive multi-page **Power BI dashboard**, built to transform raw satellite-derived data into actionable insights.

The dashboard serves **urban planners, environmental researchers, policymakers, and data enthusiasts**, enabling them to:
- Track greenness over time
- Identify seasonal patterns
- Compare cities
- Investigate the impact of urban development on vegetation

---

## 🧩 Key Metrics & Concepts

- **NDVI (Normalized Difference Vegetation Index):** Primary measure of vegetation density.
- **Seasonality:** Analysis of how NDVI changes during different months of the year.
- **Year-over-Year (YoY) Change:** Tracks long-term gains or losses in green cover.

---

## 📈 Dashboard Features

### 1. 🏙️ Executive Overview
A national-level summary of urban greenness.
- **KPI Cards** for average NDVI, greenest city, and max NDVI value
- **Map View** showing spatial NDVI intensity across cities
- **Sortable Bar Chart** ranking cities by NDVI
- **Multi-City Trend Line** for tracking changes over years

### 2. 🌳 City Deep-Dive
Focused view of a single city.
- Dynamic **KPIs** that auto-update by city
- **Historical Trend** line (2010–2023)
- **Seasonal Cycle** chart showing average month-wise NDVI
- **YoY % Change** tracker for policy insights

### 3. 🆚 Comparative Analysis
Direct head-to-head comparison between two cities.
- Dual dropdowns to choose cities
- Overlaid **historical** and **seasonal** trend charts

### 4. ℹ️ Info & Methodology
Transparency and credibility.
- Simple explanations of NDVI and terminology
- Data sourcing and processing steps
- Guide on using the dashboard

---

## ⚙️ Technical Stack

- **Data Source:** `Urban_NDVI_2010_2023.csv`
- **Cleaning & Modeling:** Power Query
- **Analysis Engine:** DAX (Data Analysis Expressions)
  - Measures like `Avg NDVI`, `Max NDVI`, `YoY Change %`, etc.
  - Advanced functions like `TREATAS`, `SWITCH`, and `SELECTEDVALUE`
- **Visualization:** Power BI Desktop
  - Line charts, bar charts, slicers, maps, KPIs, and dynamic visuals

---

## 🚀 How to Use This Project

1. **Install** Microsoft Power BI Desktop
2. **Clone or Download** this repository to your local machine
3. **Open** the `.pbix` file using Power BI
4. **Explore** the visuals by interacting with slicers, charts, and filters

---

## ✅ License

This project is licensed under the **[MIT License](./LICENSE)** — feel free to use, modify, and share with attribution.

---

## 👤 Author

**Manan Sapaloke**  
🔗 [LinkedIn](http://www.linkedin.com/in/manansapaloke)  
💻 [GitHub](https://github.com/MananSapaloke)

---

