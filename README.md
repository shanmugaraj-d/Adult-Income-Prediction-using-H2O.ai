# 💼 Adult Income Prediction using H2O.ai

## 📊 Project Overview
This project builds a binary classification model to predict whether an individual earns **more than 50K** or **less than or equal to 50K** per year. It uses the **Adult Income Dataset** from the UCI Machine Learning Repository and leverages **H2O.ai** for model building, training, and evaluation.

---

## 📁 Dataset Summary

- **Source**: [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- **Goal**: Predict whether income is `>50K` or `<=50K`
- **Type**: Supervised Learning (Binary Classification)
- **Target Variable**: `income`

### 🔑 Features

- **Numerical**: `age`, `fnlwgt`, `education-num`, `capital-gain`, `capital-loss`, `hours-per-week`
- **Categorical**: `workclass`, `education`, `marital-status`, `occupation`, `relationship`, `race`, `sex`, `native-country`

---

## 🛠️ Setup & Installation

1. Install the required Python package:

```bash
pip install -f https://h2o-release.s3.amazonaws.com/h2o/latest_stable_Py.html h2o
