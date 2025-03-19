# Brain Tumor Prediction Using Machine Learning

## Overview
This repository contains machine learning models for predicting brain tumor characteristics using classification and regression techniques. The models utilize patient data to make predictions related to tumor type, stage, survival rate, MRI results, and follow-up requirements.

## Features
- **Classification Models (Random Forest)**
  - Predict if a tumor is **benign or malignant**.
  - Determine the **tumor stage (I, II, III, IV)**.
  - Predict **high vs. low survival rate**.
  - Classify **MRI results as positive or negative**.
  - Determine whether **follow-up treatment is required**.

- **Regression Models (Random Forest)**
  - Predict **exact survival rate** based on tumor characteristics.
  - Estimate **tumor growth rate** using patient history and treatments.

## Dataset
The models are trained on a **brain tumor dataset (`brain_tumor_dataset.csv`)** containing:
- **Demographic Information** (age, gender, family history)
- **Tumor Details** (type, stage, histology, location, size, growth rate)
- **Symptoms & Medical History**
- **Treatment History** (radiation, chemotherapy, surgery)
- **MRI Results & Follow-Up Data**

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
