# AIRBNB_ANALYSIS
# 🏠 Airbnb Seattle — Listings & Revenue Dashboard

Interactive Tableau dashboard exploring pricing, geography, and revenue trends across Seattle Airbnb listings.

## 📊 Dashboard Overview

This dashboard visualizes key metrics from the Seattle Airbnb dataset across four panels:

- **Avg Price per Bedroom** — Bar chart showing how nightly rates scale with bedroom count (1–6), ranging from $94.4 to $635.3
- **Price by Zipcode** — Comparative bar chart ranking average listing prices across all Seattle zip codes
- **Price per Zipcode (Map)** — Choropleth map (Mapbox) showing geographic distribution of pricing across Seattle neighborhoods
- **Revenue per Year** — Time-series chart tracking cumulative calendar revenue from early 2016 through mid-2017
- **Listings of Bedroom (Filter)** — Interactive filter to slice all views by bedroom count (1–5+)
  <img width="1255" height="907" alt="Screenshot 2026-05-31 122656" src="https://github.com/user-attachments/assets/9761fcb3-db3f-4922-886e-fefe687afbd8" />


## 🔍 Key Insights

- 6-bedroom listings command a significant premium (~$635/night) vs. 1-bedroom (~$94/night)
- Zip code `98146` has the highest average price among mapped areas ($189.4)
- Revenue shows a steady upward trend throughout 2016–2017

## 🛠 Tools & Data

| | |
|---|---|
| **Tool** | Tableau Desktop / Tableau Public |
| **Dataset** | [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle) |
| **Fields Used** | Listing ID, Bedrooms, Avg. Price (Calendar), Zipcode, Week of Date |
| **Map Tiles** | Mapbox / OpenStreetMap |
