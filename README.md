
# Explainable Machine Learning Framework for Android Malware Detection

## 📌 Project Overview
This project addresses the growing threat of Android malware by developing an **explainable machine learning framework** that combines high-performance detection with model transparency. Using the **CICMalDroid 2020** dataset, the system leverages dynamic analysis, multiple classification algorithms, and interpretability tools (SHAP and LIME) to provide actionable insights into malware behavior.

## 📂 Dataset
- **Source**: CICMalDroid 2020
- **Type**: Dynamic analysis logs
- **Classes**: Multiple malware families and benign samples
- **Preprocessing**:
  - Label encoding
  - Feature normalization
  - Malware category distribution analysis

## ⚙️ Models Used
- [x] XGBoost
- [x] Random Forest
- [x] Naive Bayes
- [x] Logistic Regression
- [x] Support Vector Machine (SVM)
- [x] k-Nearest Neighbors (KNN)
- [x] LightGBM

## 🧠 Explainability
To ensure model transparency and trust, the framework integrates:
- **SHAP (SHapley Additive exPlanations)**
- **LIME (Local Interpretable Model-Agnostic Explanations)**

These tools highlight the most influential features driving each prediction.

## 📊 Evaluation Metrics

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| XGBoost           | 0.938    | 0.939     | 0.938  | 0.938    |
| Random Forest     | 0.934    | 0.934     | 0.934  | 0.933    |
| Naive Bayes       | 0.489    | 0.514     | 0.489  | 0.431    |
| Logistic Regression | 0.749  | 0.757     | 0.749  | 0.740    |
| SVM               | 0.800    | 0.810     | 0.800  | 0.797    |
| KNN               | 0.869    | 0.869     | 0.869  | 0.868    |
| LightGBM          | 0.935    | 0.935     | 0.935  | 0.935    |

## 🔍 Heatmap & Visualizations
The project includes a correlation heatmap and visual interpretation of model decisions using SHAP and LIME to assist in malware analysis.

## ✅ Key Contributions
- High detection performance with multiple classifiers
- Integration of XAI (Explainable AI) tools
- Insight into feature importance and behavior trends
- Discussion on temporal bias and mitigation strategies

## 📁 Files
- `model.ipynb`: Full Jupyter notebook with training, evaluation, and explainability
- `README.md`: Project summary and documentation

## 📜 License
This project is for academic and research purposes only.
