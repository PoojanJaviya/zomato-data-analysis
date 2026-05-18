# Restaurant Cost Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on building a machine learning regression model to predict the approximate cost for two people at restaurants listed in the Zomato Bangalore dataset.

The project demonstrates a complete supervised machine learning workflow including:

* Data preprocessing
* Feature engineering
* Feature encoding
* Model training
* Model evaluation
* Prediction visualization

---

## 🎯 Objective

The primary objective of this project is to predict:

# 💰 Approximate Restaurant Cost for Two People

using restaurant-related features such as:

* Ratings
* Restaurant type
* Location
* Votes
* Online ordering availability
* Table booking availability

---

## 📊 Dataset Information

The dataset contains restaurant information from Bangalore restaurants listed on Zomato, including:

* Restaurant ratings
* Restaurant categories
* Location data
* Customer voting information
* Pricing information

The cleaned dataset generated during exploratory data analysis (EDA) was used for machine learning modeling.

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed before model training:

* Removed missing values
* Cleaned numerical columns
* Selected relevant features
* Removed unnecessary columns
* Encoded categorical variables using one-hot encoding

The `cuisines` column was excluded due to extremely high categorical complexity.

---

## ⚙️ Features Used

The following features were used for training:

* `online_order`
* `book_table`
* `votes`
* `location`
* `rest_type`
* `listed_in(type)`
* `listed_in(city)`
* `rate`

Target Variable:

* `approx_cost(for two people)`

---

## 🤖 Machine Learning Model

A **Linear Regression** model was trained to predict restaurant pricing.

Linear Regression was chosen because:

* It is suitable for regression problems
* It is simple and interpretable
* It provides a strong baseline model

---

## ✂️ Train-Test Split

The dataset was split into:

* 80% training data
* 20% testing data

This ensures proper evaluation on unseen data.

---

## 📈 Model Evaluation

The model was evaluated using standard regression metrics.

| Metric                         | Value    |
| ------------------------------ | -------- |
| Mean Absolute Error (MAE)      | 149.09   |
| Mean Squared Error (MSE)       | 48872.45 |
| Root Mean Squared Error (RMSE) | 221.07   |
| R² Score                       | 0.77     |

---

## 🔍 Key Insights

* The model achieved strong predictive performance with an **R² score of approximately 0.77**
* Restaurant ratings, location, and restaurant type significantly influence pricing
* Predictions were more accurate for low-to-mid priced restaurants
* Premium restaurants showed greater variability in prediction accuracy

---

## 📊 Visualization

The project includes:

* Actual vs Predicted Cost scatter plot
* Regression model performance analysis

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

```text id="p3md7s"

│
├── model.ipynb
├── cleaned_zomato.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install required libraries:

```bash id="e9szt0"
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash id="i2n2p8"
jupyter notebook
```

---

## 📌 Conclusion

This project successfully implemented a regression-based machine learning workflow for restaurant cost prediction using real-world restaurant data. The model demonstrated strong predictive capability and highlighted the relationship between restaurant features and pricing.
