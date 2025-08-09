# 💤 Factors Affecting Sleep Quality

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/ML-Linear%20Regression-green?logo=scikit-learn" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

<p align="center">
  <em>Analyze, visualize, and predict sleep quality using health and lifestyle data</em>
</p>

---

## 📌 Project Overview
This project explores various **health and lifestyle factors** affecting **sleep quality**.  
We:
- Cleaned and preprocessed a dataset containing health indicators, physical activity, BMI, and sleep disorders.
- Conducted **correlation analysis** to find relationships between variables.
- Visualized **patterns and trends** using heatmaps and bar charts.
- Built a **Linear Regression model** to predict sleep quality from given parameters.

---

## 📂 Repository Structure
```plaintext
Factors-Affecting-Sleep-Quality/
│
├── dataset.csv                # Dataset used in analysis
├── research.ipynb              # Main analysis and ML model
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```

---

## 📊 Data Analysis Highlights
- **Correlation Heatmaps**:
  - Physical Activity ↔ Sleep Quality
  - Stress Level ↔ Sleep Duration
  - Sleep Disorder ↔ BMI Category
- **Category Analysis**:
  - Average Sleep Quality by BMI, Occupation, and Age
- **Prediction**:
  - ML model predicts **Quality of Sleep** with `R²` accuracy.

---

## 🛠 Tech Stack
- **Python** 🐍
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **scikit-learn** – Machine Learning

---

## 📈 Visualizations
<p align="center">
  <img src="https://github.com/AradRouhaniiiiii/Factors-Affecting-Sleep-Quality/raw/main/assets/heatmap1.png" width="45%" />
  <img src="https://github.com/AradRouhaniiiiii/Factors-Affecting-Sleep-Quality/raw/main/assets/heatmap2.png" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/AradRouhaniiiiii/Factors-Affecting-Sleep-Quality/raw/main/assets/barplot_bmi.png" width="45%" />
  <img src="https://github.com/AradRouhaniiiiii/Factors-Affecting-Sleep-Quality/raw/main/assets/barplot_occ.png" width="45%" />
</p>

---

## 🤖 Machine Learning Model
We trained a **Linear Regression** model using:
- **Features**: Gender, Age, Occupation, Sleep Duration, Physical Activity Level, Stress Level, BMI Category, Heart Rate, Daily Steps, Sleep Disorder.
- **Target**: Quality of Sleep.

**Example Prediction:**
```python
input_data = {
    'Gender': 1,  # Female
    'Age': 59,
    'Occupation': 0,  # Nurse
    'Sleep Duration': 8.1,
    'Physical Activity Level': 75,
    'Stress Level': 3,
    'BMI Category': 2,  # Overweight
    'Heart Rate': 68,
    'Daily Steps': 7000,
    'Sleep Disorder': 1  # Sleep Apnea
}
```

---

## 📬 Connect With Me
<p align="center">
  <a href="https://www.instagram.com/AradRouhaniiiiii"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" /></a>
  <a href="https://t.me/aradrouhaniiiiii"><img src="https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white" /></a>
  <a href="https://www.kaggle.com/aradrouhani"><img src="https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white" /></a>
</p>

---
