# Heart Disease Prediction Using Machine Learning

## Project Overview
This project uses Machine Learning to predict the likelihood of heart disease based on patient health-related features.

A Logistic Regression classification model is integrated with a Streamlit web application, allowing users to enter health information and receive a prediction through an interactive interface.

## Objectives
- Analyze and preprocess the heart disease dataset.
- Perform categorical encoding and numerical feature scaling.
- Train a Logistic Regression classification model.
- Evaluate model performance.
- Deploy the trained model using Streamlit.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib
- Jupyter Notebook

## Project Structure

```text
heart-disease-prediction/
│
├── heart.ipynb
├── heart_prediction.py
├── heart.csv
├── LOGREG_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└── README.md
```

## Machine Learning Workflow

1. Dataset loading and exploration
2. Data preprocessing
3. Categorical feature encoding
4. Numerical feature scaling using StandardScaler
5. Model training using Logistic Regression
6. Model evaluation
7. Integration with Streamlit

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/saniasharmaa003-debug/heart-disease-prediction.git
```

### 2. Navigate to the project folder

```bash
cd heart-disease-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run heart_prediction.py
```

## Application Features
- Interactive user input fields
- Health-related feature selection
- Machine Learning-based prediction
- User-friendly Streamlit interface

## Future Improvements
- Experiment with additional classification algorithms.
- Improve model performance through hyperparameter tuning.
- Add more model evaluation visualizations.
- Enhance the user interface.

## Disclaimer
This project is developed for educational purposes only. Its predictions are not a substitute for professional medical diagnosis or advice.
