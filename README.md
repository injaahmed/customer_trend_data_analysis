# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using a dataset of 3,900 transactions to understand customer spending patterns, product preferences, customer loyalty, discounts, subscriptions, and purchasing behavior.

The main goal is to generate business insights and recommendations that can help improve sales, customer engagement, marketing strategies, and long-term customer loyalty.

## 🎯 Business Problem

The company wants to understand:

- What factors influence customer purchases?
- How do customer demographics affect spending?
- Which products and categories perform best?
- Do discounts influence purchasing behavior?
- How does subscription status affect customer spending?
- Which customers are new, returning, or loyal?
- Which age groups contribute the most revenue?
- How can customer data be used to improve marketing and product strategies?

### Main Business Question

> How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

## 📊 Dataset

- **Rows:** 3,900
- **Columns:** 18
- **Missing Data:** 37 values in the Review Rating column

### Key Data

- Customer demographics
- Product and purchase information
- Discount and promotional information
- Purchase frequency
- Review ratings
- Subscription status
- Shipping information

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - Data Cleaning
  - Exploratory Data Analysis
  - Feature Engineering

- **PostgreSQL**
  - SQL Analysis
  - Business Queries
  - Customer Segmentation
  - Revenue Analysis

- **Power BI**
  - Interactive Dashboard
  - KPI Analysis
  - Customer & Product Insights

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
PostgreSQL Database
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
     ↓
Recommendations
```

## 🐍 Python Data Preparation

The dataset was cleaned and prepared using Python.

Main steps:

- Loaded the dataset using Pandas
- Explored the dataset using `info()` and `describe()`
- Checked missing values
- Filled missing Review Ratings using the median rating of each product category
- Standardized column names
- Created an `age_group` feature
- Created `purchase_frequency_days`
- Checked redundant columns
- Removed `promo_code_used`
- Loaded the cleaned data into PostgreSQL

## 🗄️ SQL Analysis

PostgreSQL was used to answer important business questions:

1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Products by Rating
4. Standard vs. Express Shipping
5. Subscribers vs. Non-Subscribers
6. Discount-Dependent Products
7. Customer Segmentation
8. Top 3 Products per Category
9. Repeat Buyers & Subscriptions
10. Revenue by Age Group

## 📈 Key Insights

### Customer Segmentation

| Customer Segment | Customers |
|---|---:|
| Loyal | 3,116 |
| Returning | 701 |
| New | 83 |

### Subscription Analysis

| Subscription | Customers | Avg. Spend | Total Revenue |
|---|---:|---:|---:|
| Yes | 1,053 | $59.49 | $62,645 |
| No | 2,847 | $59.87 | $170,436 |

### Top-Rated Products

| Product | Average Rating |
|---|---:|
| Gloves | 3.86 |
| Sandals | 3.84 |
| Boots | 3.82 |
| Hat | 3.80 |
| Skirt | 3.78 |

### Discount-Dependent Products

Products with the highest percentage of discounted purchases:

- Hat
- Sneakers
- Coat
- Sweater
- Pants

Hat had the highest discount rate at 50%.

### Revenue by Age Group

| Age Group | Revenue |
|---|---:|
| Young Adult | $62,143 |
| Middle-aged | $59,197 |
| Adult | $55,978 |
| Senior | $55,763 |

## 📊 Power BI Dashboard

An interactive **Customer Behavior Dashboard** was created in Power BI.

The dashboard includes:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Customer and purchase filters

## 💡 Business Recommendations

### 1. Boost Subscriptions
Promote exclusive benefits and incentives to increase subscription adoption.

### 2. Customer Loyalty Programs
Reward repeat buyers and encourage customers to move into the Loyal segment.

### 3. Review Discount Policy
Balance sales growth from discounts with margin control.

### 4. Product Positioning
Promote highly rated and best-selling products in marketing campaigns.

### 5. Targeted Marketing
Focus marketing efforts on high-revenue age groups and express-shipping users.


## 🚀 Project Outcome

This project demonstrates an end-to-end data analytics workflow:

**Python → PostgreSQL → SQL → Power BI → Business Recommendations**

The project converts customer transaction data into actionable insights for marketing, customer retention, product positioning, and subscription growth.

