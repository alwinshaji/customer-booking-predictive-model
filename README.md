# ✈️ Customer Booking Prediction - Machine Learning Project

This project focuses on predicting whether a customer will complete a booking for a flight, based on historical booking behavior and preferences. The goal is to help airlines proactively identify potential bookers and improve conversion using machine learning.

---

## 📂 Project Structure

- `customer_booking.ipynb` – Full data processing, model training, evaluation, and visualization notebook
- `customer_booking.csv` – Cleaned dataset used for training
- `Customer_Booking_Model_Summary.pptx` – Business-facing presentation summarizing model performance and key findings

---

## 🧠 Problem Statement

> Airlines want to predict which customers are likely to complete their bookings. This helps with marketing, personalization, and resource allocation. The challenge is to identify meaningful signals from behavioral and travel-related features.

---

## 📊 Dataset Overview

The dataset contains 14 features including:
- Passenger behavior (e.g. wants_in_flight_meals, wants_extra_baggage)
- Travel details (e.g. route, purchase_lead, length_of_stay, flight_hour)
- Target column: `booking_complete` (0 = not booked, 1 = booked)

---

## 🛠️ Techniques Used

- Exploratory Data Analysis (EDA)
- Feature Encoding (`pd.get_dummies`)
- Random Forest Classifier
- Model Evaluation using Precision, Recall, F1-Score
- Feature Importance Visualization

---

## ✅ Model Results

| Metric     | Score     |
|------------|-----------|
| Accuracy   | 85%       |
| Precision  | 56% (bookers) |
| Recall     | 12% (bookers) |
| F1 Score   | 20%       |

⚠️ The model performs well in predicting non-bookers, but underpredicts actual bookers due to class imbalance.

---

## 💡 Key Insights

- Customers with longer purchase lead times and extra service preferences (baggage, meals) are more likely to complete bookings.
- `route`, `booking_origin`, and `flight_hour` also significantly impact booking likelihood.

---

## 🚀 Next Steps

- Address class imbalance using SMOTE or class weighting
- Try ensemble methods like Gradient Boosting or XGBoost
- Fine-tune hyperparameters to improve recall for actual bookers

---

## 📎 Related Files

- 📘 [`Customer_Booking_Model_Summary.pptx`](Customer_Booking_Model_Summary.pptx)
- 📒 [`Notebook`](Customer_booking.ipynb)

---

## 👤 Author

**Alwin Shaji**  
📍 [GitHub](https://github.com/alwinshaji) | 📸 [Instagram](https://instagram.com/alwinshaji) | 🔗 [LinkedIn](https://www.linkedin.com/in/alwinshaji)

---
