# Zomato Bangalore Restaurant Data Analysis

## 📌 Project Overview

This project focuses on cleaning and analyzing the Zomato Bangalore restaurant dataset using Python and Pandas. The objective was to preprocess messy real-world data and extract meaningful insights through exploratory data analysis (EDA) and visualizations.

---

## 📊 Dataset Information

The dataset contains information about restaurants in Bangalore, including:

* Restaurant names
* Ratings
* Votes
* Online ordering availability
* Restaurant types
* Cuisines
* Approximate cost for two people
* Location and category information

The dataset was accessed using the `kagglehub` library.

---

## 🛠️ Data Cleaning Performed

The raw dataset contained:

* Missing values
* Inconsistent rating formats
* Unnecessary columns
* Numeric values stored as strings

### Cleaning Steps:

* Removed irrelevant columns such as URLs, phone numbers, and review text
* Handled missing values
* Cleaned the `rate` column by:

  * Removing `/5`
  * Handling `NEW` and `-` values
  * Converting ratings into numerical format
* Cleaned the `approx_cost(for two people)` column by:

  * Removing commas
  * Converting values into numeric datatype
* Removed rows with important missing values

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

* Distribution of restaurant ratings
* Online ordering vs restaurant ratings
* Cost vs ratings relationship
* Top restaurant types in Bangalore

---

## 🔍 Key Insights

* Most restaurants are rated between **3.5 and 4.1**
* Restaurants offering online ordering tend to have slightly higher ratings
* Expensive restaurants are not necessarily rated significantly better
* Quick Bites and Casual Dining restaurants dominate the Bangalore restaurant market

---

## 🧰 Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* KaggleHub

---

## ▶️ How to Run

Install required libraries:

```bash
pip install pandas matplotlib seaborn notebook kagglehub
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```text
zomato-data-analysis/
│
├── zomato_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 📌 Conclusion

This project demonstrates practical data cleaning and exploratory data analysis on a real-world dataset. The workflow focused on transforming inconsistent raw data into meaningful business insights using Python-based data analysis tools.
