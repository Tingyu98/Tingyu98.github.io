---
title: "Arrhythmia Detection"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/arrhythmia-detection" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>
---

## Key Highlights
- Built an end-to-end ECG arrhythmia detection pipeline using machine learning and deep learning  
- Achieved ~90% accuracy and strong abnormal recall using Random Forest and 1D CNN  
- Extracted physiological features (HRV, RR intervals, QRS) for interpretable modeling  
- Developed an interactive Streamlit app for real-time ECG analysis and visualization  

---

## Overview
This project develops an AI-powered system to detect cardiac arrhythmias from ECG signals.

By combining feature-based machine learning models and deep learning (1D CNN), the system identifies abnormal heart rhythms such as atrial fibrillation (AFib) and premature ventricular contractions (PVC), enabling early detection and monitoring of potential cardiac conditions.

---

## Key Questions
- How can ECG signals be used to accurately detect abnormal heart rhythms?  
- How do traditional ML models compare with deep learning approaches on ECG data?  
- Can real-time detection be integrated into an interactive monitoring system?  

---

## Methodology
- **Data**: MIT-BIH Arrhythmia Database (annotated ECG signals)  
- **Preprocessing**: Band-pass filtering (0.5–40 Hz), segmentation into time windows  
- **Feature Engineering**: HRV metrics (RMSSD, CVRR), heart rate, QRS width, signal energy  
- **Modeling**:  
  - Logistic Regression, Random Forest (baseline models)  
  - 1D CNN for raw signal classification  
- **Evaluation**: Accuracy, Macro-F1, AUROC, false alarms/hour  
- **Deployment**: Streamlit app for real-time visualization and interaction  

---

## Results & Insights

**Binary Classification (Normal vs Abnormal)**
- Random Forest achieved best overall performance (~90% accuracy, strong abnormal recall)  
- 1D CNN achieved highest sensitivity (92.8% abnormal recall), reducing missed detections  
- Logistic Regression provided a solid baseline but missed some abnormal cases  

**Multi-Class Classification (Normal / PVC / AFib)**
- Random Forest performed well on PVC detection (F1 ≈ 0.9)  
- AFib detection remained challenging due to class imbalance  
- CNN struggled in multi-class setup, indicating need for more data  

---

## Impact
- Enables early detection of abnormal heart rhythms for preventive healthcare  
- Demonstrates application of AI in clinical signal processing and decision support  
- Provides a scalable framework for integration with wearable or hospital ECG systems  

---

## Use Cases
- Clinical monitoring using wearable ECG devices  
- Healthcare decision support tools  
- Educational and research applications for ECG analysis  

---

## Tech Stack
- Python (NumPy, Pandas, scikit-learn)  
- PyTorch (1D CNN)  
- NeuroKit2 (signal processing)  
- Streamlit, Plotly  

---

## Future Work
- Improve AFib detection with more balanced datasets  
- Extend to multi-lead or 12-lead ECG data  
- Optimize deep learning architecture for better generalization  
- Deploy as a real-time monitoring tool integrated with wearable devices  
