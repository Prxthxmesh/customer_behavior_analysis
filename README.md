# customer_behavior_analysis
Customer shopping behavior analysis using Python, SQL, and Power BI to uncover insights on spending patterns, customer segmentation, and product preferences.

🛍️ Customer Shopping Behavior Analysis

📌 Project Overview

This project analyzes customer shopping behavior using transactional data of over **3,900 purchases** across multiple product categories. The objective is to uncover insights into **spending patterns, customer segmentation, and product preferences** to support data-driven business decisions. 


📊 Dataset Information

* Total Records:3,900
* Total Features:18
* Key Attributes:

  * Customer Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item, Category, Purchase Amount, Season
  * Behavior Data: Discounts, Frequency, Ratings, Shipping Type
* **Missing Data:** 37 values in Review Rating column handled using median imputation 



🧹 Data Preprocessing

* Data cleaning using **Pandas**
* Handling missing values
* Column renaming (snake_case format)
* Feature Engineering:

  * Age Group creation
  * Purchase Frequency (days)
* Removed redundant columns

---

🗄️ Database Integration

* Connected Python with MySQL using **SQLAlchemy**
* Stored cleaned data into database
* Executed SQL queries for analysis

---

📈 Data Analysis (SQL Insights)

* Revenue analysis by gender
* High-spending customers using discounts
* Top-rated products
* Shipping type comparison
* Subscriber vs non-subscriber behavior
* Discount-heavy products
* Customer segmentation (New, Returning, Loyal)
* Top products by category
* Repeat buyers vs subscriptions
* Revenue by age group 

---

📊 Dashboard

An interactive dashboard was created using **Power BI** to visualize:

* Customer distribution
* Revenue trends
* Category-wise sales
* Subscription insights
* Age group performance

---

💡 Business Recommendations

* Enhance subscription benefits
* Introduce loyalty programs
* Optimize discount strategies
* Focus on high-value customers
* Promote best-selling products 

---

🛠️ Tech Stack

* **Python** (Pandas, SQLAlchemy)
* **MySQL**
* **Power BI**
* **Jupyter Notebook**

---

🚀 How to Run the Project

 1. Clone Repository

```bash
git clone https://github.com/your-username/customer-shopping-analysis.git
```

2. Install Dependencies

```bash
pip install pandas sqlalchemy pymysql
```

3. Create Database

```sql
CREATE DATABASE customer_behavior;
```

4. Run Jupyter Notebook

* Load dataset
* Run preprocessing
* Connect to MySQL
* Perform analysis

---

