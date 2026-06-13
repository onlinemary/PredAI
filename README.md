# Intro to Predictive AI: Classification, Clustering, and Regression

Welcome to my Predictive AI learning repository! This project serves as a structured portfolio demonstrating my foundational knowledge in Machine Learning and Data Science. It includes hands-on implementations of Supervised and Unsupervised learning algorithms using standard datasets and real-world scenarios.

## 🛠️ Technologies & Libraries Used
* **Language:** Python
* **Machine Learning:** Scikit-Learn
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 📌 Repository Structure & Projects

### 1. Classification (Supervised Learning)
This section focuses on predicting categorical labels using multi-class and binary classification approaches.

* **Digits Multi-Class Classification:** * *Dataset:* `sklearn.datasets.load_digits`
    * *Description:* Implemented a model to classify handwritten digits from 0 to 9.
* **Digits Binary Classification (0 vs. 1):** * *Dataset:* `sklearn.datasets.load_digits` (Filtered for 0 and 1)
    * *Description:* A focused binary classification task to optimize model performance on distinguishing between two highly distinct digits.
* **Geometric Shape Classification:** * *Dataset:* Synthetically generated image data.
    * *Description:* Built a classifier to distinguish between basic geometric shapes (Circles vs. Rectangles).

### 2. Clustering (Unsupervised Learning)
This section explores finding hidden patterns in unlabeled data using clustering techniques.

* **Digits Unsupervised Clustering:** * *Dataset:* `sklearn.datasets.load_digits`
    * *Description:* Grouped handwritten digit images into 10 distinct clusters without using their predefined labels to evaluate clustering accuracy.
* **Synthetic Blobs Clustering:** * *Dataset:* `sklearn.datasets.make_blobs`
    * *Description:* Experimented with K-Means clustering on isotropic Gaussian blobs to understand cluster density and separation.

### 3. Regression (Supervised Learning)
This section focuses on predicting continuous numerical values.

* **CO2 Emission Prediction:** * *Dataset:* Custom Excel dataset containing vehicle/industrial specifications.
    * *Description:* Developed a regression model to estimate $CO_2$ production levels based on environmental and mechanical features.

---

## 🚀 Key Takeaways & Skills Developed
* **Data Preprocessing:** Handling feature scaling, train-test splitting, and data filtering using Pandas and NumPy.
* **Model Selection:** Working with classifiers, regressors, and clustering algorithms (e.g., K-Means, Logistic Regression).
---
*This repository is part of my academic journey to master Artificial Intelligence and Data Science.*
