# 🩺 Breast Cancer Prediction using Machine Learning

A Machine Learning project that predicts whether a breast tumor is **Benign (B)** or **Malignant (M)** using the **Breast Cancer Wisconsin Dataset**. The project compares multiple machine learning algorithms and identifies the best-performing model based on evaluation metrics.

---

## 📌 Project Overview

Breast cancer is one of the leading causes of cancer-related deaths among women worldwide. Early detection can significantly improve treatment outcomes. This project applies supervised machine learning techniques to classify tumors using features computed from breast cell nuclei.

The following machine learning models were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

The Random Forest model achieved the highest accuracy and was selected as the final prediction model.

---

## 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

- Total Records: **569**
- Features: **30**
- Target Variable:
  - **M** → Malignant
  - **B** → Benign

The dataset contains numerical features extracted from digitized images of breast cell nuclei, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave Points
- Symmetry
- Fractal Dimension

Each feature is available as:

- Mean
- Standard Error
- Worst Value

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📁 Project Structure

```
Breast-Cancer-Prediction/
│
├── images/
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── diagnosis_count.png
│   ├── feature_imp.png
│   └── model_comp.png
│
├── breast-cancer.csv
├── Cancer_prediction.ipynb
├── cancer_prediction_model.pkl
├── requirements.txt
└── README.md
```

---

## 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Data Preprocessing
   │
   ▼
Train-Test Split
   │
   ▼
Feature Scaling
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Prediction
```

---

## 📊 Exploratory Data Analysis

### Diagnosis Distribution

![Diagnosis Count](images/diagnosis_count.png)

---

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

### Feature Importance (Random Forest)

![Feature Importance](images/feature_imp.png)

---

### Model Comparison

![Model Comparison](images/model_comp.png)

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## 🤖 Machine Learning Models

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline binary classification model |
| Decision Tree | Tree-based classification model |
| Random Forest | Ensemble model with multiple decision trees |

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

The Random Forest classifier achieved the best overall performance and was selected as the final model.

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction.git
```

### Move into the project directory

```bash
cd Breast-Cancer-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
Cancer_prediction.ipynb
```

Run all cells sequentially.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

---

## 🎯 Results

- Successfully classified breast tumors as Benign or Malignant.
- Compared three different machine learning algorithms.
- Random Forest achieved the highest accuracy.
- Saved the trained model using Joblib for future predictions.

---

## 🚀 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- ROC Curve and AUC Analysis
- Streamlit Web Application
- Flask API Deployment
- Cloud Deployment (Render / Railway / AWS)

---

## 👩‍💻 Author

**Nandhini R**

Machine Learning Project

---

## ⭐ If you found this project useful, don't forget to star the repository!
