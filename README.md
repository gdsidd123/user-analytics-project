# 📊 User Analytics, Cohort & Retention Analysis with ML

## 🚀 Project Overview

This project focuses on analyzing user transaction data to uncover actionable insights around user behavior, retention, and revenue trends. It also includes a simple machine learning model to identify high-value users for better targeting and decision-making.

---

## 🎯 Objectives

* Analyze user transaction patterns
* Identify high-value user segments
* Perform cohort and retention analysis
* Track revenue trends over time
* Build a machine learning model to predict high-value users

---

## 📁 Dataset

The dataset consists of ~5000 transactions across ~500 users, including:

* `user_id`
* `transaction_id`
* `amount`
* `transaction_date`
* `category`
* `city`

---

## 🧠 Key Analysis Performed

### 1. 📊 Category Analysis

* Identified top-performing categories by revenue
* Analyzed average transaction value per category
* Measured transaction distribution across categories

---

### 2. 📈 Time Trend Analysis

* Analyzed daily and monthly revenue trends
* Calculated month-over-month (MoM) growth
* Identified patterns in user spending behavior

---

### 3. 👥 User Segmentation

* Segmented users into **High / Medium / Low value** based on total spend
* Enabled targeted marketing and personalization strategies

---

### 4. 🔥 Cohort Analysis

* Grouped users based on their first transaction month
* Tracked user activity across subsequent months

---

### 5. 🔁 Retention Analysis

* Calculated retention rates over time
* Built a retention matrix to visualize user engagement
* Identified drop-offs and returning user behavior

---

### 6. 🤖 Machine Learning Model

* Built a **Logistic Regression model** to classify high-value users
* Features used:

  * Total transactions
  * Average transaction value
* Evaluated using:

  * Accuracy
  * Precision
  * Recall

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📊 Key Insights

* Certain categories contribute disproportionately to revenue
* A small segment of users drives a large portion of total spend
* Retention drops after the first period but stabilizes for engaged users
* High transaction frequency and higher average spend are strong indicators of high-value users

---

## 💡 Business Impact

* Helps in identifying high-value users for targeted campaigns
* Enables better resource allocation and marketing optimization
* Provides insights into user retention and engagement trends

---

## 🚀 Future Improvements

* Add more features (recency, frequency, behavioral patterns)
* Try advanced models (Random Forest, XGBoost)
* Build an interactive dashboard (Power BI / Streamlit)

---

## 📌 Conclusion

This project demonstrates how data analysis and machine learning can be combined to drive actionable business insights, improve user targeting, and optimize overall performance.

---
