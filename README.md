# 💼 Predicting Income Using Census Data

**Author:** Tanuj Ranjith
**Program:** Stanford Pre-Collegiate Summer Institutes — Intro to Machine Learning

---

## 🔍 How to View the Notebook

You can view the notebook in several ways:

1. **Directly on GitHub:** Click on the `.ipynb` file.
2. **If it doesn’t render properly:**

   * Download it and open locally in **Jupyter Notebook** or **VS Code**.
   * Or open it on **Google Colab** here:
     👉 [Open in Google Colab](https://colab.research.google.com/drive/1D2gxvpAm6bbFq-KTIgBfaFN_Scq8rems#scrollTo=d3f54335-433e-4d6d-91b7-590775ace0b8)

---

## 🧠 Project Description

A machine-learning project completed as part of the **Stanford Pre-Collegiate Intro to Machine Learning** program.
The goal was to predict whether a person’s income exceeds **$50K/year** using the **Adult Income dataset** from the **UCI Machine Learning Repository**.

Performed:

* **Data cleaning**, **label encoding**, and **exploratory data analysis**
* **Feature preprocessing** for numerical and categorical variables
* **Model training and evaluation** using various classifiers

---

## ⚙️ Models Used

* **Tuned AdaBoost**
* **Gradient Boosting**
* **XGBoost**
* **AdaBoost**
* **Tuned Gradient Boosting**
* **Tuned Bagging Classifier**
* **Random Forest**
* **Bagging Classifier**
* **Logistic Regression**
* **Tuned Random Forest**
* **Decision Tree**
* **Tuned Decision Tree**
* **Support Vector Machine (SVM)**

---

## 📊 Dataset Details

* **Source:** UCI Adult Census Dataset
* **Records:** 48,842 | **Features:** 14
* **Target:** `income` → `>50K` or `<=50K`
* **Feature Examples:** age, education, occupation, marital-status, race, sex, hours-per-week, capital-gain/loss, native-country

---

## 📈 Performance Overview

| Model               | Accuracy | Recall | Precision | F1        |
| ------------------- | -------- | ------ | --------- | --------- |
| **Tuned AdaBoost**  | 0.868    | 0.612  | 0.805     | **0.679** |
| Gradient Boosting   | 0.865    | 0.589  | 0.761     | 0.667     |
| XGBoost             | 0.874    | 0.675  | 0.756     | 0.704     |
| Logistic Regression | 0.831    | 0.454  | 0.715     | 0.549     |

**Tuned AdaBoost** achieved the best overall performance, balancing recall and precision.
Top predictors included **education**, **capital gain**, and **hours-per-week**.

---

## 🧩 Libraries & Tools

Developed using **Python** with:
`scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`.

---

## 🚀 Future Improvements

* Improve recall using deeper ensemble architectures or SMOTE balancing.
* Add model explainability tools like **SHAP** or **LIME**.
* Experiment with neural networks for feature abstraction.

---

## 📚 References

* [UCI Machine Learning Repository — Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
