---
title: "Departure Delays and Profitability Analysis for United Airlines"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/Analyzing-Departure-Delays-and-Profitability-for-United-Airlines" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>

## Key Highlights
- Analyzed United Airlines flight performance using the nycflights13 dataset  
- Identified key drivers of departure delays including time of day, seasonality, and weather conditions  
- Established statistical relationships between delays and profitability using hypothesis testing  
- Derived actionable insights to improve operational efficiency and flight profitability  

---

## Overview
This project analyzes departure delays and profitability for United Airlines using the nycflights13 dataset.

By combining exploratory data analysis, statistical testing, and integration with weather data, the project identifies key factors affecting flight delays and evaluates how operational efficiency impacts profitability.

---

## Demo / Visualization
![Delay Analysis](images/delay-analysis.png)

**Features:**
- Time-based delay trends (hourly and monthly patterns)  
- Weather impact analysis (temperature, wind speed, precipitation, visibility)  
- Profitability analysis using net gain and gain per hour  
- Statistical testing results visualization  

---

## Key Questions
- What factors contribute most to flight departure delays?  
- How do time of day and seasonality affect delays?  
- How do weather conditions impact operational performance?  
- How does punctuality influence airline profitability?  

---

## Methodology
- **Data**: nycflights13 dataset (filtered for United Airlines flights)  
- **Feature Engineering**:  
  - Created delay indicators (late, very_late)  
  - Computed net gain (departure delay vs arrival delay)  
  - Calculated gain per hour for profitability analysis  
- **Data Integration**: Merged flight data with weather dataset  
- **EDA**:  
  - Time-based analysis (hour, month)  
  - Distribution and trend visualization  
- **Statistical Analysis**:  
  - t-tests to compare group differences (on-time vs delayed flights)  
  - Permutation tests for time-of-day and seasonal comparisons  
- **Visualization**: Built using R (ggplot2)  

---

## Results & Insights

**Delay Analysis**
- Departure delays increase throughout the day, peaking in evening hours  
- Summer months and December show higher delays due to increased travel demand  
- Weather factors significantly impact delays:  
  - Higher temperature (>60°F) correlates with increased delays  
  - Increased wind speed and precipitation lead to higher delays  
  - Low visibility (<2.5 miles) is strongly associated with delays  

**Profitability Analysis**
- Flights departing on time generate significantly higher net gain  
- Shorter flights yield higher gain per hour compared to longer flights  
- Popular routes show higher profitability than less frequent routes  

---

## Impact
- Demonstrates how operational delays directly affect airline profitability  
- Provides data-driven insights for improving scheduling and route optimization  
- Supports decision-making in airline operations and resource allocation  

---

## Use Cases
- Airline operations teams optimizing schedules and reducing delays  
- Route planning and profitability analysis  
- Aviation analytics and performance monitoring  

---

## Tech Stack
- R (dplyr, ggplot2)  
- Statistical Analysis (t-test, permutation test)  
- Data integration and feature engineering  

---

## Future Work
- Incorporate predictive modeling for delay forecasting  
- Extend analysis to multiple airlines and airports  
- Build real-time dashboards for operational monitoring  
- Integrate additional external data sources (e.g., air traffic, holidays)  