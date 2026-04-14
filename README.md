#  Apple Stock Price Prediction & Analysis Dashboard

##  Overview

This project is an end-to-end **Stock Market Analysis & Prediction System** for Apple stock.
It includes:

* Data Cleaning & Feature Engineering
* Machine Learning Models
* Interactive Dashboard using Plotly
* Insights & Visualization

---

##  Models Used

We implemented multiple machine learning models:

### 1. Linear Regression

* Simple and fast model
* Works well with linear relationships
*  **Best performance in this project**

**Performance:**

* MAE: 1.31
* RMSE: 1.93
* R² Score: 0.9988 ⭐

---

### 2. Random Forest Regressor

* Ensemble model (multiple decision trees)
* Captures non-linear patterns

**Performance:**

* MAE: 1.46
* RMSE: 2.17

---

### 3. XGBoost Regressor

* Advanced boosting algorithm
* Usually powerful for structured data

**Performance:**

* MAE: 1.63
* RMSE: 2.47

---

### 4. Support Vector Regressor (SVR)

* Works well with scaled data
*  Poor performance in this case

**Performance:**

* MAE: 4.22
* RMSE: 12.33

---

##  Best Model

 **Linear Regression performed the best** with highest R² score and lowest error.

---

## 📊 Features Used

* Close Price
* Lag Features (Close_lag1, Close_lag2)
* Moving Averages (MA10, MA20, MA50)
* Volume
* Returns & Volatility

---

## 📈 Visualizations (7 Charts)

### 1. 📉 Stock Price Trend

* Shows price movement over time
* Helps identify long-term trends



---

### 2. 📊 Moving Averages

* Compare Close, MA10, MA20
* Helps identify trend direction



---

### 3. 📈 Actual vs Predicted

* Compares model predictions with real values
* Closer lines = better model



---

### 4. 📉 Error Distribution

* Shows prediction errors
* Center near zero = good model


---

### 5. 📊 Feature Importance (Random Forest)

* Shows important features


---

### 6. 📊 Feature Importance (XGBoost)

* Feature contribution in XGB model


---

### 7. 🔥 Correlation Matrix

* Shows relationships between features



---

##  Dashboard

* Built using Plotly + HTML
* Interactive charts
* Styled UI with Apple theme

---

##  Project Structure

```
├── HistoricalQuotes.csv
├── notebook.ipynb
├── dashboard/
│   ├── index.html
│   └── charts...
├── screenshots/
└── README.md
```

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Plotly

---

##  How to Run

```
pip install -r requirements.txt
python your_script.py
```

---

##  Author

Shubham Thakur
Here you can check the dashboard
 https://shubh229177.github.io/Apple_Stock_Prediction/

