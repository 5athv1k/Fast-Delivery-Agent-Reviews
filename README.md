# 🚚 Fast Delivery Agent Reviews Analysis

> An exploratory data analysis and machine learning project focused on understanding customer ratings, delivery performance, service quality, product availability, and order accuracy across fast-delivery platforms.

## 📌 Project Overview

This project analyzes customer review and delivery-related data to identify patterns in ratings, delivery performance, customer service, product availability, and order accuracy.

The dataset contains **5,000 records and 12 features**, covering delivery agents/platforms, customer ratings, review text, delivery time, location, order type, feedback type, pricing, discounts, product availability, customer service ratings, and order accuracy.

## 🎯 Objectives

* Understand the structure and quality of the dataset
* Identify missing and duplicate values
* Analyze customer rating distributions
* Study the relationship between delivery time and customer ratings
* Compare performance across locations
* Analyze product availability
* Detect potential outliers
* Examine correlations between numerical variables
* Apply machine learning for predictive analysis

## 🗂️ Dataset Features

| Feature                 | Description                    |
| ----------------------- | ------------------------------ |
| Agent Name              | Delivery platform/agent        |
| Rating                  | Customer rating                |
| Review Text             | Customer review                |
| Delivery Time (min)     | Delivery duration              |
| Location                | Customer location              |
| Order Type              | Type of order                  |
| Customer Feedback Type  | Positive, Negative or Neutral  |
| Price Range             | Product price category         |
| Discount Applied        | Whether a discount was applied |
| Product Availability    | Stock availability             |
| Customer Service Rating | Customer service score         |
| Order Accuracy          | Whether the order was correct  |

## 🔎 Analysis Performed

### Data Cleaning

* Dataset inspection
* Data type verification
* Missing-value analysis
* Duplicate detection and removal
* Column-name cleaning
* Data preparation

### Exploratory Data Analysis

The project explores:

* Rating distribution
* Delivery time distribution
* Location-wise ratings
* Product availability
* Delivery time vs. rating
* Customer service performance
* Statistical summaries
* Outlier detection
* Correlation between numerical variables

### 📊 Visualizations

Key visualizations include:

* Rating distribution
* Location distribution
* Delivery Time vs. Rating
* Rating box plots
* Product availability analysis
* Location vs. Rating analysis
* Correlation heatmap
* Delivery-time outlier analysis

## 🤖 Machine Learning

A Linear Regression model was implemented using selected numerical variables and evaluated using:

* Mean Squared Error (MSE)
* R² Score

> **Note:** The current notebook contains an initial modelling implementation. The modelling section should be further refined to avoid target leakage and provide a more meaningful prediction task.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
fast-delivery-agent-reviews-analysis/
│
├── notebooks/
│   └── Fast_Delivery_Agent_Reviews_Analysis.ipynb
│
├── reports/
│   └── Fast_Delivery_Agent_Reviews_Report.pdf
│
├── images/
│   ├── rating-distribution.png
│   ├── delivery-vs-rating.png
│   ├── correlation-heatmap.png
│   └── location-analysis.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 💡 Key Skills Demonstrated

**Data Analysis:**
Data Cleaning • EDA • Statistical Analysis • Outlier Detection • Correlation Analysis

**Visualization:**
Matplotlib • Seaborn

**Machine Learning:**
Scikit-learn • Train/Test Split • Linear Regression • Model Evaluation

**Programming:**
Python • Pandas

## 🚀 Future Improvements

* Perform proper feature engineering
* Remove target leakage from the prediction pipeline
* Compare multiple machine learning models
* Add meaningful model evaluation
* Perform deeper sentiment analysis on review text
* Build an interactive dashboard using Power BI
* Deploy an interactive analytics application

## 👨‍💻 Author

**Sathvik B R**

BCA Student | Aspiring Data Analyst

---

⭐ If you found this project useful, consider giving the repository a star.
