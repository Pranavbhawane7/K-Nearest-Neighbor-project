# K-Nearest Neighbors (KNN) Classification Project

---

## Project Overview
This project demonstrates the implementation of a **K-Nearest Neighbors (KNN)** classifier using Python and scikit-learn.  
It covers the full workflow:
- Feature scaling with `StandardScaler`
- Train-test split
- Model training and evaluation
- Error rate analysis using the elbow method
- Performance metrics (confusion matrix & classification report)

---

## Dataset
- Contains multiple numerical features (e.g., WTT, PTI, EQW, SBI, etc.)
- Target column: **`TARGET CLASS`**
- Features standardized to ensure fair distance calculations in KNN.

---

## Steps Implemented
1. **Data Preprocessing**
   - Dropped target column for scaling
   - Applied `StandardScaler` to normalize features

2. **Train-Test Split**
   - 70% training data, 30% testing data
   - Target labels converted to 1D arrays

3. **Model Training**
   - Implemented KNN classifier
   - Tested multiple values of K (neighbors)

4. **Model Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - Error rate vs. K plot (Elbow Method)

---

##  Results
- 
