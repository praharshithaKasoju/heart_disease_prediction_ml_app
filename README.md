# Heart Disease Prediction ML App 🏥❤️

A **Heart Disease Prediction Web App** built using **Python**, **Streamlit**, and **Logistic Regression**.  
Users can input patient health information and get predictions about the risk of heart disease.

---

## Features

- Predict **High Risk** or **Low Risk** of heart disease.  
- Displays **prediction confidence (%)**.  
- Shows **probability breakdown** for each class (No Disease vs Disease).  
- Provides a **summary of patient inputs**.  
- Interactive and user-friendly **Streamlit interface**.

---

## Project Structure

heart_disease_prediction_ml_app/
├── app.py # Main Streamlit app
├── requirements.txt # Python libraries used
├── logistic_regression_model.pkl # Trained ML model
├── heart.csv # Dataset (used for feature info)
└── README.md # Project documentation



## Installation & Running Locally

1. **Clone the repository**:

```bash
git clone https://github.com/praharshithaKasoju/heart_disease_prediction_ml_app.git
cd heart_disease_prediction_ml_app
Install dependencies:


pip install -r requirements.txt
Run the Streamlit app:


streamlit run app.py
Open your browser and go to http://localhost:8501.

Requirements
text

streamlit
pandas
numpy
scikit-learn
joblib
(Save this as requirements.txt in your project folder.)

How It Works
Users enter demographic and health metrics in the sidebar.

Click Predict.

The app outputs:

Risk Level (High/Low)

Confidence (%)

Probability breakdown

Summary of patient inputs

The prediction is made using a pre-trained Logistic Regression model.

Notes
Make sure logistic_regression_model.pkl and heart.csv are in the same folder as app.py.

The app currently runs locally only.

Author
Praharshitha Kasoju

GitHub: praharshithaKasoju
