# 🚗 Car Price Prediction using Machine Learning

This project predicts **car prices** based on various features using multiple regression models. It includes **feature engineering**, **model evaluation**, and demonstrates how additional features can improve model accuracy.

## 📌 Key Features

- Predicts car prices using specs like engine type, body style, and dimensions
- Introduced a new feature: `car_volume = length × width × height`
- Boosted model performance, especially for:
  - **Random Forest Regressor**
  - **Artificial Neural Network (ANN)**

## 📈 Performance Boost

After adding `car_volume`, R² score increased for both:
- **ANN**
- **Random Forest**

This shows the value of combining basic features into more insightful metrics.

## 📊 Models Used

- Linear Regression
- Random Forest Regressor 🌲
- XGBoost
- ANN (MLPRegressor)

## ⚙️ Tools

- Python, Pandas, NumPy
- Scikit-learn
- Seaborn & Matplotlib

## 🚀 Run the Project

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
pip install -r requirements.txt
jupyter notebook
