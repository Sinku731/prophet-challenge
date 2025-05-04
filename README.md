# prophet-challenge
# MercadoLibre Prophet Challenge

## Overview

As a growth analyst at **Mercado Libre**, your role is to analyze user behavior and financial data to support data-driven decisions that drive growth. This project explores whether search traffic trends can help predict stock performance using time series techniques like Facebook's Prophet library.

---

## Project Goals

1. **Find Unusual Patterns in Hourly Google Search Traffic**
2. **Mine the Search Traffic Data for Seasonality**
3. **Relate the Search Traffic to Stock Price Patterns**
4. **Create a Time Series Model with Prophet**

---

## Instructions Summary

### Step 1: Identify Unusual Search Patterns

- Load and visualize Google search data for May 2020.
- Compare total monthly traffic to the median traffic.
- Connect spikes in search trends to financial events (e.g., quarterly earnings).

### Step 2: Detect Seasonality in Search Data

- Plot average hourly search traffic by:
  - **Hour of the Day**
  - **Day of the Week**
  - **Week of the Year**
- Uncover patterns (e.g., peak business hours or holidays).
- Discuss seasonality and marketing implications.

### Step 3: Compare Search Trends with Stock Price

- Merge stock price and search data.
- Focus on Jan–June 2020 to observe post-COVID-19 market behavior.
- Create new columns:
  - `Lagged Search Trends` (1-hour shift)
  - `Stock Volatility` (EWM over 4 hours)
  - `Hourly Stock Return` (percent change)
- Analyze correlations between lagged traffic and market signals.

### Step 4: Forecast Using Prophet

- Prepare Google search data for Prophet modeling.
- Generate near-term forecasts.
- Decompose and visualize time series components:
  - Hour of day impact
  - Weekly patterns
  - Annual low traffic point

---

## Key Questions:
- What time of day exhibits the greatest popularity?
- Which day of week gets the most search traffic?
- What's the lowest point for search traffic in the calendar year?

