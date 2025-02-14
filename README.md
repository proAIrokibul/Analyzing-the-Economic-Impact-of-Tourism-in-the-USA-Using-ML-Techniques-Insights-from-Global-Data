# Analyzing-the-Economic-Impact-of-Tourism-in-the-USA-Using-ML-Techniques-Insights-from-Global-Data
## 🚀 Project Overview  
This project applies machine learning classification techniques to analyze the **economic impact of tourism** using various economic indicators. The goal is to build **predictive models** to classify economic outcomes based on tourism-related features. 

---

## 📌 Key Objectives  
- ✅ Perform **Exploratory Data Analysis (EDA)** to uncover trends and patterns  
- ✅ Preprocess data to handle **missing values, feature scaling, and encoding**  
- ✅ Apply **classification models** (Logistic Regression, Random Forest, Gradient Boosting)  
- ✅ Evaluate model performance using **accuracy, precision, recall, and F1-score**  
- ✅ Visualize **feature importance** to identify key economic drivers  

---

## 📝 Dataset Information  
The dataset consists of tourism-related economic indicators.  

### 🔹 Key Features:  
- `tourism_receipts` - Revenue from international visitors  
- `tourism_arrivals` - Number of international tourists  
- `tourism_exports` - Revenue from tourism services  
- `tourism_expenditures` - Money spent by tourists  
- `gdp` - Gross Domestic Product of the country  
- `inflation` - Annual inflation rate  
- `unemployment` - Unemployment percentage  

---

## 🔎 Exploratory Data Analysis (EDA) & Visualizations  
The project includes **10+ insightful visualizations**, such as:  
📈 **Time-series trends** of tourism indicators  
📊 **Correlation heatmaps** between economic factors  
📌 **Bar plots** for feature distributions  
📊 **Pair plots** to visualize relationships  
📍 **Geo-visualizations** of tourism impact  

---

## 🤖 Machine Learning Models Used & Performance  
Three classification models were trained and evaluated:  

### 📌 Logistic Regression Results  
✅ **Accuracy**: 72.18%  
✅ **Precision, Recall, F1-Score:**  
```
              precision    recall  f1-score   support

           0       0.65      0.29      0.40       429
           1       0.73      0.93      0.82       901

    accuracy                           0.72      1330
   macro avg       0.69      0.61      0.61      1330
weighted avg       0.71      0.72      0.68      1330
```

---

### 📌 Random Forest Results  
✅ **Accuracy**: 98.27%  
✅ **Precision, Recall, F1-Score:**  
```
              precision    recall  f1-score   support

           0       0.97      0.97      0.97       429
           1       0.99      0.99      0.99       901

    accuracy                           0.98      1330
   macro avg       0.98      0.98      0.98      1330
weighted avg       0.98      0.98      0.98      1330
```

---

### 📌 Gradient Boosting Results  
✅ **Accuracy**: 94.74%  
✅ **Precision, Recall, F1-Score:**  
```
              precision    recall  f1-score   support

           0       0.93      0.91      0.92       429
           1       0.96      0.97      0.96       901

    accuracy                           0.95      1330
   macro avg       0.94      0.94      0.94      1330
weighted avg       0.95      0.95      0.95      1330
```

---

## 🔬 Feature Importance Analysis  
To understand **which features impact economic classification the most**, feature importance is extracted using:  
- ✅ **Tree-based Feature Importance** (Random Forest, Gradient Boosting)  
- ✅ **SHAP (SHapley Additive exPlanations)** for interpretability  
- ✅ **Coefficient Analysis** (Logistic Regression)  

---

## 📊 Results & Model Performance  
All models are evaluated using:  
- ✅ **Accuracy, Precision, Recall, and F1-Score**  
- ✅ **Confusion Matrix Visualization**  
- ✅ **ROC & AUC Curve Analysis**  


## 📢 Conclusion  
This project provides **data-driven insights** into the impact of tourism on the economy, leveraging **machine learning classification models**. The study highlights key **economic indicators**, offering valuable insights for policymakers, economists, and tourism industry stakeholders.  

