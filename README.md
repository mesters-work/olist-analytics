# Olist E-Commerce: Delivery & Retention Analysis

**Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 📌 Project Overview
This project analyzes how efficiently products are delivered on Olist (a large Brazilian e-commerce platform) and how well customers are retained over time.

The workflow demonstrates an end-to-end data analysis pipeline:
- **Google Colab (Pandas)** for cleaning and feature engineering
- **Python script** for reproducibility
- **Tableau Public** for interactive dashboards

## 🛠️ Pipeline
1. Raw Olist CSVs → `/data/raw/`
2. Data cleaning & feature engineering in [Colab Notebook](notebooks/olist_analysis.ipynb)
   - Delivery duration (`delivery_days`)
   - Late delivery flag (`late_flag`)
   - Gross Merchandise Value (GMV)
   - Customer cohorts
3. Processed datasets → `/data/processed/`
4. Mirrored workflow in [clean_data.py](scripts/clean_data.py) for reproducibility
5. Tableau Public dashboard built from processed CSVs

## 📊 Dashboard Views
👉 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/mesters-work) *

- **Line series**: Average delivery days & % late over time
- **Cohort heatmap**: Retention by first purchase month
- **Choropleth map**: % late deliveries by customer state
- **KPI cards**: GMV, total orders, % on-time

## 🚀 Skills Demonstrated
- Data wrangling with **Pandas**
- Workflow reproducibility (**Colab → GitHub → Python script**)
- **Cohort and funnel analysis** for customer retention
- **Tableau storytelling** with time series, heatmaps, and maps

---

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/mesters-work/olist-analytics/blob/main/notebooks/olist_analysis.ipynb)
