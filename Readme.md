# Fraud Detection on Financial Transactions

This project presents a robust pipeline for detecting fraudulent transactions using machine learning techniques. It combines an unsupervised AutoEncoder model for anomaly detection with a supervised XGBoost classifier for high-accuracy fraud detection.

## 📁 Files and Structure

| File / Folder | Description |
|---------------|-------------|
| `fraud_detection_pipeline.ipynb` | Main notebook containing data preprocessing, AutoEncoder training, XGBoost classification, and analysis |
| `creditcard.csv` | Dataset of financial transactions (Kaggle source) |
| `results/` | Folder containing all model outputs, plots, SHAP visualizations, evaluation metrics, etc. |

## 🔍 Project Highlights

- **AutoEncoder** for unsupervised feature extraction and anomaly scoring
- **XGBoost** as a powerful classifier for final decision
- **SMOTE** to handle class imbalance
- **SHAP** analysis for model interpretability
- Precision-Recall, ROC, Confusion Matrix, KDE, Boxplots for evaluation

## 🧪 Requirements

Install the following dependencies:

pip install -r requirements.txt


## ✅ Usage

Run the notebook fraud_detection_pipeline.ipynb in Jupyter or VS Code to reproduce the full pipeline and analysis.

## 📊 Dataset

Source: Kaggle Credit Card Fraud Detection

## 📁 Output

All figures and saved models are stored in the results/ folder.

## 👨‍💻 Author
Developed by Sara-GRB

GitHub: @Sara-GRB