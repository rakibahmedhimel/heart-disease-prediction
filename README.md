# 🫀 Heart Disease Prediction using Machine Learning

This project aims to predict whether a person is likely to have heart disease based on various medical parameters using a Logistic Regression model.

## 📁 Dataset
The dataset contains the following features:
- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (serum cholesterol)
- `fbs` (fasting blood sugar)
- `restecg` (resting electrocardiographic results)
- `thalach` (maximum heart rate achieved)
- `exang` (exercise-induced angina)
- `oldpeak` (ST depression)
- `slope` (slope of the peak exercise ST segment)
- `target` (0 = no heart disease, 1 = heart disease)

## 🧠 ML Model
- **Model Used:** Logistic Regression
- **Accuracy Achieved:** `~84.2%`
- **Encoding:** Manual mapping used for categorical features
- **Feature Scaling:** Not applied
- **Train/Test Split:** 80/20

## 🖥️ GUI
A simple GUI using Tkinter allows user to input values and get predictions.

<img src="gui1.PNG" width="500">

## 🧪 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rakibahmedhimel/heart-disease-prediction.git
   cd heart-disease-prediction
