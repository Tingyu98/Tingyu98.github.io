---
title: "Member Growth & Engagement Analytics"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/member-growth-engagement-analytics" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>

## Key Highlights
- Analyzed 300K+ records spanning 20+ years of demographic, financial, and participation data  
- Identified a 20% participation gap among young adults across regions  
- Built an end-to-end ETL pipeline, reducing processing time from weeks to hours  
- Delivered insights that informed outreach strategy, resource allocation, and long-term planning

---

## Overview
A data science project focused on analyzing community engagement patterns within a nonprofit organization. By integrating demographic, financial, and participation data (2001–2024), this study uncovers trends across cultural groups and young adults to support program development.

---

## Key Questions
- How are different cultural communities growing or declining over time?  
- What factors drive engagement, especially among young adults?  
- Do language-specific services impact participation and financial outcomes?  
- What are the projected participation trends over the next 3–5 years?  

---

## Methodology

**Data Sources**
- Organizational data (household counts, participation, financials)  
- U.S. Census demographic data  

**Data Preparation**
- Built a Python ETL pipeline to process 300K+ records from 15 fragmented sources  
- Integrated data into a centralized SQLite database  
- Cleaned missing values and standardized participation metrics  

**Modeling**
- Time series forecasting for participation trends  
- Clustering analysis to identify demographic and cultural patterns  
- Regression analysis to identify key engagement drivers  
- Statistical testing to evaluate program and structural impacts  

**Visualization**
- Python-based visualizations for trends and patterns  
- Interactive Power BI dashboard for multi-year analysis  

---

## Key Insights

**Forecasting** – Registered households are projected to decline by approximately **5,633** between 2024–2027, representing a **4.45% decrease** in participation.

**Cultural Communities** – Communities offering **Spanish (+7.5%)** and **Vietnamese (+27.7%)** services experienced growth despite an overall registration decline of **6.7%**, highlighting shifting demographic trends.

**Young Adult Engagement** – Young adults (ages 18–39) represented approximately **29%** of participants. Revenue, baptisms, and Hispanic/Latino populations were positively associated with young adult participation, while a **20% registration gap** suggests continued opportunities for engagement.

**Language & Cultural Services** – Communities offering non-English services generally demonstrated higher participation levels, although stronger engagement did not necessarily translate into higher financial outcomes.

**Community Segmentation** – PCA identified distinct demographic clusters driven by racial, marital, and cultural diversity, suggesting that targeted outreach strategies may be more effective than a one-size-fits-all approach. 

---

## Tech Stack
Python | SQL | Power BI | ETL | Data Analysis | Clustering & Segmentation | Time Series Forecasting | Regression | Statistical Analysis | Data Visualization  

---

## Future Work
- Incorporate real-time data pipelines for continuous monitoring  
- Expand forecasting with advanced models (e.g., Prophet, LSTM)  
- Develop A/B testing frameworks to evaluate new outreach programs  

