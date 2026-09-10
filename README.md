# 🇮🇳 India Urban Air Quality Analytics

<p align="center">
  <b>End-to-End Data Analytics & Business Intelligence Project</b>
</p>

<p align="center">
  Analyzing 858K+ hourly air-quality observations across Indian cities to uncover
  pollution hotspots, temporal patterns, pollutant behavior, and environmental associations.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Excel-Data%20Cleaning-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
  <img src="https://img.shields.io/badge/SQL%20Server-Analysis-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/DAX-Measures-0078D4?style=for-the-badge&logo=microsoft&logoColor=white">
</p>

---

## 📊 Dashboard Preview

<p align="center">
  <img src="screenshots/executive-overview.png" width="900">
</p>

> **Interactive Power BI dashboard covering AQI trends, city comparisons, pollution hotspots, weather relationships, seasonal patterns, festivals, crop burning and temperature inversion.**

---

## 🎯 Project Objective

> Analyze air-quality data across Indian cities to identify pollution hotspots,
> temporal patterns, pollutant behavior, and environmental factors associated
> with poor air quality.

---

## 🔄 Project Workflow

```text
📂 Raw Dataset
      ↓
🧹 Data Cleaning & Validation
      ↓
🗄️ SQL Server Database
      ↓
🔎 SQL Analysis
      ↓
📊 Analytical Views
      ↓
🔗 Power BI Data Model
      ↓
🧮 DAX Measures
      ↓
📈 Interactive Dashboard
      ↓
💡 Insights & Recommendations

India-Urban-Air-Quality-Analytics/
│
├── README.md
│
├── AQI_ANALYSIS.pbix
│
├── data/
│   └── [INDIA_AQI_COMPLETE_20251126.csv](https://www.kaggle.com/datasets/bhautikvekariya21/air-quality-dataset-indian-cities-2022-2025)
│
├── sql/
│   ├── 01_Database_Setup.sql
│   ├── 02_Table_Creation.sql
│   ├── 03_Data_Cleaning.sql
│   ├── 04_Basic_Analysis.sql
│   ├── 05_Advanced_Analysis.sql
│   └── 06_Analytical_Views.sql
│
└── screenshots/
    ├── executive-overview.png
    ├── city-comparison.png
    ├── pollution-weather.png
    └── season-events.png
