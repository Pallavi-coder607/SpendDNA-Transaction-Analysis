# 💰 SpendDNA – Transaction Analysis

SpendDNA is a Python-based personal transaction analysis project that analyzes financial transaction data to understand spending patterns, categories, vendors, and spending behaviour.

## 📌 Project Overview

The project works with transaction data and transforms raw financial records into meaningful insights.

The dataset contains **1,328 transactions** across **8 columns**:

* Date
* Time
* Description
* Type
* Amount
* Balance
* Mode
* Ref

During data cleaning, **18 duplicate transactions were removed**, resulting in **1,310 clean transactions**. Dates, amounts, transaction types, and missing modes were also processed and standardized.

## 🚀 Features

### 1. Transaction Parser

* Parses mixed date formats
* Cleans transaction amounts
* Standardizes Debit/Credit values
* Handles missing transaction modes
* Removes duplicate transactions

### 2. Vendor Extractor

Extracts and standardizes vendors from transaction descriptions using keyword-based matching.

The project identifies **43 unique vendors**, including:

* Swiggy
* Zomato
* Amazon
* Flipkart
* Blinkit
* Zepto
* Uber
* Ola
* Starbucks
* Netflix
* Spotify
* Zerodha
* Groww
* And more

No descriptions were left uncategorised in the completed vendor extraction.

### 3. Category Tagger

Transactions are grouped into spending categories such as:

* 🍔 Food Delivery
* 🛒 Quick Commerce
* 🛍️ E-commerce
* 🚕 Transport
* ☕ Cafe
* 🍽️ Restaurants
* 📺 Subscriptions
* 💡 Utilities
* 🥦 Groceries
* 📈 Investments
* ⛽ Fuel
* 🎬 Entertainment
* 💸 Personal Transfer
* 🏧 Cash Withdrawal

The notebook also separates income transactions into an **Income** category.

### 4. Spending Analysis

The project analyzes:

* Total credits and debits
* Net financial change
* Savings rate
* Spending by category
* Top vendors
* Transaction counts

### 5. Monthly & Time-of-Day Analysis

The project studies spending patterns across:

* Monthly spending trends
* Spending categories by month
* Spending by hour of the day

### 6. Anomaly Detection

Spending anomalies are identified using category-level statistical analysis and z-scores to highlight unusually large transactions.

### 7. Spending Archetypes

SpendDNA identifies behavioural spending patterns such as:

* 🛍️ The Shopaholic
* 📈 The Investor
* 💸 The YOLO Spender
* 🍔 The Foodie
* 🛒 The Quick Commerce Junkie
* 🌙 The Late-Night Snacker
* 🚕 The Cab Commuter
* 📺 The Subscription Lover
* 💰 The Disciplined Saver

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Google Colab
* Jupyter Notebook

## 📂 Project Structure

```text
SpendDNA-Transaction-Analysis/
│
├── SpendDNA_Week2_Pallavi.ipynb
├── README.md
└── rahul_transactions.csv
```

## ▶️ How to Run

1. Download or clone this repository.
2. Open the `.ipynb` file using Google Colab or Jupyter Notebook.
3. Upload the transaction dataset.
4. Run the notebook cells in order.
5. View the generated spending analysis and final SpendDNA report.

## 📊 Sample Insights

The analysis helps identify:

* Highest spending categories
* Most frequently used vendors
* Monthly spending changes
* Time-of-day spending behaviour
* Unusual transactions
* Personal spending archetypes

## 🎯 Learning Outcomes

Through this project, I strengthened my understanding of:

* Data cleaning and preprocessing
* Pandas DataFrames
* NumPy
* Date and time handling
* String processing
* Feature engineering
* Transaction categorization
* Exploratory data analysis
* Basic anomaly detection
* Rule-based behavioural analysis

## 👩‍💻 Author

**Pallavi C N**

B.Tech – Computer Science and Engineering

## ⭐ Project

**SpendDNA – Week 2 Minor Project**

Built as part of my minor project work to explore financial transaction data and understand spending behaviour.
