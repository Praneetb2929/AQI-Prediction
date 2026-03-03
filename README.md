# 🌍 Intelligent AQI Prediction & Analytics System

A Machine Learning based web application that predicts Air Quality Index (AQI) using pollutant concentrations and provides interactive data analytics dashboard.

---

## 🚀 Project Overview

This project uses Regression models to predict AQI based on air pollutant levels such as:

- PM2.5
- PM10
- NO
- NO2
- NOx
- NH3

It also includes:

✔ AQI category classification  
✔ Health advisory recommendations  
✔ Dataset visualization dashboard  
✔ Correlation heatmap  
✔ Distribution analysis  

---

## 📊 Dataset Used

Dataset: `city_day.csv`

Features include:

- City
- Date
- PM2.5
- PM10
- NO
- NO2
- NOx
- NH3
- CO
- SO2
- O3
- Benzene
- Toluene
- Xylene
- AQI
- AQI_Bucket

---

## 🧠 Machine Learning Models Used

### 1️⃣ Linear Regression
Baseline regression model for AQI prediction.

### 2️⃣ Ridge Regression
Used to handle multicollinearity between pollutants.

---

## 📈 Model Evaluation Metrics

- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

Example performance:

R² Score ≈ 0.90
MAE ≈ 19
RMSE ≈ 28


---

## 🖥️ Web Application (Streamlit)

The app includes:

### 🔮 AQI Prediction Page
- Enter pollutant values
- Predict AQI
- Get AQI category
- Get health advice

### 📊 Data Dashboard
- AQI distribution histogram
- PM2.5 distribution
- Correlation heatmap
- Pollution analytics

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit

---

## ▶️ How To Run Locally

### 1️⃣ Clone the repository


### 2️⃣ Install dependencies



### 3️⃣ Run the application



---

## 🌡 AQI Category Classification

| AQI Range | Category |
|-----------|----------|
| 0–50 | Good |
| 51–100 | Satisfactory |
| 101–200 | Moderate |
| 201–300 | Poor |
| 301–400 | Very Poor |
| 401+ | Severe |

---

## 📌 Key Insights

- PM2.5 has strong influence on AQI.
- AQI distribution is positively skewed.
- Ridge regression helps reduce coefficient instability caused by multicollinearity.
- Pollution levels show seasonal and regional variations.

---

## 🔥 Future Improvements

- Add time-series forecasting
- Add city-wise comparison dashboard
- Deploy to Streamlit Cloud
- Add AQI category classifier model
- Add real-time API integration

---

## 👨‍💻 Author

Praneet Biswal  
B.Tech – 2027  
Machine Learning | Data Engineering | DevOps   

---

## ⭐ If you like this project, give it a star!
