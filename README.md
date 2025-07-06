# 📧 Spam Mail Detection using Logistic Regression

This project focuses on building a spam email classifier using Logistic Regression. It was developed and executed on Google Colab and includes steps like preprocessing, handling data imbalance, TF-IDF feature extraction, model training, and evaluation using appropriate metrics.

---

## 📌 Features

- Data preprocessing with null value handling
- Class imbalance addressed using resampling techniques
- TF-IDF vectorization for feature extraction
- Logistic Regression for classification
- Model evaluated using confusion matrix, accuracy-score
- Achieved **98% training accuracy** and **95% testing accuracy**

---

## ⚙️ Technologies Used

- Python (Google Colab)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📊 Confusion Matrix Explanation

The confusion matrix on the testing data is as follows:

|                      | Predicted: Ham | Predicted: Spam |
|----------------------|----------------|-----------------|
| **Actual: Ham**      | 148 (✅)        | 2 (❌)           |
| **Actual: Spam**     | 10 (❌)         | 139 (✅)         |

### 🔍 Interpretation:

- **True Negatives (148):** Ham messages correctly predicted as ham.
- **False Positives (2):** Ham messages incorrectly predicted as spam.
- **False Negatives (10):** Spam messages incorrectly predicted as ham.
- **True Positives (139):** Spam messages correctly predicted as spam.

This confusion matrix demonstrates that the model is well-balanced, with **very low false positives**, which is critical in spam detection systems to avoid wrongly classifying legitimate emails.

---

## 📂 Note on Dataset

The dataset used in this project is not included in this repository. The model was developed on **Google Colab**, and the dataset was loaded manually during execution.

---

## 📌 Future Enhancements

- Explore alternative models like Naive Bayes or Random Forest
- Deploy the model using Streamlit or Flask
- Add model interpretability using SHAP or LIME

---
---

⭐ Feel free to **star** this repository if you found it helpful!


