# Urban Green Cover Analysis: An Interactive Power BI Dashboard

## Project Overview

This project provides a comprehensive analysis of urban green cover, measured by the Normalized Difference Vegetation Index (NDVI), for nine major Indian cities from 2010 to 2023. The core of this project is a dynamic, multi-page Power BI dashboard that transforms a raw CSV dataset into an interactive and insightful analytical tool.

The dashboard is designed for a wide audience, including urban planners, environmental researchers, policymakers, and data enthusiasts, allowing them to explore trends, compare cities, and understand the seasonal dynamics of urban vegetation.

### Key Metrics & Concepts
*   **NDVI (Normalized Difference Vegetation Index):** A satellite-based indicator for the presence and health of green vegetation. Higher values signify denser and healthier plant life.
*   **Seasonality:** The analysis of cyclical patterns in green cover, primarily driven by climate events like monsoons.
*   **Year-over-Year (YoY) Change:** A metric to track the annual progress or decline in a city's greenness.

---

## Features

The Power BI report is structured into four distinct pages, each serving a specific analytical purpose:

### 1. 🏙️ Executive Overview
A high-level summary of the national urban green cover landscape.
*   **KPI Cards:** At-a-glance metrics for overall average NDVI, the top-performing ("greenest") city, and peak recorded greenness.
*   **Geographic Map:** Visualizes the distribution and intensity of green cover across India.
*   **City Ranking:** A dynamic bar chart ranking cities by their average NDVI, sortable by year.
*   **Annual Trend Comparison:** A line chart for comparing the long-term greenness trajectories of multiple cities simultaneously.

### 2. 🌳 City Deep-Dive
A focused analytical page to explore the unique profile of a single selected city.
*   **Dynamic KPIs:** Key statistics update automatically based on the city chosen.
*   **Historical Trend Analysis:** A detailed line chart showing the monthly evolution of NDVI over the 14-year period, complete with a trend line.
*   **Seasonal Pattern Cycle:** A chart illustrating the "typical year" for a city's vegetation, clearly showing the impact of seasons.
*   **Performance Tracker:** A column chart displaying the year-over-year percentage change in green cover, highlighting periods of significant growth or decline.

### 3. 🆚 Comparative Analysis
A powerful tool for a direct, head-to-head comparison of any two cities.
*   **Dual Slicers:** Independent dropdowns to select two cities for comparison.
*   **Comparative Trend Charts:** Overlaid line charts for directly comparing historical and seasonal NDVI patterns.


### 4. ℹ️ Info & Methodology
A crucial page that builds trust and provides context for the data.
*   **Clear Definitions:** Explanations of NDVI and key terms.
*   **Data Transparency:** Details on the data source, time period, and processing steps.
*   **User Guide:** Simple instructions on how to use and navigate the dashboard.

---

## Technical Stack

*   **Data Source:** `Monthly_NDVI_Cities_2010_2023.csv`
*   **Data Transformation & Modeling:** **Power Query** (for data cleaning, type casting, and creating supplementary tables).
*   **Data Analysis & Calculations:** **DAX (Data Analysis Expressions)**
    *   Calculated Measures for `Average NDVI`, `Max NDVI`, `YoY Change %`, etc.
    *   Advanced DAX for dynamic titles, conditional filtering (`TREATAS`), and context-aware calculations (`SWITCH`, `SELECTEDVALUE`).
*   **Data Visualization:** **Power BI Desktop**
    *   Interactive visuals including line charts, bar charts, maps, matrices, and KPI cards.
    *   Features like slicers, cross-filtering, and dynamic titles to create a responsive user experience.

---

## How to Use This Project

1.  **Prerequisites:** You will need **Microsoft Power BI Desktop** installed on your machine.
2.  **Clone the Repository:** Download or clone this project repository to your local machine.
3.  **Open the File:** Locate the Power BI file (`.pbix`) and open it with Power BI Desktop.
4.  **Explore:** The dashboard is fully interactive. Click on slicers, chart elements, and map bubbles to explore the data. Use the navigation buttons or tabs to move between the different analysis pages.

---

## Author

*   **Manan Sapaloke**
*   **(http://www.linkedin.com/in/manansapaloke)**
*   **https://github.com/MananSapaloke**
