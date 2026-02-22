# Research Papers: AI & Big Data for Cardiovascular Disease Detection

Welcome to my research repository! Here you'll find concise summaries and documentation for two IEEE-published papers focused on leveraging machine learning and big data for early detection of cardiovascular disease (CVD).

---

## 📚 Table of Contents
1. [Overview](#overview)
2. [Paper 1: Classical ML for CVD Risk Detection](#paper-1)
3. [Paper 2: Big Data & Neural Networks for CVD Prediction](#paper-2)

---

## <a name="overview"></a>Overview
These projects showcase how predictive analytics and artificial intelligence can transform healthcare by enabling early diagnosis and improving patient outcomes. The first paper uses classical ML models, while the second leverages neural networks and scalable big data infrastructure.

---

## <a name="paper-1"></a>Paper 1: Cardio-Vascular Risk Detection System using Machine Learning
**DOI:** [10.1109/iSSSC56467.2022.10051216](https://doi.org/10.1109/iSSSC56467.2022.10051216)

### Abstract
Atherosclerosis, the main cause of most cardiovascular conditions, often progresses silently. Early identification through machine learning can guide timely medical intervention. This research experiments with several classification models and achieves 98% accuracy using a Decision Tree Classifier.

### Dataset
- 1,000–1,500 anonymized patient records
- Features: Age, Gender, Resting Blood Pressure, Cholesterol, ECG, Max Heart Rate, Exercise-Induced Angina, Blood Sugar, Cardiovascular risk (binary)

### Models Used
- Decision Tree (Best, 98% accuracy)
- Logistic Regression
- SVM
- KNN
- Naive Bayes

### Methodology
- Data preprocessing (standardization, label encoding)
- Train-test split (stratified)
- 10-fold cross-validation
- Model tuning & evaluation: Accuracy, Precision, Recall, F1 Score, Confusion Matrix

### Results & Impact
- Decision Tree model performed best
- Enables early risk detection and preventive routines
- Suitable for diagnostic tools, hospital systems, or mobile health apps

---

## <a name="paper-2"></a>Paper 2: Big Data Predictive Analytics Model for CVD Detection
**DOI:** [10.1109/iSSSC56467.2022.10051293](https://doi.org/10.1109/iSSSC56467.2022.10051293)

### Abstract
This project extends CVD risk prediction into a big data and AI-driven framework. Using ~1,500 patient records and geospatial health data, it applies Artificial Neural Networks (ANN) to achieve 99% accuracy. The focus is scalable, real-time risk assessment for population-level health.

### Dataset
- ~1,500 patient records (demographic & clinical)
- Features: Age, Gender, BMI, Smoking, Alcohol, Physical Activity, Blood Pressure, Glucose, Cholesterol, Geospatial region codes, CVD label

### AI Models & Framework
- ANN (ReLU, softmax layers)
- Compared with Logistic Regression, Decision Trees
- Training: Cross-validation, grid search for hyperparameter tuning

### Methodology
- Big data ingestion pipeline (simulated/Spark-based)
- Feature vectorization & normalization
- Multi-layer ANN architecture optimized for precision & recall
- Evaluation: Accuracy, Confusion Matrix, ROC Curve

### Results & Impact
- ANN achieved 99% accuracy with strong recall
- Designed for real-time health dashboards/public health systems
- Supports health policy planning by mapping CVD risk across regions

---

For more details, see the full papers or reach out for collaboration!
