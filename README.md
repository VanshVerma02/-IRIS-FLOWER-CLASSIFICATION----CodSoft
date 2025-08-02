# 🌸 Iris Flower Classification

This project uses the classic Iris dataset to build a machine learning model that classifies iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on their sepal and petal measurements. It demonstrates a step-by-step pipeline including data preprocessing, visualization, model training, and evaluation.

---

## 📂 Dataset Overview

The Iris dataset contains 150 samples with the following features:

* **Sepal length (cm)**
* **Sepal width (cm)**
* **Petal length (cm)**
* **Petal width (cm)**
* **Species** *(Target: Setosa, Versicolor, Virginica)*

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas, NumPy
* Seaborn, Matplotlib (for charts)
* Scikit-learn (for modeling and evaluation)

---

## 📊 Workflow Summary

### 🔹 Data Exploration

* No missing values found
* All three species are equally represented (50 samples each)
* Pairplots and correlation heatmaps helped visualize feature relationships and patterns across species

### 🔹 Preprocessing

* Standardized features using **StandardScaler**
* Split dataset into training (80%) and testing (20%) sets

### 🔹 Model Training

* **Logistic Regression** was used for classification
* Trained with a maximum of 200 iterations to ensure convergence

### 🔹 Evaluation Results

* ✅ **Accuracy**: `96.67%`
* 📄 **Classification Report**:

  * High precision, recall, and F1-score across all three species
* 📉 **Confusion Matrix**:

  * Minimal misclassifications
  * Visualized using a heatmap for clarity

---

## 📌 Conclusion

This project showcases how a simple linear model like **Logistic Regression** can effectively classify flowers based on clear numeric features. The Iris dataset remains a strong starting point for beginners to understand supervised classification tasks.

---

## 👤 Author

**Vansh Verma**
*Data Science & Machine Learning Enthusiast*
