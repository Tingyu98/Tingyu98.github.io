---
title: "Sentiment Analysis of Yelp Reviews"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/Sentiment-Analysis-" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>

## Key Highlights
- Analyzed 150K restaurant reviews from a 6M+ Yelp dataset using NLP techniques  
- Built sentiment classification models using TF-IDF, Logistic Regression, and XGBoost  
- Achieved ~94% F1-score with XGBoost, outperforming baseline models  
- Identified key drivers of negative sentiment, including service delays and order issues  

---

## Overview
This project applies Natural Language Processing (NLP) and machine learning techniques to analyze restaurant reviews from Yelp.

By modeling customer sentiment from textual reviews, the project identifies key factors influencing customer satisfaction and provides actionable insights to improve service quality and user experience.

---

## Key Questions
- What words and phrases drive positive or negative customer sentiment?  
- How accurately can we predict sentiment from review text?  
- What operational insights can businesses extract from customer feedback?  

---

## Methodology
- **Data**: Yelp Open Dataset (6M+ reviews, 150K sampled for analysis)  
- **Preprocessing**: Tokenization, lowercasing, stop-word removal, lemmatization  
- **Filtering**: Selected restaurant-related reviews and merged business metadata  
- **EDA**: Analysis of rating distribution, text length, and word frequency  
- **Feature Engineering**: TF-IDF vectorization using NLTK and scikit-learn  
- **Modeling**:  
  - Logistic Regression (baseline)  
  - XGBoost (optimized via hyperparameter tuning)  
- **Evaluation**: Accuracy, F1-score, precision-recall tradeoffs  
- **Interpretation**: Feature importance analysis to identify sentiment drivers  

---

## Results & Insights
- XGBoost achieved ~94% F1-score, outperforming Logistic Regression  
- Logistic Regression provided a strong and interpretable baseline  
- Key negative sentiment drivers included terms such as "time" and "order"  
- Insights indicate customer dissatisfaction is strongly linked to service delays and order accuracy  

---

## Impact
- Enables businesses to automatically analyze large-scale customer feedback  
- Provides actionable insights to improve service quality and customer satisfaction  
- Demonstrates scalable NLP solutions for real-world text analytics  

---

## Use Cases
- Restaurants monitoring customer feedback and identifying service issues  
- Platforms like Yelp automating sentiment classification and review summaries  
- Product and operations teams improving customer experience based on data insights  

---

## Tech Stack
- Python (pandas, numpy)  
- NLP: NLTK, scikit-learn  
- Modeling: Logistic Regression, XGBoost  
- Visualization: matplotlib, seaborn  

---

## Future Work
- Incorporate word embeddings (Word2Vec, BERT) for deeper semantic understanding  
- Extend to multi-class sentiment classification  
- Deploy as a real-time API or dashboard for continuous monitoring  