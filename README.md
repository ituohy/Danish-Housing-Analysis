# 🏡 Danish Municipal Housing Market Analysis

An analysis of one-family house market values across all 98 Danish municipalities
from 2004 to 2024, built with Python as part of my data analysis portfolio.

## 📊 Key Questions
- Which municipalities are the most and least expensive?
- How do prices differ across Sjælland, Jylland, and Fyn?
- How have prices in major cities trended over time?

## 🔍 Key Findings
- Sjælland dominates the top of the market — 19 of the top 20 most expensive
  municipalities are on Sjælland
- Frederiksberg averages ~12.6M DKK, nearly 5x the national average of ~2.7M DKK
- The most affordable municipalities are concentrated in Jylland
- All major cities show a clear dip in 2008 and recovery from ~2012 onwards

## 🛠️ Tools Used
- Python, Pandas, Matplotlib, Seaborn
- Data source: [Statistics Denmark StatBank API](https://api.statbank.dk)
  (Table: EJDFOE1 — Real estate market value by municipality)

## 📁 Files
- `analysis.ipynb` — full Jupyter notebook with code and commentary
- `top3_per_region.png` — most expensive municipalities per region
- `bottom3_per_region.png` — most affordable municipalities per region
- `city_trends.png` — price trends over time for major cities
- `heatmap.png` — all municipalities and years as a heatmap

## 📌 Status
Complete ✅
