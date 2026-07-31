# 📊 LLegadasTuristaCostaRicaPowerBI

This repository features a **Power BI** dashboard focused on analyzing foreign national arrivals in Costa Rica over a multi-year period. The dashboard is designed to provide clear insights into tourism trends and the primary entry points into the country.

This project was developed as part of the **GrowUp** academy program.

---

## 📋 Table of Contents
- [Features](#-features)
- [Data Source](#-data-source)
- [ETL and Data Modeling Process](#-etl-and-data-modeling-process)
- [Visualizations and Insights](#-visualizations-and-insights)
- [Requirements](#-requirements)

---

## ✨ Features
- **Time-Series Analysis:** Track the evolution of foreign arrivals year over year.
- **Geographic Segmentation:** Breakdown of data based on the specific entry method.
- **Route Comparison:** Direct comparison between the 2 main airports versus land and sea borders.

---

## 🗄️ Data Source
The data is derived from a **public database** tracking immigration and migration flows in Costa Rica.
- **Original Format:** Structured files in `.csv` format.
- **Content:** Purely numerical data categorized by time periods and border control checkpoints.

---

## 🛠️ Data Preparation & Modeling (ETL)
The workflow to clean and structure the information involved the following steps:

1. **Extraction:** Loading the raw CSV files into Power BI.
2. **Normalization (Power Query):** 
   - Cleaning the data and correcting data types.
   - Leveraging *Transform Data* tools to pivot, filter, and consolidate the tables.
   - Eliminating inconsistencies to prepare the dataset for analysis.
3. **Data Modeling:** Establishing optimal relationships between the numerical variables and time dimensions.

---

## 📈 Visualizations and Insights
*(Optional: Take a screenshot of your dashboard, upload it to your repository folder, and link it below)*

[![Dashboard Preview](your-image-path.png)](https://github.com/fabianvargasr-create/LLegadasTuristaCostaRicaPowerBI/blob/main/screenshotofDashboard.PNG)

The final interactive report highlights:
* The total volume of foreign national entries.
* The market share of arrivals through the **2 main airports**.
* The cumulative influx recorded across **land and sea** borders.

---

## 💻 Requirements
To open and explore this project locally, you will need:
* **Power BI Desktop** (latest version recommended).
* The `.pbid` file included in this repository.
