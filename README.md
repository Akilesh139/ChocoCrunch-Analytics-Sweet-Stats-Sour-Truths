# ChocoCrunch-Analytics-Sweet-Stats-Sour-Truths
This project integrates nutrition datasets into a structured SQLite database, explores them with SQL + Pandas, and builds Power BI dashboards for visualization and storytelling.

# 📌 Project Overview

The project focuses on:

Data Integration

1) Using pandas to preprocess raw nutrition data.

2) Handling missing values, duplicates, and derived metrics.

Database Management

1) SQLite database (Choco_Crunch.db) created with three normalized tables:

2) product_info – Product metadata (code, name, brand).

3) nutrient_info – Nutritional values (calories, sugars, fats, proteins, etc.).

4) derived_metrics – Calculated metrics (sugar-to-carb ratio, categories, ultra-processed flag).

# SQL Queries

Performed basic to advanced SQL analysis:

Top brands by product count.

Average sugars per nova-group.

High calorie & high sugar product identification.

Products with nutrient thresholds (e.g., sodium > 1g).

# Exploratory Data Analysis (EDA)

Used Matplotlib/Seaborn to create:

Histograms, scatter plots, box plots, and heatmaps.

Category-wise distributions (calorie, sugar, fiber).

Correlation analysis of nutritional fields.

# Power BI Dashboards
Built 8 interactive visualizations, including:

Product count by calorie/sugar categories.

Proportion of products by nova group.

Scatter plot of sugar vs calories.

Top 10 brands by product count.

KPIs for total products, unique brands, and % ultra-processed.

# 🛠️ Tech Stack

* Language: Python (Pandas, Matplotlib, Seaborn, SQLite3)

* Database: SQLite (Choco_Crunch.db)

* Visualization: Power BI

* Data Export: CSV (for Power BI ingestion)
