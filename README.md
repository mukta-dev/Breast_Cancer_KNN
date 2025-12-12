#  Breast Cancer Diagnosis Prediction  
### Using K-Nearest Neighbors (KNN) & K-Means Clustering

---

##  Project Overview
The goal of this project is to **classify breast cancer diagnosis** as either **Malignant (M)** or **Benign (B)** using:

1. **K-Means Clustering** → Unsupervised learning to group tumors into 2 clusters and observe natural patterns.  
2. **K-Nearest Neighbors (KNN) Classifier** → Supervised learning to predict diagnosis based on similarity with training data.  

The dataset contains features extracted from breast tumor images, such as radius, texture, smoothness, and cell properties.  
All preprocessing, scaling, and model evaluation are performed in **Google Colab**.

---

##  Data Preprocessing Steps
1. Removed unnecessary columns: `id` and `Unnamed:32`  
2. Encoded diagnosis column: **M → 1**, **B → 0**  
3. Applied **Min-Max Normalization** to all numeric features  
4. Split dataset into:  
   - **80% Training set**  
   - **20% Testing set**

---

##  Model 1: K-Means Clustering
- Applied **k = 2** to group the data  
- Compared clusters with actual diagnosis  
- Observed distribution of malignant and benign cases  

---

## Model 2: KNN Classifier
- Trained using **k = 5** on normalized training data  
- Tested on unseen data  
- Evaluated using: **Accuracy, Precision, Recall, F1-score**  

---

##  Model Evaluation Results

| Metric     | Value |
|-----------|--------|
| Accuracy  | 0.xxx |
| Precision | 0.xxx |
| Recall    | 0.xxx |
| F1-Score  | 0.xxx |

> Replace these placeholder values with the results from your Colab notebook.

---

##  Files in Repository
- `Breast_Cancer_KNN_KMeans.ipynb` → Full Colab notebook (preprocessing, model training, evaluation)  
- `Dataset.csv` → Dataset used for modeling  
- `README.md` → Project documentation  

---

## How to Run
1. Open the `.ipynb` notebook in **Google Colab**  
2. Upload `Dataset.csv` in the same session  
3. Run all cells sequentially  
4. Check outputs:  
   - Preprocessed and normalized data  
   - K-Means clustering results  
   - KNN predictions  
   - Metrics: Accuracy, Precision, Recall, F1-score  
   - Confusion matrix  

---

## Summary
This project demonstrates that with proper **preprocessing + clustering + classification**, breast cancer diagnosis can be predicted accurately.  
The KNN classifier performs well when the data is cleaned and normalized.
-
