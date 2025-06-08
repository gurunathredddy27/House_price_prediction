# 🏠 House Price Prediction Model (Flask Web App)

This project is a **Machine Learning Web Application** that predicts house prices based on user inputs. It uses both **Linear Regression** and **Random Forest Regression** models, and is deployed with **Flask** through a clean and simple web interface.

---

## Features

- Predict house prices using:
  -  Linear Regression
  -  Random Forest Regression
- Input fields:
  - Bedrooms
  - Bathrooms
  - Square Feet Living Area
  - Number of Floors
  - Year Built
  - City
  - Country
- Real-time predictions displayed on the web page
- One-hot encoding for categorical inputs (city, country)
- Clean and responsive UI with HTML/CSS

---

## Models Used

- `house.pkl` → Trained Linear Regression model
- `house_rf.pkl` → Trained Random Forest Regression model
- `features.pkl` → List of training features for one-hot encoding consistency

---