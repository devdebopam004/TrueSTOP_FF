# TrueSTOP

AI Powered Fraud Detection System for Financial Transactions using Machine Learning and Streamlit.

TrueSTOP is a smart fraud detection web application that predicts whether a financial transaction is fraudulent or legitimate based on transaction details such as transaction type, amount, sender balance, and receiver balance.

---

# Features

- AI-powered fraud transaction prediction
- Real-time transaction analysis
- Interactive Streamlit web interface
- Machine Learning based detection system
- Fast and lightweight application
- Beginner-friendly project structure
- Easy deployment and customization
- Financial transaction risk analysis

---

# Tech Stack

- Python
- Streamlit
- Pandas
- Scikit-learn
- Joblib

---

# Project Structure

```bash
TrueSTOP/
│
├── fraud_detection.py           # Main Streamlit application
├── fraud_detection_model.pkl    # Trained machine learning model
├── analysis_model.ipynb         # Jupyter notebook for analysis/training
├── requirements.txt             # Required dependencies
└── README.md                    # Project documentation
```

---

# How It Works

The application takes transaction-related inputs such as:

- Transaction Type
- Transaction Amount
- Sender Old Balance
- Sender New Balance
- Receiver Old Balance
- Receiver New Balance

The system then:

1. Processes the input transaction data
2. Sends the data to the trained ML model
3. Predicts whether the transaction is:
   - Fraudulent
   - Legitimate

---

# Installation Guide

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/TrueSTOP.git
```

---

## 2. Move Into the Project Directory

```bash
cd TrueSTOP
```

---

## 3. Create Virtual Environment (Recommended)

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

# Install Dependencies

Create a `requirements.txt` file containing:

```txt
streamlit
pandas
scikit-learn
joblib
```

Then install all dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Application

Run the following command:

```bash
streamlit run fraud_detection.py
```

After running the command, Streamlit will automatically open the application in your browser.

---

# Model Information

The project uses a trained Machine Learning model saved using Joblib.

## Model File

```bash
fraud_detection_model.pkl
```

## Prediction Output

| Output | Meaning |
|---|---|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

---

# Input Parameters

| Parameter | Description |
|---|---|
| Transaction Type | Type of transaction |
| Amount | Transaction amount |
| Old Balance (Sender) | Sender balance before transaction |
| New Balance (Sender) | Sender balance after transaction |
| Old Balance (Receiver) | Receiver balance before transaction |
| New Balance (Receiver) | Receiver balance after transaction |

---

# Example Use Case

A user enters transaction details into the application.

The AI model analyzes the financial behavior pattern and predicts whether the transaction is potentially fraudulent.

This can help in:
- Banking systems
- Payment gateways
- Financial monitoring systems
- Fraud prevention systems

---

# Future Improvements

- User authentication system
- Transaction history database
- Dashboard analytics
- Real-time API integration
- Fraud probability percentage
- Dark mode UI
- Cloud deployment support
- Deep Learning integration

---

# Deployment Options

You can deploy this project easily on:

- Streamlit Community Cloud
- Render
- Railway
- Hugging Face Spaces
- AWS
- Azure
- Google Cloud Platform

---


# Contributing

Contributions are welcome.

Steps:

1. Fork the repository
2. Create a new branch
3. Make changes
4. Commit your changes
5. Push to your branch
6. Create a Pull Request

---

# Author

Debopam Ghosh

B.Tech CSE (Cyber Security)

Passionate about Artificial Intelligence, Cyber Security, and Full Stack Development.

---

# Support

If you found this project helpful, consider giving the repository a star.

---

# Repository Topics

```txt
Machine Learning
Fraud Detection
Financial Fraud Detection
Streamlit
Python
Cyber Security
AI Project
Transaction Monitoring
Scikit-learn
```

---

# Notes

- Ensure the trained model file is present before running the application.
- Keep all files in the root project directory.
- Works best with Python 3.10+.
- The application is designed for educational and demonstration purposes.

---

Built with Python, Streamlit, and Machine Learning for intelligent fraud detection.
