# 🍷 Red Wine Quality Prediction Using Machine Learning

Ever wonder what makes a wine "good"?

This project explores the science behind wine quality — beyond price tags and branding — using machine learning models trained on **real-world physicochemical data**.

With every sip of red wine lies a story of acidity, sulfates, alcohol content, and more. I wanted to decode that story using data science.

---

## 📌 Project Overview

This notebook-based project focuses on predicting the quality of red Portuguese "Vinho Verde" wine based solely on its **chemical properties** — no brand names, no marketing fluff, just raw, measurable data.

- ✅ **Binary & Multi-class Classification Approaches**
- 🧪 Dataset from the **UCI Machine Learning Repository**
- 🔍 Models Used: **Support Vector Machine (SVM)** and **Decision Tree**
- 📊 Visualized feature impacts + decision boundaries
- 🧠 Built in **Python (Jupyter Notebook)**

---

## 🎯 Objective

Build a supervised machine learning model to **predict wine quality (0–10)** using 11 physicochemical tests. The goal is to:
- Classify wines as high/low quality
- Understand which chemical properties most affect taste
- Help demystify what “quality” really means in data terms

---

## 🧬 Dataset Details

📚 Source: [UCI Machine Learning Repository – Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
📦 Format: CSV  
📌 Records: 1599 red wine samples  
🔍 Target Variable: `quality` (score between 0 and 10)

### 🔬 Features (Input Variables):

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`

### 🎯 Output:
- `quality` — A score from **0 to 10** rated by wine tasters

---

## 🛠️ Tools & Technologies

- Python 🐍
- Jupyter Notebook 📒
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-Learn (SVM, Decision Tree, Metrics)
- Data Preprocessing & Feature Engineering

---

## 🧠 Models Implemented

### 1️⃣ **Support Vector Machine (SVM)**
- Captures complex boundaries
- Great performance on structured data

### 2️⃣ **Decision Tree Classifier**
- Interpretable and visual
- Shows which features influence quality most

---

## 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1)
- Cross-validation for model stability

---

## 📊 Key Insights

- **Alcohol** and **Sulphates** showed the strongest correlation with wine quality.
- Wines with **lower volatile acidity** tended to score higher.
- Most wines scored between **5 and 7**, showing imbalanced class distribution.

---

---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/red-wine-quality-prediction.git
   ```

Let’s Connect

If you found this interesting, feel free to fork, star ⭐, or open an issue.
Have feedback or suggestions? I’d love to hear from you.
