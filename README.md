# KNN-Classification-and-KD-Tree-Optimization

This project applies the **K-Nearest Neighbors (KNN)** algorithm to a video game sales dataset to **predict game genres**. It focuses on **model tuning**, **KD-Tree optimization**, and **efficiency analysis** of distance-based learning methods.

---

## 🎯 Project Overview

The main objective was to build and optimize a **KNN classifier** that predicts the genre of a video game using sales and platform data. The project explores how **KD-Tree structures** improve the speed of nearest-neighbor searches compared to brute-force methods.

---

## ⚙️ Key Steps

* **Data Preparation:** Cleaned and transformed the dataset using `pandas` and `numpy`. Applied **feature scaling** with `StandardScaler` and encoded categorical variables (`Platform`) with `OneHotEncoder`.
* **Model Building:** Implemented a **KNN Classifier** using `scikit-learn` and tuned parameters such as the number of neighbors (`k`), distance metric (`p`), and weights through `GridSearchCV` to achieve optimal accuracy.
* **KD-Tree Optimization:** Constructed a **KD-Tree** to accelerate neighbor lookups, demonstrating how spatial partitioning reduces computational cost compared to brute-force searches.
* **Model Evaluation:** Generated a **classification report** and **confusion matrix** to assess precision, recall, and F1-score across genres, highlighting common misclassifications.
* **Backend Analysis:** Compared different search algorithms (`kd_tree`, `ball_tree`, and `brute`) to understand their performance in varying data dimensions.

---

## 🧠 Key Takeaways

This project highlights how **feature preprocessing**, **hyperparameter tuning**, and **efficient search structures** like KD-Trees can significantly enhance the performance of KNN models. It also demonstrates the importance of balancing accuracy with computational efficiency in real-world machine learning workflows.
