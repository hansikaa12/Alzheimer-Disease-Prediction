# 🧠 Alzheimer Disease Prediction

## 📌 Problem Statement

Alzheimer's disease is a chronic neurodegenerative disorder that progressively destroys memory and cognitive skills. Early diagnosis is crucial to slow progression and improve patient quality of life. However, due to subtle onset, it often goes undetected until significant cognitive decline has occurred. The aim of this project is to build a predictive model to accurately detect Alzheimer's disease using patient medical and imaging data.

---

## 🎯 Objectives

- To perform Exploratory Data Analysis (EDA) on the Alzheimer's dataset to uncover key insights.
- To preprocess the dataset, handle missing values, and encode categorical variables.
- To build and evaluate various machine learning models for classifying the presence of Alzheimer’s disease.
- To determine the best-performing model based on accuracy and other evaluation metrics.

---

## 🎯 Aim

To develop a reliable machine learning model that can predict the diagnosis of Alzheimer's disease based on features derived from clinical data and MRI measurements.

---

## 📚 Dataset Description

The dataset used contains medical features such as:

- MRI metrics (e.g., `eTIV`, `nWBV`, `ASF`)
- Clinical and demographic information (e.g., `Age`, `Sex`, `Education`, `SES`)
- Target Variable: `Group` (Converted vs Non-Converted)

---

## 🧪 Exploratory Data Analysis (EDA)

- Checked data types, null values, and unique values
- Visualized distribution of variables using histograms and boxplots
- Analyzed correlation between features
- Used pairplots and heatmaps to understand relationships

---

## 🧼 Data Preprocessing

- Handled missing values using mean/mode imputation
- Label encoded categorical variables (`Group`, `M/F`)
- Normalized numerical features for model input

---

## 🤖 Machine Learning Models Used

The following classification models were implemented and compared:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Random Forest Classifier**

---

## ✅ Model Evaluation

Metrics used:

- **Accuracy**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 86%      |
| KNN                 | 83%      |
| SVM                 | 88%      |
| Decision Tree       | 84%      |
| Random Forest       | **91%**  ✅ |

🏆 **Best Model**: **Random Forest Classifier** with **91% Accuracy**

---

## 📈 Visualizations

- Confusion matrices for each model
- ROC curves for model comparison
- Feature importance plot for Random Forest

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn (sklearn)

---

## 📁 Project Structure

