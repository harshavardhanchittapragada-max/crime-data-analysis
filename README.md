# 🔍 Crime Against Women in India — Data Analysis & Visualization

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-lightgrey?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Heatmaps-teal)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

This project analyzes **15+ years of NCRB (National Crime Records Bureau) data** on crimes against women across all 35 Indian states and union territories. The goal was to move beyond surface-level statistics and find patterns that could inform policy and public awareness.

**Key Question:** Where are crimes most concentrated, and do socioeconomic indicators like literacy affect crime reporting?

---

## 📊 Dataset

| Property | Detail |
|---|---|
| Source | National Crime Records Bureau (NCRB), Government of India |
| Time Range | 2001 – 2021 |
| Rows | 5,000+ records |
| Columns | State, Year, Crime Type, Count |
| Crime Types | Rape, Kidnapping, Dowry Deaths, Domestic Violence, Assault, Trafficking |

---

## 🔧 Tech Stack

- **Python 3.10**
- **Pandas** — data cleaning, EDA, aggregation
- **Matplotlib** — trend lines, bar charts
- **Seaborn** — heatmaps, distribution plots
- **Jupyter Notebook** — interactive analysis

---

## 🧹 Data Cleaning Steps

- Handled null values across 10+ crime category columns
- Standardized inconsistent state name spellings
- Cast year and count columns to correct numeric types
- Removed duplicate records
- Created derived columns: total crimes per state, Y
