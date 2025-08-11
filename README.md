# Heart Disease Prediction Project

## Overview

This project uses machine learning techniques to predict whether a patient has heart disease based on medical features such as age, cholesterol level, blood pressure, and other relevant health indicators.

The project is implemented in Python using a Jupyter Notebook (`Heart_Disease_Prediction.ipynb`). It involves steps such as data preprocessing, feature selection, model training, and evaluation.

## Dataset

The dataset contains various medical attributes and a target variable indicating the presence or absence of heart disease. Some of the key features include:

* **age**: Patient's age in years.
* **sex**: Gender of the patient.
* **cp**: Chest pain type.
* **trestbps**: Resting blood pressure.
* **chol**: Serum cholesterol in mg/dl.
* **fbs**: Fasting blood sugar > 120 mg/dl.
* **restecg**: Resting electrocardiographic results.
* **thalach**: Maximum heart rate achieved.
* **exang**: Exercise induced angina.
* **oldpeak**: ST depression induced by exercise.
* **slope**: The slope of the peak exercise ST segment.
* **ca**: Number of major vessels colored by fluoroscopy.
* **thal**: Thalassemia type.
* **target**: 1 = disease present, 0 = disease not present.

## Project Workflow

1. **Data Loading**: Load the dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**: Inspect data, check for missing values, and visualize distributions.
3. **Data Preprocessing**:

   * Handle missing values.
   * Encode categorical variables (`cp`, `thal`, `restecg`).
   * Normalize or scale numerical features.
4. **Model Training**:

   * Train multiple models (e.g., Logistic Regression, Random Forest, SVM).
   * Use cross-validation for performance estimation.
5. **Model Evaluation**:

   * Compare accuracy, precision, recall, and F1-score.
   * Choose the best-performing model.
6. **Prediction**:

   * Use the trained model to predict heart disease presence on new patient data.

## Requirements

* Python 3.x
* Jupyter Notebook
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Install requirements:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone this repository.
2. Open `Heart-Disease-Prediction.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to reproduce the results.

## Results

The notebook contains visualizations and evaluation metrics showing model performance. Logistic Regression and Random Forest typically show high accuracy for this dataset.

## License

This project is licensed under the MIT License.
