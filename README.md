# Heart Disease Prediction ML App 🏥❤️

A Machine Learning web application that predicts heart disease risk using Logistic Regression with **89.27% accuracy** and **88.68% precision**.

Users can input patient health information and receive real-time predictions along with confidence score and probability breakdown.

---

## Features

- Predicts **High Risk** or **Low Risk** of heart disease  
- Displays prediction confidence (%)  
- Shows probability breakdown (No Disease vs Disease)  
- Provides a summary of patient inputs  
- Interactive and user-friendly Streamlit interface  

---

## Model Performance

- **Algorithm:** Logistic Regression  
- **Accuracy:** 89.27%  
- **Precision:** 88.68%  
- Evaluated using standard classification metrics on the test dataset  

---

## Project Structure

```
heart_disease_prediction_ml_app/
│
├── app.py                         # Main Streamlit application
├── logistic_regression_model.pkl  # Trained ML model
├── heart.csv                      # Dataset (used for feature reference)
├── requirements.txt               # Required Python libraries
└── README.md                      # Project documentation
```

---

## Installation & Running Locally

### 1️⃣ Clone the repository
```
git clone https://github.com/praharshithaKasoju/heart_disease_prediction_ml_app.git
cd heart_disease_prediction_ml_app
```

### 2️⃣ Install dependencies
```
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app
```
streamlit run app.py
```

Then open your browser and go to:

```
http://localhost:8501
```

---

## Requirements

- streamlit  
- pandas  
- numpy  
- scikit-learn  
- joblib  

---

## How It Works

1. Users enter demographic and health metrics in the app interface.  
2. Click **Predict**.  
3. The application outputs:
   - Risk Level (High / Low)  
   - Confidence Percentage  
   - Probability Breakdown  
   - Summary of patient inputs  

The prediction is generated using a pre-trained Logistic Regression model.

---

## Notes

- Ensure `logistic_regression_model.pkl` and `heart.csv` are in the same directory as `app.py`.
- The application currently runs locally.

---

## Author

**Praharshitha Kasoju**  
GitHub: https://github.com/praharshithaKasoju
