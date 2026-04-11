---
title: "NutritionExpert"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/NutritionExpert" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>

## Key Highlights
- Built an end-to-end AI-powered nutrition analysis system using YOLOv8, GPT-4, and external APIs  
- Achieved ~73% mAP in food detection across 65 food categories  
- Integrated real-time nutrition data and personalized diet recommendations  
- Delivered an interactive Streamlit app for real-world usability  

---

## Overview
In today's fast-paced world, maintaining a healthy diet is increasingly challenging. NutritionExpert is an AI-powered system that analyzes meal images and generates personalized diet recommendations.

By combining computer vision, nutrition APIs, and large language models, the platform transforms food images into actionable dietary insights, enabling users to make data-driven health decisions.

---

## Key Questions
- How can we automatically detect food items from images in real time?  
- How can image-based detection be translated into actionable nutrition insights?  
- Can AI generate personalized diet recommendations based on detected meals?  

---

## Methodology
- **Data**: UECFOOD-256 and School Lunch datasets (65 classes used for training)  
- **Preprocessing**: Annotation conversion to YOLO format, normalization, train/validation split (9:1)  
- **Modeling**: Trained YOLOv8 with hyperparameter tuning (epochs, learning rate)  
- **Evaluation**: Assessed performance using mAP and precision-recall curves  
- **Integration**: Connected detection results with CalorieNinjas API for real-time nutrition data  
- **Application**: Built an interactive Streamlit interface  
- **Personalization**: Integrated GPT-4 via OpenAI API for tailored diet recommendations  

---

## Results & Insights
- Achieved ~73% mAP in food detection  
- Maintained precision above 0.7 across most categories  
- Identified lower recall for underrepresented food classes  
- Improved model stability by increasing training epochs (10 → 20)  

---

## Demo / Visualization

**Application Demo**

<img src="/images/projects/food_detect.png" width="60%">

**Features Demonstrated**
- Upload meal images for real-time food detection  
- View detected food items with bounding boxes  
- Retrieve calorie and macronutrient information  

---

## Impact
- Enables users to make data-driven dietary decisions  
- Transforms food images into actionable nutrition insights  
- Demonstrates real-world application of AI in health and nutrition  
- Provides a scalable foundation for food-tech and wellness applications  

---

## Use Cases
- Personal use for tracking meals and calorie intake  
- Healthcare and fitness coaching support  
- Integration into nutrition apps and smart food platforms  

---

## Tech Stack
- Python (PyTorch, OpenCV)  
- YOLOv8  
- Streamlit  
- APIs: CalorieNinjas, OpenAI GPT-4  

---

## Future Work
- Expand dataset to include more diverse food categories  
- Address class imbalance to improve recall  
- Incorporate portion size and weight estimation  
- Deploy as a mobile application for real-time usage  