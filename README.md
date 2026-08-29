# 🚗 Car Price Prediction System

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://used-car-prediction-07.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> An end-to-end Machine Learning web application that predicts the **selling price of used cars** based on key attributes such as manufacturing year, mileage, fuel type, transmission, seller type, and ownership history.

🔗 **Live Demo:** [https://used-car-prediction-07.streamlit.app/](https://used-car-prediction-07.streamlit.app/)

---

## 🌐 Live Web Application

Try the deployed web app directly in your browser:
👉 **[Launch Live Demo](https://used-car-prediction-07.streamlit.app/)** 🚀

---

## 📌 Project Overview

This project provides buyers and sellers with an accurate, data-driven estimate of the **fair resale value of a car** using historical market data and regression-based machine learning models. The trained model is deployed as an **interactive Streamlit web app** featuring real-time price estimation, depreciation analysis, and intuitive visual insights.

---

## 🧠 Machine Learning Details

- **Problem Type:** Regression
- **Target Variable:** Car Selling Price (in Lakhs INR)
- **Model Used:** Random Forest / Regression ML Model
- **Evaluation Metrics:**
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - $R^2$ Score

---

## 📊 Features Used

- **Manufacturing Year:** Year the vehicle was manufactured
- **Present Ex-Showroom Price:** Original showroom price (in Lakhs)
- **Kilometers Driven:** Total distance driven
- **Fuel Type:** Petrol / Diesel / CNG
- **Seller Type:** Dealer / Individual
- **Transmission:** Manual / Automatic
- **Number of Previous Owners:** 0, 1, 2+

---

## 🖥️ Streamlit Web App Features

- 🎛️ **Interactive Sidebar Inputs:** Adjust mileage, year, price, fuel, and transmission dynamically.
- ⚡ **Real-time Price Prediction:** Instant estimated resale value calculation.
- 📉 **Depreciation & Valuation Insights:** Visual insights into car depreciation over time.
- 📊 **Interactive Gauge Charts:** Visual representation of market value using Plotly.
- 📱 **Clean & Responsive UI:** Optimized layout with custom styling.

---

## 🗂️ Project Structure

```text
├── .devcontainer/               # Dev container configuration
├── app.py                       # Streamlit web application
├── car-price-prediction.ipynb   # Exploratory Data Analysis & Model Training
├── car_data.csv                 # Raw dataset
├── car_prediction_model.pkl     # Serialized trained ML model pipeline
├── requirements.txt             # Python dependencies
├── runtime.txt                  # Python runtime version
└── README.md                    # Project documentation
```

---

## ⚙️ Installation & Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/chirag-gupta-07/Used_Car_Price_Prediction_Model.git
cd Used_Car_Price_Prediction_Model
```

### 2. Create and activate a virtual environment (optional but recommended)
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application
```bash
streamlit run app.py
```

Open your browser at `http://localhost:8501`.

---

## 🚀 Cloud Deployment

### Deploying to Streamlit Community Cloud:
1. Push all code to your GitHub repository: `chirag-gupta-07/Used_Car_Price_Prediction_Model`.
2. Visit [share.streamlit.io](https://share.streamlit.io/) and log in with GitHub.
3. Click **"New app"**.
4. Select your repository: `chirag-gupta-07/Used_Car_Price_Prediction_Model`, branch: `main` (or `master`), and main file path: `app.py`.
5. Click **"Deploy"**!

---

## 👨‍💻 Author

**Chirag Gupta**
- **GitHub:** [@chirag-gupta-07](https://github.com/chirag-gupta-07)
- **LinkedIn:** [Chirag Gupta](https://linkedin.com) *(Update with your LinkedIn link)*

---

⭐ If you find this project useful, please consider giving it a star on GitHub!

