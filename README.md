# This repository contains documentation, and summaries for two of my IEEE published research papers in the domain of medical machine learning. Both works focus on the early detection of cardiovascular disease (CVD) using different approaches, one with classical machine learning models and the other with neural networks and big data infrastructure.
# The goal of these projects is to demonstrate how predictive analytics and artificial intelligence can be applied to real-world healthcare problems to assist in early diagnosis and improve patient outcomes.

# 1. Cardio-Vascular Risk Detection System using Different Machine Learning Techniques
## DOI: 10.1109/iSSSC56467.2022.10051216

Cardiovascular disease is one of the leading causes of death and disability worldwide. This project focuses on developing a patient-level risk detection system using classical machine learning algorithms to classify individuals into "risky" or "non-risky" categories based on clinical indicators.

---

## Abstract

Atherosclerosis, the underlying cause of most cardiovascular conditions, progresses silently and is often detected too late. Early identification through machine learning can guide timely medical intervention. This research performs extensive experimentation on different classification models and achieves a 98% recognition accuracy using a Decision Tree Classifier.

---

## Dataset

- Approximately 1,000–1,500 anonymized patient records  
- Key features:
  - Age, Gender  
  - Resting Blood Pressure  
  - Cholesterol Levels  
  - ECG Results  
  - Maximum Heart Rate Achieved  
  - Exercise-Induced Angina  
  - Blood Sugar Levels  
  - Target label: Cardiovascular risk (binary)

---

## Machine Learning Models

- Decision Tree (Best performing, 98% accuracy)  
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes

---

## Methodology

- Data preprocessing (standardization, label encoding)  
- Train-test split with stratification  
- Cross-validation (10-fold)  
- Model tuning and evaluation using:
  - Accuracy  
  - Precision / Recall  
  - F1 Score  
  - Confusion Matrix

---

## Results and Impact

- Decision Tree model achieved the highest performance  
- Enables patients to detect risk early and follow preventive routines  
- Suitable for integration into diagnostic tools, hospital systems, or mobile health apps

---

# 2. Big Data Predictive Analytics Model for Cardiovascular Risk Detection using Machine Learning Techniques
## DOI: 10.1109/iSSSC56467.2022.10051293

This project extends cardiovascular risk prediction into a big data and AI-driven framework. It leverages neural networks and large-scale patient records to enable fast, scalable, and intelligent CVD detection suitable for real-time systems and healthcare policy planning.

---

## Abstract

Using a dataset of around 1,500 patients and integrating geospatial health data, this research applies Artificial Neural Networks (ANN) to achieve 99% recognition accuracy. The focus is on early detection and scalable deployment in population-level risk assessment scenarios.

---

## Dataset

- ~1,500 patient records with demographic and clinical data  
- Features include:
  - Age, Gender, BMI  
  - Smoking, Alcohol Use, Physical Activity  
  - Blood Pressure, Glucose, Cholesterol  
  - Geospatial region codes (for policy insight)  
  - Label: Presence of cardiovascular disease

---

## AI Models and Framework

- Artificial Neural Network (ANN) with ReLU and softmax layers  
- Compared with:
  - Logistic Regression  
  - Decision Trees  
- Trained and tested using:
  - Cross-validation  
  - Grid search for hyperparameter tuning

---

## Methodology

- Big data ingestion pipeline (simulated or Spark-based)  
- Feature vectorization and normalization  
- Multi-layer ANN architecture optimized for precision and recall  
- Evaluation using:
  - Accuracy  
  - Confusion Matrix  
  - ROC Curve

---

## Results and Impact

- ANN achieved 99% accuracy with strong recall  
- Designed for use in real-time health dashboards or public health systems  
- Supports health policy planning by mapping cardiovascular risk across regions
