# K-Nearest Neighbors (KNN) Classification - Customer Segmentation

This project uses the **K-Nearest Neighbors (KNN)** algorithm to classify customers based on demographic and behavioral features from the `telecust.csv` dataset. The goal is to predict the **customer category (`custcat`)** to better understand customer segments and inform marketing strategies.

---

## 📁 Dataset

**`telecust.csv`** includes various features such as:
- `marital` – Marital status
- `region_*` – Encoded region information
- `reside_*` – Encoded residential categories
- `ed_*` – Education level indicators
- `tenure` – Duration of customer relationship
- `age`, `income`, `employ`, `address` – Demographic details
- `custcat` – 🎯 **Target variable** (Customer Category)

---

## ⚙️ Tools & Libraries

- **Python**
- **Pandas** – Data loading and preprocessing
- **Scikit-learn** – Machine learning (KNN, train-test split, scaling)
- **Matplotlib** – Visualization

---

## 📊 Model Performance

- Accuracy Score: **0.34**
- Confusion matrix and evaluation metrics included in the output

> Note: Accuracy may vary depending on the value of `k` and data scaling. Feature scaling was done using `StandardScaler` for improved performance.

---

## 📈 Future Improvements

- Hyperparameter tuning with cross-validation
- Feature selection to reduce dimensionality
- Try alternative models (e.g., Decision Tree, Random Forest)

---
