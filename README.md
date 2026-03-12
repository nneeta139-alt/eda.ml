# Tip Prediction App

## 📌 Overview

The **Tip Prediction App** is a simple Machine Learning web application built using **Streamlit**.
It predicts the **expected tip amount** in a restaurant based on customer and bill information.

The application uses a **trained machine learning model (`tips_model.pkl`)** to make predictions.

---

## 🚀 Features

* Predict restaurant tip amount
* Simple and interactive web interface
* Built using **Streamlit**
* Real-time predictions using a trained ML model
* Easy to run locally

---

## 📂 Project Structure

```
Tip-Prediction-App
│
├── app.py              # Streamlit web application
├── tips_model.pkl      # Trained machine learning model
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🛠 Technologies Used

* **Python**
* **Streamlit**
* **Pandas**
* **Scikit-learn**
* **Pickle**

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/tip-prediction-app.git
cd tip-prediction-app
```

### 2️⃣ Install required libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit app using the following command:

```bash
streamlit run app.py
```

After running the command, the application will open in your **default web browser**.

---

## 📊 Input Features

The app takes the following inputs:

| Feature    | Description                      |
| ---------- | -------------------------------- |
| Total Bill | Total bill amount                |
| Size       | Number of people at the table    |
| Sex        | Gender of the customer           |
| Smoker     | Whether the customer is a smoker |
| Day        | Day of the visit                 |
| Time       | Lunch or Dinner                  |

---

## 📈 Output

The model predicts the **tip amount** based on the given inputs.

Example:

```
Predicted Tip: 3.45
```

---

## 📖 How It Works

1. User enters the required inputs.
2. The inputs are converted into a **data format suitable for the model**.
3. The trained model (`tips_model.pkl`) processes the input.
4. The model predicts the **tip amount**.

---

## 👩‍💻 Author : Neeta 

This project was created for **Machine Learning practice using Streamlit**.
