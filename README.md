# Instacart Basket Analysis – Customer Behavior & Marketing Insights

## Project Overview

This project analyzes customer purchasing behavior on the Instacart platform to generate data-driven marketing and sales insights.

Using Python (Pandas, NumPy, Matplotlib, Seaborn), large-scale transactional, product, and customer datasets were cleaned, merged, enriched, and analyzed to uncover patterns in:

- Ordering frequency
- Spending behavior
- Product demand
- Customer loyalty
- Demographic segmentation
- Regional trends

The final deliverable was an executive-style Excel report designed for non-technical stakeholders.

---

## Business Objective

Instacart’s Marketing and Sales leadership sought to answer:

- What are the busiest days and times?
- When do customers spend the most?
- How should products be grouped by price?
- Which departments drive the highest demand?
- How does loyalty impact ordering behavior?
- Do regional differences affect spending?
- How do customer demographics influence purchasing patterns?

The goal: Translate behavioral data into actionable marketing strategy.

---

## Tools & Technologies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel (Final Executive Report)

---

## Analytical Workflow

### 1. Data Cleaning & Validation
- Handled missing values
- Removed duplicates
- Standardized column formats
- Verified merge integrity using join indicators

### 2. Data Integration
- Combined orders, products, departments, and customer data
- Preserved full order history using left joins
- Ensured no unintended row loss

### 3. Feature Engineering
Created behavioral and segmentation features including:

- Order frequency metrics
- Loyalty segmentation (New / Regular / Loyal)
- Spending tiers (Low / High spender)
- Median days between orders
- Regional mapping (U.S. Census regions)
- Rule-based customer profiles

### 4. Aggregation & Behavioral Analysis
- Customer-level KPI calculation
- Temporal demand analysis
- Segment comparison
- Department performance evaluation

---

## Key Insights

### Ordering Patterns
- Sunday and Monday show highest order volumes.
- Mid-week (Wed–Thu) shows lower demand.
- Orders peak between 9 AM and 5 PM.

**Marketing implication:** Shift promotions to lower-demand periods.

### Spending Behavior
- Average item price peaks during early mornings and weekends.
- Most products fall within the $1–$15 range.

**Marketing implication:** Promote premium products during high-spend windows.

### Department Demand
- A small number of departments drive a disproportionate share of orders.
- Remaining categories follow a long-tail distribution.

**Marketing implication:** Prioritize high-performing departments while testing targeted promotions in lower-frequency categories.

### Loyalty & Retention
- Regular customers generate the largest total order volume.
- Loyal customers show highest order frequency.
- New customers contribute the fewest orders.

**Marketing implication:** Focus on converting Regular → Loyal customers.

### Regional Trends
- Spending behavior is consistent across U.S. regions.
- No region significantly over-indexes in high spending.

**Marketing implication:** National pricing strategies are appropriate.

### Customer Segmentation
- Family households represent the largest active segment.
- Affluent frequent shoppers show highest average spend and order frequency.
- Budget occasional shoppers demonstrate price sensitivity.

**Marketing implication:** Tailor campaigns by customer profile rather than age alone.

---

## Dataset

Primary dataset: Instacart Online Grocery Shopping Dataset 2017  
Source: Kaggle  

Note: Customer demographic attributes were synthetically generated for educational purposes.

---

## Project Outcome

This project demonstrates:

- End-to-end data analysis workflow
- Data cleaning and validation
- Feature engineering and segmentation
- Behavioral analytics
- Business-driven storytelling
- Translation of insights into marketing strategy

---

## Author

Joesielyn Toling  
Data Analytics Immersion Program – 2026
