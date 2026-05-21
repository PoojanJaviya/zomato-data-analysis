# Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This project focuses on performing exploratory data analysis (EDA) on the Zomato Bangalore restaurant dataset to uncover meaningful patterns, relationships, and business insights.

The project demonstrates practical applications of:

* Data preprocessing
* Statistical analysis
* Data visualization
* Correlation analysis
* Insight generation

using Python-based data analysis tools.

---

# 📊 Dataset Information

The dataset contains restaurant-related information from Bangalore restaurants listed on Zomato, including:

* Restaurant ratings
* Customer votes
* Restaurant types
* Locations
* Cuisine categories
* Online ordering availability
* Approximate restaurant cost

The dataset was accessed using the `kagglehub` library.

---

# 🛠️ Data Cleaning

Several preprocessing steps were performed before analysis:

* Removed unnecessary columns
* Handled missing values
* Cleaned inconsistent rating formats
* Converted ratings into numerical format
* Converted pricing information into integer datatype
* Removed incomplete rows for accurate analysis

---

# 📈 Exploratory Data Analysis

The following analyses and visualizations were performed:

* Restaurant rating distribution
* Online ordering vs restaurant ratings
* Cost vs restaurant ratings
* Top restaurant types
* Statistical summaries
* Correlation heatmap analysis

---

# 🔍 Key Insights

* Most restaurants are rated between **3.5 and 4.1**
* Online ordering restaurants tend to have slightly higher ratings
* Restaurant cost shows only a moderate relationship with ratings
* Quick Bites and Casual Dining dominate the Bangalore restaurant market
* Higher customer votes are generally associated with better restaurant ratings

---

# 📊 Correlation Analysis

Correlation analysis was performed on numerical features to identify relationships between restaurant ratings, votes, and pricing.

The analysis revealed:

* Positive correlation between ratings and customer votes
* Moderate relationship between pricing and ratings
* No extremely strong linear relationships among features

---

# 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* KaggleHub

---

# 📁 Project Structure

```text id="jlwm7f"
eda-project/
│
├── task3_eda_report.ipynb
├── cleaned_zomato.csv
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

Install required libraries:

```bash id="jlwm3f"
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash id="jlwm0f"
jupyter notebook
```

---

# 📌 Conclusion

This project demonstrates how exploratory data analysis can be used to understand customer behavior, restaurant trends, and pricing patterns using real-world restaurant data. The workflow highlights the importance of preprocessing, visualization, and analytical thinking in extracting valuable business insights from data.
