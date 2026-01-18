# Heart Disease Risk Prediction with Explainable AI

## 📋 Deskripsi Proyek
Proyek ini mengembangkan model machine learning untuk memprediksi risiko penyakit jantung menggunakan **Explainable AI (XAI)** dengan library SHAP, sehingga prediksi tidak hanya akurat tetapi juga dapat dijelaskan kepada stakeholder medis.

## 🎯 Tujuan
- Membuat model klasifikasi dengan akurasi tinggi
- Implementasi SHAP untuk interpretability
- Mengidentifikasi faktor risiko utama penyakit jantung

## 📊 Dataset
- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- **Size**: ~300 instances
- **Features**: 14 (age, sex, chest pain type, cholesterol, dll)
- **Target**: Binary (0: No disease, 1: Disease)

## 🚀 Quick Start
```bash
# Clone repository
git clone 

# Install dependencies
pip install -r requirements.txt

# Run exploratory analysis
jupyter notebook notebooks/01_eda.ipynb
```

## 📁 Struktur Proyek
```
heart-disease-explainable-ai/
│
├── data/
│   ├── raw/                      # Dataset asli dari Kaggle (jangan diubah)
│   │   └── heart.csv
│   ├── processed/                # Data setelah preprocessing
│   │   ├── train.csv
│   │   ├── test.csv
│   │   └── val.csv
│   └── external/                 # Data tambahan (jika ada)
│
├── notebooks/
│   ├── 01_eda.ipynb             # Exploratory Data Analysis
│   ├── 02_preprocessing.ipynb    # Data cleaning & feature engineering
│   ├── 03_modeling.ipynb         # Model training & comparison
│   └── 04_explainability.ipynb   # SHAP analysis & visualization
│
├── src/
│   ├── __init__.py
│   ├── data/
│   │   ├── __init__.py
│   │   ├── load_data.py          # Fungsi load dataset
│   │   └── preprocess.py         # Fungsi preprocessing
│   │
│   ├── features/
│   │   ├── __init__.py
│   │   └── build_features.py     # Feature engineering
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   ├── train_model.py        # Training logic
│   │   ├── predict_model.py      # Prediction logic
│   │   └── evaluate_model.py     # Evaluation metrics
│   │
│   ├── visualization/
│   │   ├── __init__.py
│   │   └── visualize.py          # Plotting functions
│   │
│   └── explainability/
│       ├── __init__.py
│       └── shap_explainer.py     # SHAP implementation
│
├── models/                       # Saved models
│   ├── xgboost_model.pkl
│   ├── random_forest_model.pkl
│   └── logistic_regression_model.pkl
│
├── reports/
│   ├── figures/                  # Grafik hasil analisis
│   │   ├── correlation_matrix.png
│   │   ├── shap_summary.png
│   │   └── roc_curve.png
│   └── metrics/                  # Performance metrics
│       └── model_comparison.csv
│
├── app/                          # Streamlit dashboard (opsional)
│   ├── app.py
│   └── utils.py
│
├── tests/                        # Unit tests (best practice)
│   ├── test_data.py
│   └── test_models.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── config.yaml                   # Configuration file
```
## 🧪 Models Comparison
| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | - | - | - | - | - |
| Random Forest | - | - | - | - | - |
| XGBoost | - | - | - | - | - |

## 📈 Key Findings
[Akan diisi setelah analisis]

[//]: # (## 👥 Contributors )

[//]: # ([Your Name])# Hear-Disease-explainable
# Hear-Disease-explainable
