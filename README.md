# Chronic Kidney Disease Classification

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A machine learning project for classifying the presence of Chronic Kidney Disease (CKD) in patients based on clinical medical records. This was a learning exercise to explore end-to-end ML workflows, from data preprocessing to model evaluation and comparison.

## 🎯 Objective

Build and compare classification models that can predict whether a patient has CKD based on medical attributes, using a real-world dataset.

## 🧠 Models Compared

- Logistic Regression
- Decision Tree
- Random Forest
- KNN

## 📊 Pipeline Overview

1. **Exploratory Data Analysis (EDA)** — understanding distributions, missing values, and correlations
2. **Data Cleaning & Preprocessing** — handling missing values, encoding categorical features, normalization
3. **Model Training** — fitting each classifier on the processed dataset
4. **Evaluation & Comparison** — comparing models using metrics such as accuracy, precision, recall, and F1-score

## 🛠️ Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Google Colab

## 📂 Project Structure

```text
.
├── README.md
└── ckd_classification.ipynb   # Full pipeline: EDA, preprocessing, training, and evaluation
```

## 🚀 Running the Notebook

The notebook was developed on Google Colab. To run it:

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `ckd_classification.ipynb` or open it directly from GitHub
3. Run all cells in order

Alternatively, you can clone the repo and run it locally with Jupyter:

```bash
git clone https://github.com/isaaoki/ml-ckd-classification.git
cd ml-ckd-classification
jupyter notebook ckd_classification.ipynb
```

> **Note:** Make sure the required libraries are installed (`pandas`, `numpy`, `scikit-learn`, `matplotlib`).

## 📄 Dataset

The dataset used contains clinical attributes of patients (e.g. blood pressure, blood glucose, red blood cells) labeled with the presence or absence of CKD.

[CKD-NHANES 2021-2023: Staged Kidney Disease Dataset](https://www.kaggle.com/datasets/alitaqishah/ckd-nhanes-2021-2023-staged-kidney-disease/data).

## 👥 Authors

Developed as a team project. Contributors:

- Isabela Aoki
- Karol Paiva

## 📄 License

This project is available for educational and portfolio purposes.