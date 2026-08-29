# Supermarket Sales Performance Analysis

![SQL](https://img.shields.io/badge/SQL-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.10%2B-3572A5?style=flat-square&logo=python&logoColor=white)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=flat-square&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/leandro.soares5108/viz/Libro1_17879369054260/Dashboard1)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales/data)

An end-to-end data analytics project analyzing supermarket sales performance. The pipeline includes **data cleaning and preprocessing in Python**, **exploratory data analysis (EDA) using Matplotlib/Seaborn**, **data aggregations via SQL**, and an **interactive executive dashboard in Tableau**.

---

## 📌 Executive Summary

The primary objective of this project is to analyze transaction records from a supermarket chain to identify key revenue drivers, purchasing trends across days and hours, and top-performing product lines. 

By comparing analytical results between **SQL** and **Python**, the analysis was validated before building the final visualization layer in **Tableau**.

* **Dataset Source:** [Supermarket Sales on Kaggle](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales/data)

---

## 📊 Key Performance Indicators (KPIs)

* **Total Revenue:** `$323K`
* **Peak Sales Day:** `Saturday` (`$56.1K`)
* **Peak Sales Hour:** `19:00 h` (`$39.7K`)
* **Top Product Line:** `Food and Beverages` (`$56.1K`)

---

## 🛠️ Project Workflow & Tech Stack

| Phase | Tool / Library | Description |
| :--- | :--- | :--- |
| **1. Data Cleaning** | `Python` (Pandas, NumPy) | Handled missing values, formatted timestamps, extracted temporal features (`Hour`, `Day_Name`), and standardized categorical data. |
| **2. Exploratory Data Analysis** | `Python` (Matplotlib, Seaborn) | Generated bar plots and revenue heatmaps to explore sales distributions across days and time slots. |
| **3. Analytical Aggregations** | `SQL` | Structured relational queries to compute KPI metrics, group revenue by product categories, and build day-by-hour cross-tabulations. |
| **4. Visualization Layer** | `Tableau Desktop` | Designed a dynamic executive dashboard featuring interactive filters (`Day`, `Product Line`) and custom color palettes for operational insights. |

---

## 🖼️ Dashboard Preview

![Tableau Dashboard](dashboard_preview.png)

---

👤 Author: Leandro Soares: [LinkedIn Profile](https://www.linkedin.com/in/leandro-soares-91912097/)
