# Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes **customer shopping behavior** using transactional retail data to uncover insights into **spending patterns, customer segments, product performance, and subscription behavior**. The goal is to support **data-driven business decisions** through a complete analytics workflow involving **Python, SQL, PostgreSQL, and Power BI**. 

---

## 🎯 Business Objectives
- Understand how **customer demographics** impact revenue  
- Identify **high-value customers** and repeat buying behavior  
- Analyze **product performance**, ratings, and discount dependency  
- Evaluate the impact of **subscriptions and shipping types**  
- Translate insights into **actionable business recommendations**

---

## 📊 Dataset Summary
- **Total Records:** 3,900 transactions  
- **Total Features:** 18 columns  

### Key Data Attributes
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavioral Data:** Discounts, Promo Codes, Previous Purchases, Review Ratings, Shipping Type  

⚠️ *Missing Values:*  
- 37 missing values in the `review_rating` column, handled during data preprocessing. 

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy) – Data cleaning & feature engineering  
- **PostgreSQL** – Business-driven SQL analysis  
- **SQLAlchemy** – Python–PostgreSQL integration  
- **Power BI** – Interactive dashboard & data storytelling  

---

## 🔍 Data Preparation & Feature Engineering (Python)
Key steps performed using Python:
- Loaded and explored data using `pandas`
- Handled missing review ratings using **median imputation by product category**
- Standardized column names (snake_case)
- Created derived features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns after validation
- Loaded cleaned data into **PostgreSQL** for SQL analysis 
---

## 🧮 SQL-Based Business Analysis
The following key business questions were answered using SQL:

1. Revenue contribution by **gender**
2. Identification of **high-spending discount users**
3. Top 5 products by **average review rating**
4. Purchase behavior by **shipping type**
5. Spend comparison between **subscribers vs non-subscribers**
6. Products most **dependent on discounts**
7. Customer segmentation into **New, Returning, Loyal**
8. Top 3 products within each **category**
9. Relationship between **repeat buyers and subscriptions**
10. Revenue contribution by **age group** 

Advanced SQL concepts used:
- CTEs
- Subqueries
- Window functions
- Conditional aggregation

---

## 📈 Power BI Dashboard
An interactive **Power BI dashboard** was built to visualize insights, including:
- Customer distribution & KPIs
- Revenue and sales by category
- Subscription analysis
- Age-group based revenue
- Discount and shipping behavior

The dashboard enables **drill-down analysis** and supports business stakeholders in decision-making. 

---

## 💡 Key Business Insights
- A small percentage of customers contribute a **major share of revenue**
- Subscribed customers show **higher engagement**, though non-subscribers still drive volume
- Certain products rely heavily on **discounts**, impacting margins
- Younger and middle-aged customer groups contribute the **highest revenue**
- Express shipping users tend to have **higher average purchase values**

---

## ✅ Business Recommendations
- **Boost subscriptions** by offering exclusive benefits  
- Introduce **loyalty programs** to convert repeat buyers into loyal customers  
- Optimize **discount strategies** to protect profit margins  
- Highlight **top-rated and best-selling products** in marketing campaigns  
- Focus **targeted marketing** on high-revenue age groups and premium shipping users 

---

## 📌 Author
**[Dev Prince]**  
Business Analyst | SQL | Python | Power BI  

---

## 📄 Notes
This project demonstrates an **end-to-end business analytics workflow**, aligning technical analysis with real-world retail decision-making.
