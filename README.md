# Iris-Flower-Classification-KNN-VS-Random-Forest
Iris Flower Classification using K-Nearest Neighbors (KNN) and Random Forest algorithms. This project compares the performance of KNN and Random Forest models on the classic Iris dataset, focusing on classification accuracy, evaluation metrics, and model behavior.


# 🌸 Iris Flower Classification: KNN VS Random Forest

## 📌 Project Overview

This project focuses on the **classification of Iris flower species** using two supervised machine learning algorithms:  
**K-Nearest Neighbors (KNN)** and **Random Forest**.

The main objective is to **compare the performance** of both models using multiple evaluation metrics, including **accuracy**, **confusion matrix**, **classification report**, and **ROC curve analysis**.

---

## 📊 Dataset Description

- **Dataset:** Iris Dataset (from scikit-learn)
- **Total Samples:** 150
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target Classes:**
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

The Iris dataset is a well-known benchmark dataset commonly used for evaluating classification algorithms.

---

## ⚙️ Machine Learning Algorithms

### 🔹 K-Nearest Neighbors (KNN)
KNN is a **distance-based algorithm** that classifies data points based on the majority class among the nearest neighbors. It is simple, intuitive, and effective for small datasets.

### 🔹 Random Forest
Random Forest is an **ensemble learning algorithm** that builds multiple decision trees and combines their predictions. It reduces overfitting and improves model accuracy and robustness.

---

## 🧪 Project Workflow

1. Load and explore the Iris dataset
2. Perform data preprocessing
3. Split the dataset into training and testing sets
4. Train KNN and Random Forest models
5. Evaluate models using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - ROC Curve (Macro-Average)
6. Compare the results

---

## 📈 Model Evaluation & Results

### 🔹 Accuracy Comparison
Both models achieved high accuracy on the Iris dataset, demonstrating effective classification of flower species.

### 🔹 Confusion Matrix & Classification Report
The confusion matrices and classification reports show that both classifiers correctly predict most samples, with minimal misclassification.

### 🔹 ROC Curve Comparison (Macro-Average)
<img width="790" height="590" alt="output" src="https://github.com/user-attachments/assets/85c65ddd-f9aa-4a6b-afc7-85e344854d0b" />

The **Receiver Operating Characteristic (ROC) curve** was used to further evaluate the performance of both classifiers.  
A **macro-average ROC curve** was applied to handle the multi-class classification problem.

- **KNN AUC Score:** 0.975
- **Random Forest AUC Score:** 0.993

The ROC curves indicate that:
- Both models perform significantly better than random guessing.
- Random Forest achieves a higher AUC score, demonstrating better class separation and overall performance.
- Random Forest shows greater robustness and consistency across all classes compared to KNN.

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohammad-Joumaa/Iris-Flower-Classification-KNN-VS-Random-Forest.git
````

2. Navigate to the project directory:

   ```bash
   cd Iris-Flower-Classification-KNN-VS-Random-Forest
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the file:

   ```text
   Data_Mining_Project(Iris).ipynb
   ```

---

## 🎯 Conclusion

This project demonstrates how different machine learning algorithms perform on the same dataset. While both KNN and Random Forest achieve high accuracy, **Random Forest outperforms KNN** in terms of robustness and ROC-AUC score, making it the more reliable model for this classification task.

---

## 👨‍💻 Author

**Mohammad Joumaa**
Data Mining & Machine Learning Project

---


::contentReference[oaicite:0]{index=0}
```
