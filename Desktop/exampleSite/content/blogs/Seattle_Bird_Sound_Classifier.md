---
title: "Seattle Bird Sound Classifier"
draft: false
tags: []
hideDate: true
socialShare: false
---

<style>.gh-btn,.gh-btn:hover,.gh-btn:focus,.gh-btn:active{display:inline-flex!important;align-items:center!important;gap:6px!important;padding:6px 14px!important;background:#fff!important;color:#000!important;border:1px solid #000!important;border-radius:6px!important;text-decoration:none!important;font-size:0.9rem!important;margin-bottom:1.5rem!important;transform:none!important;box-shadow:none!important;white-space:nowrap!important;width:auto!important;}</style>
<a href="https://github.com/Tingyu98/Analysis-of-Seattle-Bird-Sounds-Deep-Learning" target="_blank" class="gh-btn"><i class="fab fa-github"></i> View on GitHub</a>

## Key Highlights
- Built deep learning models to classify bird species from audio recordings using spectrograms  
- Achieved 95% accuracy in binary classification between two bird species  
- Developed multi-class classification model for 12 species, highlighting real-world complexity  
- Applied audio signal processing and neural networks to a real-world ecological dataset  

---

## Overview
This project applies deep learning techniques to identify bird species from audio recordings.

By converting audio signals into spectrograms and training neural network models, the system learns to classify bird calls and supports automated species identification, with potential applications in ecological monitoring and biodiversity research.

---

## Key Questions
- How can audio signals be transformed into features suitable for classification?  
- How accurately can neural networks distinguish between bird species from sound?  
- What challenges arise when scaling from binary to multi-class classification?  

---

## Methodology
- **Data**: Xeno-Canto Bird Sound Archive (audio recordings for 12 bird species)  
- **Preprocessing**:  
  - Audio cleaning and normalization  
  - Conversion of audio clips into spectrograms  
- **Feature Representation**: Spectrogram images used as model input  
- **Modeling**:  
  - Binary classification model (two species)  
  - Multi-class classification model (12 species)  
  - Neural networks built using TensorFlow and Keras  
- **Evaluation**: Accuracy metrics and performance comparison across models  

---

## Results & Insights
- Binary classification achieved 95% test accuracy between selected species  
- Multi-class classification achieved 67.24% accuracy, reflecting increased task complexity  
- Performance gaps indicate challenges in distinguishing acoustically similar species  
- Dataset limitations and class imbalance contributed to reduced multi-class performance  

---

## Impact
- Demonstrates application of deep learning in bioacoustics and ecological monitoring  
- Enables automated bird species identification from audio data  
- Provides a foundation for scalable biodiversity tracking systems  

---

## Use Cases
- Wildlife monitoring and conservation efforts  
- Automated species identification in field recordings  
- Research in ecology and environmental science  

---

## Tech Stack
- Python  
- TensorFlow, Keras  
- Audio processing libraries (e.g., librosa)  
- Data visualization tools  

---

## Future Work
- Expand dataset to include more species and diverse recordings  
- Improve model performance with advanced architectures (e.g., CNN, transfer learning)  
- Address class imbalance and noise in real-world audio data  
- Deploy as a real-time audio classification system  