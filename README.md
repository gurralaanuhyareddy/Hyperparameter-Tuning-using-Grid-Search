# Hyperparameter Tuning using Grid Search (SVM)

## 📌 Overview

This project demonstrates how hyperparameter tuning using Grid Search improves the performance of a Support Vector Machine (SVM) model. It focuses on selecting optimal values for key parameters such as **C**, **kernel**, and **gamma** to enhance model accuracy and generalisation.

---

## 🎯 Objectives

* Understand the role of hyperparameters in SVM
* Apply Grid Search for systematic optimisation
* Use cross-validation for reliable model evaluation
* Compare baseline and tuned model performance

---

## 📊 Dataset

The dataset used in this project is a synthetic dataset generated using the `make_moons` function.

* Total samples: 600
* Data split: 80% training / 20% testing
* Characteristics: Non-linear and challenging for simple models

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Feature scaling using standardisation
* Train-test split applied

### 2. Baseline Model

* SVM model trained with default parameters
* Used as a reference for comparison

### 3. Hyperparameter Tuning

Grid Search is applied to explore combinations of:

* **C**: 0.1, 1, 10, 100
* **Kernel**: Linear, RBF
* **Gamma**: scale, 0.01, 0.1, 1

### 4. Cross-Validation

* 5-fold cross-validation used
* Ensures reliable and unbiased evaluation

---

## 📈 Results

* Tuned model achieved better performance than the baseline
* Improved decision boundary for nonlinear data
* Reduced misclassification
* Heatmap analysis showed optimal parameter regions

---

## 🔍 Key Insights

* Hyperparameters significantly impact SVM performance
* RBF kernel performs better for nonlinear datasets
* Proper tuning balances **overfitting** and **underfitting**
* Cross-validation improves model reliability

---

## 📐 Visualisations

The project includes:

* Dataset distribution plot
* Baseline vs tuned decision boundaries
* Accuracy comparison
* Grid search heatmap

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* NumPy
* Matplotlib

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Navigate to the project folder:

```bash
cd <repo-name>
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📚 Conclusion

This project shows that Grid Search combined with cross-validation is an effective method for improving machine learning model performance. Proper hyperparameter tuning leads to better accuracy and more generalisable models.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

* Your Name
