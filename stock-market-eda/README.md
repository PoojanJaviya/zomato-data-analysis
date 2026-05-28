# Apple Stock Market Analysis & Prediction

## 📌 Project Overview

This project focuses on analyzing historical Apple stock market data and building a machine learning model to predict stock closing prices using financial indicators and time-series analysis techniques.

The project demonstrates:

* Time-series data analysis
* Financial data visualization
* Feature engineering
* Machine learning regression
* Predictive analytics

using real-world stock market data.

---

## 📊 Dataset Information

The dataset contains historical Apple stock data including:

* Opening Price
* Highest Price
* Lowest Price
* Closing Price
* Trading Volume
* Open Interest

The data spans multiple years of Apple stock market activity and is suitable for financial trend analysis and prediction.

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

* Converted the `Date` column into datetime format
* Set the date column as the dataframe index
* Generated moving averages
* Calculated daily returns
* Removed rows containing missing values introduced by rolling calculations

---

## ⚙️ Feature Engineering

Additional financial indicators were created to improve analysis and prediction performance:

* 30-Day Moving Average
* 100-Day Moving Average
* Daily Returns

These indicators help capture stock trends and market behavior over time.

---

## 📈 Exploratory Data Analysis

Visualizations were created to analyze:

* Historical stock price trends
* Moving averages
* Daily return distribution
* Market volatility

The analysis revealed strong long-term growth trends and recurring stock market fluctuations.

---

## 🤖 Machine Learning Model

A **Linear Regression** model was trained to predict future Apple stock closing prices using:

* Open Price
* High Price
* Low Price
* Trading Volume
* Moving Averages

A time-based train-test split was used to preserve chronological order during training and testing.

---

## 📊 Model Evaluation

The model was evaluated using standard regression metrics:

| Metric                         | Value    |
| ------------------------------ | -------- |
| Mean Absolute Error (MAE)      | Very Low |
| Root Mean Squared Error (RMSE) | Very Low |
| R² Score                       | ~0.99    |

The model demonstrated very strong predictive performance due to the strong relationship between stock market indicators and closing prices.

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure

```text
apple-stock-analysis/
│
├── stock_analysis.ipynb
├── apple_stock.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Conclusion

This project demonstrates how machine learning and time-series analysis techniques can be applied to financial market data for stock price prediction. The workflow combines data preprocessing, feature engineering, visualization, and regression modeling to analyze historical Apple stock behavior and generate predictive insights.
