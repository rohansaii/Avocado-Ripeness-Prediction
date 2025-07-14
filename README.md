# 🥑 Avocado Ripeness Analysis using Data Science & Machine Learning

This project demonstrates how data science techniques and machine learning models can be used to **predict the ripeness stage of avocados** based on physical characteristics such as firmness, hue, brightness, sound levels, and size.

## 📌 Objective

To analyze avocado ripeness stages and build a predictive model that can classify the ripeness based on measurable features.

---

## 📂 Dataset

- **Source**: `avocado_ripeness_dataset.csv`  
- **Attributes**:
  - `firmness`
  - `hue`
  - `saturation`
  - `brightness`
  - `color_category`
  - `sound_db`
  - `weight_g`
  - `size_cm3`
  - `ripeness` (Target)

---

## 🔎 Exploratory Data Analysis (EDA)

- Checked for missing values and data types
- Visualized:
  - Ripeness distribution (count & pie chart)
  - Firmness vs Sound Level (scatter plot)
  - Firmness by Ripeness stage (box plot)
  - Firmness distribution (histogram)
  - Feature correlations (heatmap)

---

## 🧠 Machine Learning Model

- **Model**: Random Forest Classifier
- **Preprocessing**:
  - Converted categorical columns using one-hot encoding
  - Converted `ripeness` into numerical labels
  - Aligned `X_train` and `X_test` after encoding
- **Training & Evaluation**:
  - Train-test split (80-20)
  - Accuracy achieved: `100%` on test data
  - Detailed classification report with precision, recall, and F1-scores

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---


## 📜 Results

The model can accurately classify avocados into ripeness stages such as:
- Hard
- Pre-conditioned
- Breaking
- Firm-ripe
- Ripe

This demonstrates how simple sensory and physical measurements can be effectively used in **agri-tech solutions** using machine learning.

---


