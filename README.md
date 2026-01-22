# Customer Shopping Behavior Analysis

An end-to-end data analytics project that analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI to uncover actionable business insights and support data-driven decision-making.

---

## 📌 Project Overview

This project explores customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The analysis focuses on understanding customer demographics, spending patterns, discount usage, subscription behavior, and product performance. The goal is to transform raw data into meaningful insights that can help businesses optimize marketing strategies, improve customer retention, and increase revenue. :contentReference

---

## 🎯 Project Objectives

- Analyze customer demographics and purchasing trends  
- Identify high-value customers and loyal segments  
- Understand the impact of discounts and subscriptions on revenue  
- Evaluate product performance and customer preferences  
- Present insights through an interactive Power BI dashboard  

---

## 📊 Dataset Overview

- **Total Records:** 3,900  
- **Total Features:** 18  

### Key Data Includes:
- Customer demographics: age, gender, location, subscription status  
- Purchase details: item purchased, category, season, size, color, purchase amount  
- Shopping behavior: discounts applied, purchase frequency, shipping type, review ratings  

### Data Quality:
- Missing values: 37 entries in the *Review Rating* column  
- Missing values were handled using category-wise median imputation 

---

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, NumPy)
- **PostgreSQL**
- **SQL**
- **Power BI**
- **SQLAlchemy**

---

## 🧹 Data Cleaning & Feature Engineering (Python)

The following steps were performed to prepare the dataset for analysis:
- Loaded and explored data using `pandas`
- Checked data structure using `.info()` and `.describe()`
- Handled missing values in the *Review Rating* column using median imputation
- Standardized column names using snake_case
- Created new features:
  - `age_group` to segment customers by age
  - `purchase_frequency_days` to understand buying patterns
- Identified and removed redundant columns after consistency checks
- Prepared a clean dataset for database storage and SQL analysis 

---

## 🗄️ Database Integration

- Connected Python to PostgreSQL using SQLAlchemy
- Loaded the cleaned DataFrame into PostgreSQL tables
- Performed structured SQL analysis to answer business-focused questions 

---

## 📈 SQL Analysis (Business Questions Answered)

The following analyses were performed using SQL:
- Revenue comparison by gender
- Identification of high-spending customers who used discounts
- Top 5 products based on average review ratings
- Comparison of average purchase amounts by shipping type
- Subscriber vs non-subscriber revenue and spending analysis
- Identification of discount-dependent products
- Customer segmentation into New, Returning, and Loyal groups
- Top 3 products within each category
- Relationship between repeat purchases and subscription status
- Revenue contribution by different age groups 

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:
- Revenue trends
- Customer segmentation
- Product performance
- Subscription and discount impact
- Shipping type analysis

The dashboard allows stakeholders to explore insights dynamically and supports data-driven business decisions. 

---

## 🔍 Key Insights

- Subscribers contribute higher average revenue compared to non-subscribers  
- Loyal customers show consistent purchasing behavior with lower discount dependency  
- Certain products rely heavily on discounts to drive sales  
- Express shipping users tend to have higher average purchase values  
- Specific age groups contribute disproportionately to total revenue  

---

## 💡 Business Recommendations

- Promote subscription plans with exclusive benefits to increase retention  
- Strengthen customer loyalty programs for repeat buyers  
- Optimize discount strategies to balance sales growth and profit margins  
- Highlight top-rated and best-selling products in marketing campaigns  
- Focus targeted marketing efforts on high-revenue customer segments 

---

## ▶️ How to Run This Project

1. Clone this repository  
2. Install required Python libraries  
3. Run the Python scripts for data cleaning and loading  
4. Connect to PostgreSQL for SQL analysis  
5. Open the Power BI dashboard to explore insights  

---

## 📌 Skills Demonstrated

- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis (EDA)  
- SQL Business Analysis  
- Database Integration  
- Data Visualization & Storytelling  
- Business Insight Generation  

---



⭐ If you found this project useful, feel free to star the repository!

