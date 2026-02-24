# Food Expiry Detection System

A machine learning-based project to predict the expiry dates of fruits and other food items, helping reduce food wastage and alert users before items go bad.

---

## 📝 Project Overview
This system predicts the shelf life of food items using regression models trained on historical expiry data. Users can monitor food freshness, track expiry dates, and optionally receive real-time notifications through Twilio when items are about to expire.

---

## ⚡ Features
- Predicts expiry dates for apples, oranges, and other food items.  
- Uses regression models trained on collected datasets.  
- Optional notification system using Twilio to alert users before items expire.  
- Easy-to-run Jupyter Notebook interface for predictions.  
- Helps reduce food wastage and track leaf/fruit health.

---

## 📂 Dataset
- `expiry_dates.csv`: Historical expiry data of fruits.  
- Images of fruits included for reference (`apple.png`, `orange.png`).  

---

## 🧠 Model
- `fruit_expiry_regression_model.h5`: Pre-trained regression model for predicting food expiry.  
- Uses features like fruit type, storage conditions, and observed freshness.

---

## 🔑 Twilio Integration
- Optional notifications for items nearing expiry.  
- **Credentials must be stored safely in a `.env` file** and loaded in Python using `python-dotenv`.  
- Do **not commit any secrets** to GitHub.  

---

## 🏆 Outcome
- Predict food expiry to reduce wastage.  
- Monitor leaf and fruit health.  
- Receive optional alerts via Twilio safely without exposing credentials.  
- Learn practical machine learning applications with real-world datasets.