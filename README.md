# EEG Brainwave Analysis: Neural Signatures of Psychiatric Disorders

This project investigates **EEG (electroencephalography) coherence and amplitude features** to uncover neural differences between psychiatric conditions — with a focus on comparing **Healthy Controls** and individuals with **Addictive Disorders**.  
By combining statistical analysis, dimensionality reduction (PCA), and machine learning (Random Forest), the project demonstrates how EEG data can be used to reveal altered brain network dynamics.

---

## 📊 Project Overview

- **Goal:** Identify EEG connectivity patterns that distinguish addictive disorders from healthy controls.  
- **Dataset Source:** [OSF Dataset – EEG and Psychiatric Disorders](https://osf.io/8bsvr/)  
- **License:** [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
- **Author:** Tina  
- **Date:** October 2025  

---

## 🔍 Key Analyses

1. **Exploratory Data Analysis (EDA)**  
   - Inspected EEG coherence features across brain regions and frequencies.  
   - Visualized group-level differences.  

2. **Statistical Testing (t-tests)**  
   - Identified EEG features significantly different between Healthy and Addictive groups.  
   - Found strongest effects in **delta** and **theta** bands over **frontal** and **temporal** regions.

3. **Principal Component Analysis (PCA)**  
   - Reduced high-dimensional EEG data to visualize separability between groups.  

4. **Machine Learning (Random Forest)**  
   - Trained a classifier to predict group membership.  
   - Achieved **~68% accuracy**, revealing informative EEG connectivity patterns.

---

## 🧩 Interpretation

The analysis shows that **EEG coherence** captures neural signatures distinguishing addiction from healthy functioning.  
Top features were primarily in **frontal-temporal** and **parietal** regions — areas critical for **executive control, emotion regulation, and reward processing**.  

Although classification accuracy was moderate, the findings highlight EEG’s promise for understanding psychiatric disorders and emphasize the importance of:
- Larger, balanced datasets  
- Feature selection to improve generalization  
- Combining EEG with behavioral/clinical data  

---

## ⚙️ How to Run Locally

### 📁 Folder Path

If your project is stored here:

