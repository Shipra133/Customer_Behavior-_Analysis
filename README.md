# Customer_Behavior-_Analysis

* **`customer_shopping_behavior.ipynb`** → your Python notebook (EDA + cleaning steps)
* **`Customer_behavior_pgsql.sql`** → your SQL queries for PostgreSQL analysis
---

# 🧠 Customer Behavior Data Analytics Project

## 📘 Overview

This project performs an end-to-end analysis of **customer shopping behavior** — from raw data to interactive insights.
It combines **Python (EDA + cleaning)**, **PostgreSQL (SQL-based analysis)**, and **Power BI (visualization)** to reveal patterns in spending, preferences, and customer segments.

The main objective is to derive actionable insights that can help businesses improve **sales strategy, marketing focus, and customer retention**.

---

## 📂 Dataset

* **File:** `customer_shopping_behavior.csv`
* **Size:** ~10,000+ rows
* **Attributes include:**

  * Customer demographics (Gender, Age, Location)
  * Shopping details (Item Purchased, Purchase Amount, Discount, Shipping Type)
  * Customer engagement (Previous Purchases, Subscription Status, Review Ratings)

---

## 🧰 Tools & Technologies

| Category            | Tools Used                                  |
| ------------------- | ------------------------------------------- |
| Data Cleaning & EDA | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database & Queries  | PostgreSQL                                  |
| Visualization       | Power BI                                    |
| Presentation        | Gamma App                                   |
| IDEs                | Jupyter Notebook, VS Code                   |

---

## ⚙️ Project Workflow

### 1. **Data Loading & Cleaning (Python)**

* File: `customer_shopping_behavior.ipynb`
* Steps include:

  * Loading dataset with `pandas`
  * Handling missing values and outliers
  * Data type corrections and standardization
  * Exploratory Data Analysis (EDA) using `matplotlib` & `seaborn`

### 2. **SQL-Based Analysis (PostgreSQL)**

* File: `Customer_behavior_pgsql.sql`
* Queries performed:

  * **Revenue by gender**
  * **Top-rated products**
  * **Effect of discounts on purchases**
  * **Customer segmentation by purchase frequency**
  * **Shipping type cost comparison**
  * **Subscription impact on revenue**

### 3. **Visualization (Power BI)**

* Built an **interactive Power BI dashboard** visualizing:

  * Sales by gender, category, and region
  * Customer segmentation (New, Returning, Loyal)
  * Purchase trends and revenue distribution
  * Discount vs Purchase correlation

### 4. **Reporting & Presentation**

* A concise **report** summarizes insights and business recommendations.
* **Presentation created in Gamma App** for a clean, modern showcase of findings.

---

## 📈 Key Insights

* **Female customers** contribute higher average revenue.
* **Discounts** positively influence purchase frequency and total spend.
* **Express shipping users** show higher average order values.
* **Loyal customers** (10+ purchases) contribute over 50% of total sales.
* **Top 5 items** have average ratings above 4.5.

---

## 🧩 Folder Structure

```
📁 Customer-Behavior-Analytics/
│
├── 📊 data/
│   └── customer_shopping_behavior.csv
│
├── 🧮 notebooks/
│   └── customer_shopping_behavior.ipynb
│
├── 💾 sql/
│   └── Customer_behavior_pgsql.sql
│
├── 📊 dashboard/
│   └── customer_behavior.pbix
│
├── 📄 reports/
│   └── final_report.pdf
│
├── 🎥 presentation/
│   └── gamma_presentation_link.txt
│
└── README.md
```
## 🪄 How to Run

### Prerequisites

* Python 3.x
* PostgreSQL
* Power BI Desktop
* Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sqlalchemy`, `psycopg2`


## 💡 Future Enhancements

* Integrate predictive modeling (e.g., churn prediction).
* Automate data pipeline from SQL → Power BI.
* Deploy dashboard for live updates.

---


