# 🧠 Gen Z Social Media Addiction Classification

## 📌 Project Overview

Social media usage among Gen Z teenagers is rapidly increasing. This project uses Machine Learning to **classify the addiction level** of teenagers based on their social media behavior patterns — helping identify at-risk individuals early.

> 📱 More Usage → High Addiction → Low Mental Health

## 📂 Dataset

- **Size:** 1,000,000 rows × 12 columns
- **No missing values**

| Label | Meaning |
|-------|---------|
| 0.0 | Low Addiction ✅ |
| 1.0 | Medium Addiction ⚠️ |
| 2.0 | High Addiction 🚨 |

## 🔍 EDA

- Correlation Heatmap (seaborn, coolwarm)
- daily_usage_hours ↔ mental_health_score = **-0.76**
- Class Imbalance found → Fixed with RandomUnderSampler

## ⚙️ Preprocessing

- StandardScaler for numerical columns
- RandomUnderSampler for class imbalance

## 🤖 Model

- **XGBoost Classifier**
- Train/Test Split: 80/20

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | 99% |
| Precision | 100% |
| Recall | 99% |
| F1 Score | 100% |

## 🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, Seaborn, Google Colab

## 👨‍💻 Author

pragadeeshwaran
