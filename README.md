# 🩺 Health Risk Prediction using Machine Learning

<div align="center">

# Health Risk Prediction System
### Dual Prediction of Diabetes and High-Risk Pregnancy using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Classifier-green)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

# 📌 Project Overview

Early prediction of diabetes and high-risk pregnancy can significantly improve healthcare outcomes. This project develops a **dual prediction system** by integrating diabetes and maternal health datasets and applying a complete machine learning pipeline for accurate health risk assessment.

The project includes:

- Dataset Integration
- Data Cleaning
- Data Preprocessing
- Train-Test Split
- Feature Scaling
- Principal Component Analysis (PCA)
- SMOTE for Class Balancing
- Hyperparameter Tuning
- Model Comparison
- Final Health Risk Prediction

---

# ✨ Features

- Dual Prediction System
- Diabetes Prediction
- High-Risk Pregnancy Prediction
- Dataset Integration using RIGHT JOIN
- Missing Value Handling
- Invalid Value Treatment
- StandardScaler
- Principal Component Analysis (PCA)
- SMOTE (Training Dataset Only)
- Random Forest & XGBoost Comparison
- Hyperparameter Tuning using RandomizedSearchCV

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-Learn, XGBoost |
| Visualization | Matplotlib, Seaborn |
| Development | Jupyter Notebook |

---

# ⚙️ Machine Learning Workflow

```text
Raw Healthcare Datasets
        │
        ▼
Dataset Integration
(RIGHT JOIN)
        │
        ▼
Data Cleaning
• Handle Missing Values
• Remove Invalid Values
• Remove Duplicate Records
        │
        ▼
Train-Test Split (80:20)
        │
        ▼
Feature Scaling
(StandardScaler)
        │
        ▼
Principal Component Analysis (PCA)
        │
        ▼
SMOTE
(Training Dataset Only)
        │
        ▼
Model Training
(Random Forest & XGBoost)
        │
        ▼
Hyperparameter Tuning
(RandomizedSearchCV)
        │
        ▼
Performance Evaluation
        │
        ▼
Final Health Risk Prediction
```

---

# 🤖 Machine Learning Models

The following supervised learning models were implemented and compared:

- Random Forest
- XGBoost

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

Based on the evaluation results, **XGBoost** was selected as the final model.

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Health-Risk-Prediction.git
```

Move into the project directory:

```bash
cd Health-Risk-Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

# 📈 Future Improvements

- Streamlit Web Application
- Explainable AI using SHAP
- Larger Clinical Dataset
- REST API for Real-Time Prediction
- Docker Containerization
- Cloud Deployment

---

# 👨‍💻 Author

**Arun Mahajan**

B.E. Computer Engineering

Thapar Institute of Engineering and Technology

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
