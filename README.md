# 🧠 Thyroid Disease Prediction

## 📘 Description

This project uses Machine Learning techniques to predict thyroid diseases based on patient clinical data. The workflow includes data preprocessing, feature engineering, model training, evaluation, and visualization. The objective is to support early diagnosis and assist healthcare professionals in decision-making.

---

## ✨ Features

* Load and preprocess thyroid disease dataset
* Handle missing values and data cleaning
* Feature encoding and scaling
* Train machine learning models
* Evaluate model performance
* Generate confusion matrix and classification reports
* Save trained model for future predictions

---

## 💡 Use Cases

### Early Diagnosis

Predict thyroid disorders at an early stage using patient health records.

### Risk Assessment

Estimate the probability of thyroid disease based on clinical parameters.

### Personalized Treatment

Support healthcare professionals in designing effective treatment plans.

### Monitoring and Management

Track patient conditions and improve disease management strategies.

---

## ✅ Benefits

* High prediction accuracy
* Faster diagnosis process
* Data-driven decision making
* Improved patient care
* Easy deployment and scalability

---

## 🧩 Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

### Dependencies

* Python 3.x
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## 📦 Project Components

| Component      | File                     | Description                  |
| -------------- | ------------------------ | ---------------------------- |
| Dataset        | thyroid-disease.data     | Patient clinical dataset     |
| Notebook       | thyroid_prediction.ipynb | Complete ML workflow         |
| Trained Model  | thyroid_model.pkl        | Saved machine learning model |
| Documentation  | README.md                | Project information          |
| Requirements   | requirements.txt         | Dependencies                 |
| Visualizations | images/                  | Confusion matrix and charts  |

---

## 🔄 Workflow

### 1. Data Loading

* Load thyroid-disease.data
* Inspect dataset
* Handle missing values

### 2. Data Preprocessing

* Encode categorical variables
* Scale numerical features
* Split into training and testing sets

### 3. Model Training

Model Used:

* HistGradientBoostingClassifier
* CatBoostClassifier (optional comparison)

### 4. Evaluation

Performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 5. Model Saving

```python
import joblib
joblib.dump(model, "thyroid_model.pkl")
```

---

## 📊 Dataset Information

**Source:** UCI Machine Learning Repository

Features may include:

* Age
* Sex
* TSH
* T3
* TT4
* T4U
* FTI
* Other thyroid-related indicators

Target:

* Thyroid Disease Classification

---

## 🤖 Model Information

### HistGradientBoostingClassifier

A gradient boosting algorithm optimized for large datasets and missing values.

Advantages:

* High accuracy
* Fast training
* Handles complex patterns effectively

---

## 📈 Performance Metrics

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 95-98% |
| Precision | High   |
| Recall    | High   |
| F1-Score  | High   |

*Results may vary depending on train-test split and preprocessing.*

---

## 🖼️ Visualization

### Confusion Matrix Heatmap

The confusion matrix helps visualize the classification performance by comparing actual and predicted classes.

Example:

![Confusion Matrix](images/confusion_matrix.png)

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/Thyroid-Disease-Prediction.git
```

Navigate to project folder:

```bash
cd Thyroid-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
thyroid_prediction.ipynb
```

---

## 👨‍💻 Author

Parigi Anya Reddy

Machine Learning Project for Thyroid Disease Prediction.

---

## 📜 License

This project is licensed under the MIT License.

