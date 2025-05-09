# Breast Cancer Detection Using Machine Learning

This repository presents a machine learning-based system for the **early detection and classification of breast cancer** using the **Breast Cancer Wisconsin Diagnostic (WBCD) dataset**. The project evaluates and compares multiple supervised learning algorithms to identify the most effective model for accurate diagnosis.

## 🔍 Overview

Breast cancer is one of the most common and life-threatening diseases affecting women worldwide. Early detection plays a vital role in increasing survival rates. This project uses classical machine learning algorithms to predict whether a tumor is benign or malignant based on input features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

## 📊 Dataset

- **Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** UCI Machine Learning Repository
- **Features:** 31 real-valued features computed from digitized images
- **Classes:** Benign, Malignant

## 🛠️ Technologies Used

- Python
- Anaconda
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

## 🧠 Models Implemented

- Support Vector Machine (SVM)
- Random Forest Classifier
- Decision Tree Classifier
- XGBoost Classifier

## 📈 Evaluation Metrics

- Confusion Matrix
- Accuracy
- Precision
- Sensitivity (Recall)
- F1 Score
- AUC (Area Under the Curve)

## 📋 Results

After training and evaluating the models, **Random Forest** showed the best performance with:

- **Accuracy:** 94.68%
- **Precision:** 98.58%
- **AUC:** 97.00%

## Future Scope
- Apply deep learning models like CNNs on image data

- Test with real-world clinical data

- Integrate with a web-based prediction interface

## 📜 License
This project is open-source and available under the MIT License.

