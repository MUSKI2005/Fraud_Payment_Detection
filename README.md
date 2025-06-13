# Fraud Payment Detection Web App

A machine learning-based web application to detect fraudulent transactions using user input. Built with **Flask** for the backend and a trained **scikit-learn model** for predictions.

---

## Features

- Predicts whether a payment is fraudulent or not.
- Built using a trained machine learning model (e.g., Logistic Regression, Random Forest).
- Clean and responsive web interface.
- Lightweight Flask backend.

---

## Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas & NumPy
- HTML/CSS (Bootstrap optional)
- Jupyter Notebook (for preprocessing & training)

---

<!-- Structure of the PROJECT -->
project/
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   └── styles.css        # CSS file here
│
├── app.py                # Flask backend
├── fraud_model.pkl
├── data_preprocessing.ipynb
├── model_training.ipynb
└── requirements.txt