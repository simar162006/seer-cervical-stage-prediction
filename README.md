# seer-cervical-stage-prediction
This project builds an XGBoost-based clinical decision support model that automatically predicts cervical cancer stage (Stage 1–4) using SEER epidemiological and diagnostic features.
# Cervical Cancer Stage Prediction Model (SEER Dataset)

## 📌 Overview
This project builds an XGBoost-based clinical decision support model that automatically predicts cervical cancer stage (Stage 1–4) using SEER epidemiological and diagnostic features.

## 🎯 Research Objective
To evaluate whether machine learning can reliably reproduce clinical staging using tumour extension, lymph-node involvement and metastasis patterns across multiple diagnosis years.

## 🧠 Methodology
- Data preprocessing: imputation, encoding, scaling
- Models trained: Random Forest, XGBoost
- Final pipeline: XGBoost + sklearn pipeline
- Evaluation: Accuracy, Precision, Recall, F1, Confusion Matrix, Temporal testing (2018–2022)

## 📂 Dataset
The SEER cervical cancer dataset was used.
Dataset is **not uploaded due to licensing policy**, but download instructions are provided.

## 🔬 Results
| Metric | Score |
|--------|-------|
| Accuracy | 100% |
| Precision | 100% |
| Recall | 100% |
| F1-Score | 100% |

Model performance remained consistent across 2018–2022 with **no performance drift**, demonstrating strong temporal generalization.

## 🚀 Running the model
