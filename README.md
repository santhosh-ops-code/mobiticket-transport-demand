# 🚍 Nairobi Transport Demand Prediction – Mobiticket

## 🎯 Objective

This project aims to build a machine learning model to predict the number of seats sold for Mobiticket intercity bus rides from various towns in Western Kenya to Nairobi. By analyzing historical ticket booking data, the model helps forecast transport demand, which can optimize scheduling and operations.


## 📁 Project Structure

📁 Mobiticket_Transport_Demand_Project_May2025
├── Transport_Demand_Prediction.ipynb # EDA + model building (Colab-ready)
├── train_revised.csv # Cleaned training data
├── mobiticket_predicted_seats.csv # Model predictions
└── README.md # Project overview

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Google Colab

## 📊 Machine Learning Models

The following regression models were built and evaluated:

- ✅ Linear Regression
- ✅ Random Forest Regressor
- ✅ XGBoost Regressor

The models were compared based on:
- **R² Score**
- **RMSE (Root Mean Squared Error)**

## 📈 Features Used

Key features engineered for the model include:

- Travel date and time components (day of week, month)
- Travel origin (`travel_from`)
- Car type (`car_type`)
- Time slot (morning, afternoon, evening)
- Max capacity per ride

## 📦 Output

The final model (`XGBoost`) was used to generate predictions for ride-level seat demand. Results are saved in:
mobiticket_predicted_seats.csv

## 👤 Author

**Santhosh**  
Capstone Project – May 2025 Batch  
🔗 [GitHub Profile](https://github.com/santhosh-ops-code)
⭐ *If you like this project, feel free to fork or star the repository!*
