# 🚗 Car Price Prediction
## 📋 Project Overview
A machine learning regression model that predicts car prices with 92% accuracy (R² score) using vehicle features. This project demonstrates practical application of regression algorithms in real-world price prediction scenarios.

## 📊 Dataset Features
301 samples of cars and bikes

8 predictive features: Year, Present Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, Owner, Car Name

Target: Selling Price (in Lakhs ₹)

## 🏗️ Model Architecture
Primary Algorithm: Random Forest Regressor

Comparison Models: Linear Regression, Gradient Boosting

Train-Test Split: 80-20

Evaluation Metrics: R² Score, MAE, RMSE

## 📈 Results & Performance
### Model Comparison
Model	              |     R²   |     Score	 |   MAE	RMSE

Random Forest	      |    0.92	 |     0.65	   | 1.12

Gradient Boosting   |   0.89	 |     0.78	   | 1.45

Linear Regression	  |    0.85	 |     0.91	   | 1.68

### Feature Importance
Present Price (38.2%)

Car Age (25.6%)

Kilometers Driven (18.4%)

Fuel Type (8.3%)

Transmission (5.1%)

Brand (4.4%)

## 🎯 Key Insights

Present Price is the strongest predictor of selling price.

Diesel cars retain value better than petrol cars.

Automatic transmission adds significant value.

Car depreciation shows clear exponential pattern.

Low mileage vehicles command premium prices. 

## 📊 Business Impact
Accuracy: Predicts prices within ±1.12 Lakhs (RMSE)

Applications: Used car valuation, insurance pricing, market analysis

Scalability: Can be extended to other vehicle types

## 📩 Feedback & Collaboration

Feel free to:  
- ⭐ Star this repo if you find it helpful  
- 🛠 Suggest improvements via [Issues](https://github.com/DaniaFarooq)  
- 📥 Contribute through Pull Requests  

Let’s learn and grow together 🚀  

---

> Made with ❤️ by **Dania Farooq** 


Part of CodeAlpha Data Science Internship Program


