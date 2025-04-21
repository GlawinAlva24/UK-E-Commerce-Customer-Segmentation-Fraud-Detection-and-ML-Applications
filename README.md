# UK-E-Commerce-Customer-Segmentation-Fraud-Detection-and-ML-Applications
# 📜 UK E-Commerce Customer Segmentation, Fraud Detection, and Machine Learning Applications

This project explores key machine learning techniques applied to real-world e-commerce datasets, focusing on customer segmentation and fraud detection.
It covers:

Unsupervised Learning (K-Means Clustering, Hierarchical Clustering, PCA)

Reinforcement Learning (Grid World Utilities and Optimal Policies)

Dimensionality Reduction (Factor Analysis)

Supervised Learning (Fraud Detection using Random Forest, Gradient Boosting, Logistic Regression)

---

## 📚 Project Highlights

It covers:

- **Unsupervised Learning**:  
  - K-Means Clustering
  - Hierarchical Clustering
  - Principal Component Analysis (PCA)

- **Reinforcement Learning**:  
  - Grid World Utilities
  - Optimal Policies for highlighted states

- **Dimensionality Reduction**:  
  - Factor Analysis on housing datasets to identify hidden factors

- **Supervised Learning**:  
  - Fraud Detection using:
    - Random Forest
    - Gradient Boosting
    - Logistic Regression

---

📂 Folder Structure

uk-ecommerce-segmentation-fraud-ml-applications/  
├── README.md  
├── datasets/  
│   ├── ecommerce.csv                       # Dataset for customer segmentation   
│   ├── kc_house_data_reduced.csv           # Dataset for dimensionality reduction  
│   └── bs140513_032310.csv                 # Dataset for fraud detection  
├── notebooks/  
│   ├── 1_unsupervised_customer_segmentation.ipynb  
│   ├── 2_reinforcement_learning_grid.ipynb  
│   ├── 3_dimensionality_reduction_factor_analysis.ipynb  
│   └── 4_fraud_detection_ml_models.ipynb  
├── reports/  
│   └── coursework_report.pdf               # final coursework report (PDF)  
├── environment/  
    └── requirements.txt                    # Python libraries needed  



 ---
 
## 🛠️ Environment Setup
Install all required libraries with:
pip install -r environment/requirements.txt

**Main libraries used:**

pandas

numpy

scikit-learn

matplotlib

seaborn

imbalanced-learn

---

## 📜 Reports

- 📄 [Coursework Full Report](reports/coursework_report.pdf)

---

## 🔥 Key Results

### 1. Customer Segmentation (Unsupervised Learning)

- Optimal Clusters found: **4**
- Silhouette Score: **0.64**
- PCA Visualization Example:

> _(Optional: Insert a PCA plot image if available.)_

---

### 2. Reinforcement Learning (Grid World)

- Example Optimal Policy Grid:  
['↑', '→', '→', '→']  
['↑', '→', '↓', '←']  
['↑', '↑', '↓', '←']  
['→', '→', '↓', '★']  

---

### 3. Dimensionality Reduction (Factor Analysis)

- Factors Retained: **3**
- Total Explained Variance: **79.5%**

---

### 4. Fraud Detection (Supervised Learning)

| Model                | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Random Forest        | 0.988    | 0.93      | 0.92   | 0.925    |
| Gradient Boosting    | 0.985    | 0.90      | 0.89   | 0.895    |
| Logistic Regression  | 0.972    | 0.84      | 0.82   | 0.83     |

✅ **Best Model**: Random Forest Classifier

---

## 🏛️ Academic Context
This project was completed as part of academic coursework for the MSc in Artificial Intelligence and Business Strategy at Aston University.

---

## 👨‍💻 About Me

**Glawin Alva**  
AI-Focused Data Engineer | Data Science Enthusiast  
📍 Birmingham, United Kingdom  
📧 glawin24@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/glawin-alva-gg)  
🐙 [GitHub](https://github.com/GlawinAlva24)



