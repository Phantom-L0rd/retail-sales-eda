# Retail Sales & Customer Demographics EDA

## Overview

This project explores a **synthetic retail dataset** that mimics real-world sales and customer interactions. Through a detailed **exploratory data analysis (EDA)**, we uncover patterns in purchasing behavior, time-based trends, and product category performance — all through the lens of storytelling with data.

## About the Dataset

This dataset includes:
- **Transaction Details** (Date, Quantity, Price, Total Amount)
- **Customer Demographics** (Gender, Age)
- **Product Info** (Product Category)

**Total records:** 1000  
**Source:** [Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset/data)  
**Author:** Mohammad Talib

It is ideal for showcasing skills in:
- Data cleaning & feature engineering
- Business-focused data visualization
- Insight generation & storytelling


## Project Goals

- Understand how **age and gender** influence retail behavior
- Discover **temporal patterns** in sales volume and value
- Identify **top product categories** by quantity and revenue
- Examine **transaction-level dynamics** and spending patterns
- Deliver **business-ready insights** for strategic decisions


## EDA Approach (Highlights)

### 1. Introduction  
Framing the retail setting and laying out the objectives of this analysis.

### 2. Dataset Preview  
Exploring the structure, types, and quality of the data.

### 3. Data Cleaning  
Checking duplicates, fixing types, and preparing features (e.g., extracting Month/Year from Date).

### 4. Univariate Exploration    
- Who are the shoppers? (Age, Gender)  
- What do they buy? (Product Categories)  
- How much do they spend? (Total Amount, Quantity, Unit Price)

### 5. Business Questions Explored

1. How does customer age and gender influence their purchasing behavior?
2. Are there discernible patterns in sales across different time periods?
3. Which product categories hold the highest appeal among customers?
4. What are the relationships between age, spending, and product preferences?
5. How do customers adapt their shopping habits during seasonal trends?
6. Are there distinct purchasing behaviors based on the number of items bought per transaction?
7. What insights can be gleaned from the distribution of product prices within each category?


## Tools & Technologies

- Python
- pandas, matplotlib, seaborn
- Jupyter Notebook

## Environment Setup

To replicate this project:

```bash
git clone https://github.com/Phantom-L0rd/retail-sales-eda.git
cd retail-sales-eda
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook
```

