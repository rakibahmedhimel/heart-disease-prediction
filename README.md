# ❤️ Heart Disease Prediction

A machine learning project that predicts the presence of heart disease using a variety of patient features. Built using Logistic Regression and Random Forest with a focus on interpretability and performance.

---

## 📊 Dataset Features

| Feature         | Description                       |
|----------------|-----------------------------------|
| Age            | Age of the patient                |
| Sex            | Male or Female                    |
| ChestPainType  | Type of chest pain                |
| RestingBP      | Resting blood pressure            |
| Cholesterol    | Serum cholesterol (mg/dl)         |
| FastingBS      | Fasting blood sugar               |
| RestingECG     | Resting electrocardiographic results |
| MaxHR          | Maximum heart rate achieved       |
| ExerciseAngina | Exercise-induced angina (Y/N)     |
| Oldpeak        | ST depression                     |
| ST_Slope       | Slope of the peak exercise ST segment |
| HeartDisease   | Target variable (1 = disease)     |

---

## ⚙️ Model Building Steps

- ✔️ Data Cleaning
- ✔️ One-Hot Encoding for categorical features
- ✔️ Feature Scaling using StandardScaler
- ✔️ Train-Test Split
- ✔️ Logistic Regression
- ✔️ Random Forest Classifier
- ✔️ 5-Fold Cross-Validation
- ✔️ Model Evaluation: Accuracy, Precision, Recall, F1-score

---

## ✅ Results

| Model               | Accuracy | CV Score |
|--------------------|----------|----------|
| Logistic Regression| 85.3%    | 82.7%    |
| Random Forest       | 86.4%    |    -     |

> 📈 Random Forest performed slightly better and is saved as the final model.

---

## 🧠 Future Improvements

- Add GUI (Tkinter/Streamlit)
- Use GridSearchCV for hyperparameter tuning
- Add ROC-AUC curve analysis
- Deploy on web with Flask or Streamlit

---

## 🖼️ Sample Output Screenshot

![Heart Disease Prediction_GUI](Screeshots/gui1.png)
---

## 💻 Run Locally

```bash
# Install requirements
pip install pandas scikit-learn matplotlib seaborn

# Run the notebook
jupyter notebook heart_disease_model_improvement.ipynb
