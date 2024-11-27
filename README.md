# Abalone Classification and Clustering Project

This project implements two machine learning techniques to analyze the Abalone dataset obtained from the UCI Machine Learning Repository:  
1. **Classification Model using Naive Bayes**  
2. **Clustering Model using K-Means**

---

## Models

### 1. Classification Model: Naive Bayes
- **Description:** This model predicts the age of abalones based on various physical measurements using the Naive Bayes algorithm.
- **Accuracy:** 0.98
- **Metrics:**
  - **Precision:** 
    - Class 0: 1.00
    - Class 1: 0.95
    - Class 2: 0.98
  - **Recall:** 
    - Class 0: 0.95
    - Class 1: 1.00
    - Class 2: 1.00
  - **F1-Score:** 
    - Class 0: 0.98
    - Class 1: 0.97
    - Class 2: 0.99

- **Confusion Matrix:**
   [[354 13 4] [ 0 239 0] [ 0 0 226]]

---

### 2. Clustering Model: K-Means
- **Description:** This model groups the abalones into clusters based on their physical attributes using the K-Means algorithm.
- **Best number of clusters (k):** 2
- **Cluster Summary:**

Cluster 0:
Mean Length: 0.6128
Mean Diameter: 0.4816
Mean Rings: 11.33

Cluster 1:
Mean Length: 0.4214
Mean Diameter: 0.3227
Mean Rings: 8.32

---

## Dataset
The dataset can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/1/abalone).
The Abalone dataset contains various physical measurements of abalones, including:
- **Sex:** (M, F, I)
- **Length**
- **Diameter**
- **Height**
- **Whole Weight**
- **Shucked Weight**
- **Viscera Weight**
- **Shell Weight**
- **Rings** (used as the target variable for age prediction)

---

## Prerequisites  
Make sure you have the following installed on your machine:  
- Python 3.8 or later  
- Jupyter Notebook  
- pip (Python package manager)

---

## How to Run
1. Clone this repository:
   ```bash
   git@github.com:fazza-abiyyu/Classification-Models-for-Abalone-using-Naive-Bayes-and-K-Means.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd Classification-Models-for-Abalone-using-Naive-Bayes-and-K-Means
   ```
3. Open and run Jupyter Notebook:
   ```bash
   jupyter notebook Abalone_dengan_Naive_Bayes_dan_K_Means.ipynb
