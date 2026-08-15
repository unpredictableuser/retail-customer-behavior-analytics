# Customer Shopping Behaviour Analysis

## Overview

This project demonstrates an end-to-end data analytics workflow for analyzing customer shopping behaviour and generating meaningful business insights.

The project covers data cleaning and exploratory analysis using Python, business analysis using SQL, and interactive visualization using Power BI.

The analysis focuses on customer demographics, purchasing behaviour, product categories, revenue, discounts, subscriptions, shipping methods, customer segmentation, and purchasing patterns.

The objective is to transform raw customer data into actionable insights that can support data-driven business and marketing decisions.

---

## Dashboard Preview

The Power BI dashboard provides an interactive view of customer shopping behaviour and key business metrics.

![Customer Behaviour Dashboard](images/dashboard.png)

### Dashboard Highlights

The dashboard currently provides:

* Total number of customers
* Average purchase amount
* Average review rating
* Customer subscription analysis
* Revenue by product category
* Sales by product category
* Revenue by age group
* Sales by age group
* Interactive filters for subscription status, gender, category, and shipping type

---

## Business Problem

Businesses need to understand how customers purchase products, which categories generate the most revenue, how customer demographics influence purchasing behaviour, and how factors such as subscriptions, discounts, and shipping methods relate to customer activity.

This project addresses these questions by analyzing customer shopping data and developing an interactive business intelligence dashboard.

The analysis helps identify:

* Customer purchasing patterns
* High-performing product categories
* Revenue contribution across customer groups
* Subscription behaviour
* Customer demographic trends
* Discount and promotional behaviour
* Repeat purchasing behaviour
* Customer segments based on previous purchases

---

## Dataset

The project uses a customer shopping behaviour dataset containing **3,900 customer records and 18 columns**.

The dataset contains information related to:

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

### Dataset Quality

The dataset was examined for:

* Missing values
* Duplicate records
* Data types
* Categorical values
* Numerical values
* Outliers
* Data consistency

The `Review Rating` field contains missing values, which were identified during the data-quality analysis.

---

## Tools & Technologies

| Tool / Technology  | Purpose                                             |
| ------------------ | --------------------------------------------------- |
| Python             | Data cleaning, preprocessing, EDA and visualization |
| Pandas             | Data manipulation and analysis                      |
| NumPy              | Numerical operations                                |
| Matplotlib         | Data visualization                                  |
| Seaborn            | Statistical visualization                           |
| PostgreSQL         | SQL-based business analysis                         |
| Power BI           | Interactive dashboard and business intelligence     |
| Jupyter Notebook   | Python analysis and documentation                   |
| PowerPoint / Gamma | Project presentation                                |

---

# Project Workflow

```text
Raw Dataset
     ↓
Python
     ↓
Data Cleaning & EDA
     ↓
SQL / PostgreSQL
     ↓
Business Analysis
     ↓
Power BI
     ↓
Interactive Dashboard
     ↓
Business Insights & Recommendations
```

---

## 1. Data Loading & Exploration

The dataset was imported into Python using Pandas.

Initial analysis included:

* Checking dataset dimensions
* Inspecting column names
* Understanding data types
* Viewing sample records
* Checking missing values
* Understanding numerical and categorical variables
* Generating descriptive statistics

The dataset contains **3,900 rows and 18 columns**.

---

## 2. Data Cleaning & Preprocessing

The raw dataset was prepared for analysis through a series of data-quality and preprocessing steps.

The cleaning process included:

* Checking missing values
* Checking duplicate records
* Validating data types
* Standardizing column names
* Renaming columns where required
* Creating derived features
* Creating customer age groups
* Checking data consistency
* Preparing the dataset for SQL and Power BI analysis

### Python Analysis

The following screenshot shows part of the Python/Jupyter Notebook workflow, including column preprocessing and the creation of an `age_group` feature.

![Python Data Cleaning and Preprocessing](images/python-analysis.png)

---

## 3. Exploratory Data Analysis

Exploratory Data Analysis was performed to identify patterns and relationships within the customer shopping dataset.

The analysis covers:

* Customer demographics
* Gender distribution
* Age groups
* Product categories
* Purchase amounts
* Review ratings
* Subscription status
* Discount usage
* Promo code usage
* Shipping methods
* Purchase frequency
* Previous purchases
* Revenue trends

Visualizations were used to understand customer behaviour and identify important business patterns.

---

# 4. Customer Segmentation

Customer segmentation was performed to understand customers based on their previous purchasing behaviour.

Customers were categorized into behavioural groups based on their number of previous purchases.

The segmentation logic used in the analysis includes:

* **New Customers**
* **Returning Customers**
* **Loyal Customers**

This segmentation helps businesses understand customer engagement and identify opportunities for retention and targeted marketing.

---

# 5. SQL Analysis

PostgreSQL was used to perform structured business analysis on the customer dataset.

The SQL analysis includes:

* Aggregation functions
* `GROUP BY`
* Filtering
* Conditional logic using `CASE`
* Subqueries
* Common analytical queries
* Customer segmentation
* Revenue analysis
* Product analysis
* Subscription analysis
* Discount analysis
* Customer behaviour analysis

### Business Questions

The SQL analysis addresses questions such as:

1. What is the total revenue generated by male and female customers?
2. Which customers used a discount but still spent more than the average purchase amount?
3. Which products have the highest average review ratings?
4. How does purchase amount vary by shipping type?
5. How does purchasing behaviour differ between subscribers and non-subscribers?
6. Which products have the highest percentage of discounted purchases?
7. How can customers be segmented based on previous purchases?
8. Which products are most purchased within each category?
9. What is the relationship between repeat purchases and subscription status?
10. How does revenue vary across different customer age groups?

### SQL Analysis Preview

![SQL Business Analysis](images/sql-analysis.png)

---

# 6. Power BI Interactive Dashboard

The processed data was used to create an interactive Power BI dashboard.

The dashboard provides business-focused visualizations and interactive filtering capabilities.

### Key Dashboard Components

#### KPI Cards

* Number of Customers
* Average Purchase Amount
* Average Review Rating

#### Customer Analysis

* Customers by subscription status
* Customer behaviour by gender
* Customer analysis by age group

#### Product & Revenue Analysis

* Revenue by category
* Sales by category
* Category-level purchasing behaviour

#### Demographic Analysis

* Revenue by age group
* Sales by age group

#### Interactive Filters

The dashboard provides filters for:

* Subscription Status
* Gender
* Category
* Shipping Type

These filters allow users to interactively explore different customer segments and business dimensions.

---

# 7. Key Business Insights

The analysis provides several useful insights into customer shopping behaviour.

### Customer Behaviour

* The dataset contains approximately **3.9K customers**.
* Customer purchasing behaviour varies across demographic and product categories.
* Previous purchases can be used to distinguish new, returning, and loyal customers.

### Revenue & Purchase Behaviour

* The average purchase amount shown on the dashboard is approximately **$59.76**.
* Clothing is one of the strongest categories in terms of both sales and revenue.
* Customer age groups show differences in revenue and purchase volume.

### Subscription Behaviour

* The dashboard shows that approximately **27% of customers are subscribers**, while approximately **73% are non-subscribers**.
* This indicates an opportunity to investigate strategies for improving subscription adoption.

### Customer Ratings

* The average review rating shown on the dashboard is approximately **3.75**.

These insights can be used to support marketing, customer retention, product, and promotional decisions.

---

# 8. Business Recommendations

Based on the analysis, the following business recommendations can be considered.

### 1. Customer Retention

Focus on returning and loyal customers through:

* Loyalty programs
* Personalized offers
* Exclusive promotions
* Repeat-purchase incentives

### 2. New Customer Conversion

Encourage new customers to make their second purchase through:

* First-to-second purchase offers
* Personalized recommendations
* Limited-time incentives
* Follow-up campaigns

### 3. Subscription Growth

Since the dashboard shows a smaller proportion of subscribers compared with non-subscribers, businesses can experiment with:

* Subscription discounts
* Exclusive subscriber benefits
* Personalized subscription offers
* Loyalty rewards for subscribers

### 4. Product & Category Strategy

High-performing categories such as Clothing and Accessories can receive greater focus through:

* Inventory planning
* Promotional campaigns
* Cross-selling
* Product recommendations

### 5. Customer Personalization

Customer characteristics such as age group, gender, previous purchases, and category preferences can be used to develop more targeted marketing campaigns.

### 6. Discount Strategy

Discount usage should be analyzed carefully so that promotions increase customer engagement without unnecessarily reducing revenue.

---

# 9. Important Note on RFM Analysis

The current dataset does **not contain a transaction/purchase date field**.

Because Recency requires an actual purchase date, a complete traditional **RFM (Recency, Frequency, Monetary)** model cannot be calculated reliably from this dataset.

The current project therefore uses **previous purchase behaviour-based customer segmentation** rather than claiming a full RFM implementation.

A complete RFM model can be added in a future version if transaction-level data containing a purchase date becomes available.

---

# 10. Project Files

```text
retail-customer-behavior-analytics/
│
├── images/
│   ├── dashboard.png
│   ├── python-analysis.png
│   └── sql-analysis.png
│
├── customer_shopping_behavior.csv
├── customer_shopping_behaviour_analysis.ipynb
├── customer behaviour analysis.sql
├── customer behaviour dashboard.pbix
├── Customer Shopping Behavior Analysis report.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
└── README.md
```

---

# 11. How to Run the Project

## Python Notebook

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
customer_shopping_behaviour_analysis.ipynb
```

Run the notebook cells to perform data loading, cleaning, exploratory analysis, feature creation, and visualization.

---

## SQL Analysis

The SQL analysis is designed for PostgreSQL.

Steps:

1. Set up a PostgreSQL database.
2. Import the customer shopping dataset.
3. Create/load the `customer` table.
4. Open:

```text
customer behaviour analysis.sql
```

5. Execute the queries using PostgreSQL or a compatible SQL client.

---

## Power BI Dashboard

Open the following file using Power BI Desktop:

```text
customer behaviour dashboard.pbix
```

If required, update the data source location and refresh the dataset.

The dashboard can then be explored using the available filters and interactive visuals.

---

# 12. Deliverables

The repository contains the following project deliverables:

* Public GitHub Repository
* Customer Shopping Behaviour Dataset
* Python/Jupyter Notebook
* SQL Analysis
* Power BI Interactive Dashboard
* README Documentation
* Business Insights Report (PDF)
* Project Presentation (PPTX)

---

# 13. Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Python
* Pandas
* NumPy
* Data Visualization
* SQL
* PostgreSQL
* Customer Segmentation
* Power BI
* Interactive Dashboard Development
* Business Intelligence
* Business Insights
* Data Storytelling
* Analytical Reporting

---

# 14. Conclusion

This project demonstrates an end-to-end customer behaviour analytics workflow using Python, SQL, and Power BI.

The analysis transforms raw customer shopping data into structured business insights by combining data cleaning, exploratory analysis, SQL-based business questions, customer segmentation, visualization, and interactive dashboard development.

The resulting dashboard provides an accessible way for business users to explore customer behaviour, product performance, revenue patterns, subscription activity, and demographic trends.

The project also highlights opportunities for customer retention, subscription growth, personalized marketing, and category-level business strategy.

---

## Repository

This project is publicly available on GitHub for review and verification.

**GitHub Repository:**
https://github.com/unpredictableuser/retail-customer-behavior-analytics

---
