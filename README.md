# breast-cancer-diagnosis-kernel-pca
Breast cancer classification using Logistic Regression and Kernel PCA for dimensionality reduction. Explores different kernels ('rbf', 'poly', 'sigmoid') and compares model accuracy before and after transformation. Includes visualizations and evaluation metrics.

Sure, here's the updated `README.md` file with your **LinkedIn** and **email** included in the author section:

---

````markdown
# 🧠 Breast Cancer Diagnosis using Kernel PCA and Logistic Regression

This project focuses on classifying breast cancer tumors as **Malignant (M)** or **Benign (B)** using the **Breast Cancer Wisconsin dataset**. It applies **Kernel PCA** for dimensionality reduction and trains a **Logistic Regression** model to compare classification performance with and without Kernel PCA.

---

## 📌 Objectives

- Load and preprocess the dataset
- Handle missing values and scale features
- Visualize feature relationships and target distribution
- Apply **Kernel PCA** with different kernels: `'rbf'`, `'poly'`, `'sigmoid'`
- Train **Logistic Regression** on both original and transformed data
- Compare accuracy and evaluate the best-performing kernel
- Visualize PCA and Kernel PCA projections in 2D

---

## 📊 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📈 Results Summary

| Method               | Accuracy |
|----------------------|----------|
| Without Kernel PCA   | 96.49%   |
| With RBF Kernel PCA  | 97.37%   |
| With Poly Kernel PCA | 96.49%   |
| With Sigmoid Kernel  | 94.73%   |

> 📌 *Best kernel:* `rbf` – It performed best by effectively separating the classes in nonlinear feature space.

---

## 🖼️ Visualizations

- Target distribution bar chart
- Correlation heatmap
- Pairplot of top correlated features
- 2D scatter plot of Kernel PCA-transformed data
- Confusion matrices before and after transformation

---

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/Malatheeswari/breast-cancer-diagnosis-kernel-pca.git
   cd breast-cancer-diagnosis-kernel-pca
````

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook
   Open `Breast_Cancer_Kernel_PCA.ipynb` using Jupyter Notebook or any compatible IDE.

---

## 📂 Dataset

* **Source:** UCI Machine Learning Repository
* **Features:** 30 numeric attributes related to cell nuclei
* **Target:** Diagnosis (`M` = Malignant, `B` = Benign)

---

## 👩‍💻 Author

**Malatheeswari E**
📧 Email: [malathieswaran0@gmail.com](mailto:malathieswaran0@gmail.com)
🔗 LinkedIn: [linkedin.com/in/malatheeswari-e-048b9122a](https://www.linkedin.com/in/malatheeswari-e-048b9122a/)



