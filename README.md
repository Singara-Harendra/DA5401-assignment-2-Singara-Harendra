## 👨‍💻 Author  

Name : **Singara Harendra** 

Roll Number : DA25M028

# 🍄 Mushroom Classification with PCA & Logistic Regression  

## 📌 Overview  
This project explores **dimensionality reduction, visualization, and classification** using the **Mushroom Dataset**.  
We apply **Principal Component Analysis (PCA)** to reduce dimensionality and compare the performance of a **Logistic Regression classifier** trained on:  
1. Original (one-hot encoded) features  
2. PCA-transformed features  

The objective is to evaluate how PCA impacts model performance, interpretability, and efficiency.  

---

## 📂 Contents  
- **Exploratory Data Analysis (EDA)**  
  - Dataset loading & preprocessing  
  - One-hot encoding of categorical variables  
  - Standardization of features  

- **Principal Component Analysis (PCA)**  
  - Scree plot with explained variance  
  - Identifying number of components to retain (≥95% variance)  
  - 2D visualization of first two PCs  

- **Classification with Logistic Regression**  
  - Baseline model (original features)  
  - PCA-transformed model  
  - Performance metrics (accuracy, precision, recall, F1-score)  
  - Confusion matrices for both models  

- **Comparison & Analysis**  
  - Trade-off between dimensionality and information loss  
  - Role of PCA in handling collinearity and redundancy  
  - Insights on using Logistic Regression as a surrogate performance measure  

---

## 📊 Dataset  
The dataset used is the **Mushroom Classification Dataset** from Kaggle:  
👉 [Mushroom Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification)  

---

## ⚙️ Requirements  
Install dependencies with:  

```bash
pip install numpy pandas matplotlib seaborn scikit-learn


