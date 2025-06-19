
# ❤️ Heart Disease Prediction with Machine Learning

This project builds a machine learning model to predict the likelihood of heart disease in patients based on various health parameters. It aims to support early detection using clinical data and supervised learning techniques.

## 📁 Dataset Overview

The dataset is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease) and includes 14 medical attributes that are known risk factors for heart disease.

### Key Features

| Feature              | Description                                                  |
|----------------------|--------------------------------------------------------------|
| `age`                | Age of the patient                                           |
| `sex`                | Gender (1 = male, 0 = female)                                |
| `cp`                 | Chest pain type (0–3)                                        |
| `trestbps`           | Resting blood pressure                                       |
| `chol`               | Serum cholesterol in mg/dl                                   |
| `fbs`                | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)        |
| `restecg`            | Resting ECG results                                          |
| `thalach`            | Maximum heart rate achieved                                  |
| `exang`              | Exercise-induced angina (1 = yes; 0 = no)                    |
| `oldpeak`            | ST depression induced by exercise                            |
| `slope`              | Slope of the peak exercise ST segment                        |
| `ca`                 | Number of major vessels colored by fluoroscopy (0–3)         |
| `thal`               | Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible)   |
| `target`             | Diagnosis of heart disease (1 = present, 0 = absent)         |

## 🎯 Objective

To develop a classification model that predicts the presence of heart disease based on patient health indicators.

## 🧪 Project Workflow

1. **Data Loading**: Imported the dataset using `pandas` and explored data shape, types, and structure.
2. **Data Cleaning**: Handled missing values, encoded categorical features, and normalized values where needed.
3. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions of features
   - Correlation heatmaps to identify feature importance
   - Pair plots and histograms
4. **Model Building**:
   - Trained multiple classifiers:
     - Logistic Regression
     - K-Nearest Neighbors
     - Random Forest
     - Support Vector Machine
   - Used train-test split and cross-validation
5. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1-score, Confusion Matrix
   - ROC-AUC curves

## 📈 Results

- Achieved up to **90%+ accuracy** with the best-performing model.
- Random Forest and SVM yielded the highest scores in terms of both precision and recall.
- ROC-AUC curve analysis showed good model generalization.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)

## ⚙️ How to Run

1. Clone the repository or download the `.ipynb` notebook.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
