# Customer-Purchase-Behaviour-Analysis-Excel-Dashboard

This project analyzes customer purchase behaviour for a retail fashion company using Excel.  
The goal is to identify the key revenue drivers, understand customer segments, evaluate seasonal trends, and study the impact of discounts, shipping types, and payment methods on purchasing patterns.  
The final output is an interactive Excel dashboard built using PivotTables and PivotCharts.

---

##  1. Business Problem Statement

A retail fashion company wants to analyze customer purchase behavior to improve:

- Marketing strategies  
- Inventory planning  
- Product recommendations  
- Customer segmentation  

The main goals are to understand:

- Which customer groups generate the most revenue  
- Trends across product categories, seasons, and purchase frequency  
- Impact of shipping types, discounts, and promo codes on sales  
- Customer preferences based on age, gender, location, and payment method  

This analysis helps the business make **data-driven decisions** and optimize sales performance.

---

## 🎯 2. Objective

Perform an end-to-end Excel data analysis workflow:

1. Data Loading  
2. Data Cleaning  
3. Data Preprocessing  
4. PivotTables & PivotCharts  
5. Dashboard Building  
6. Insight Generation  

---

## 📁 3. Dataset Description

**Dataset:** Customer Purchase Dataset  
Contains customer-level purchase information.

| Column Name | Description |
|------------|-------------|
| Customer ID | Unique identifier for customers |
| Age | Customer age |
| Gender | Male / Female |
| Item Purchased | Product name |
| Category | Clothing, Footwear, Accessories, Outerwear |
| Purchase Amount (USD) | Amount spent (used as revenue) |
| Location | Customer state |
| Size | Product size |
| Colours | Product color |
| Season | Winter, Spring, Summer, Fall |
| Review Rating | Rating (1–5) |
| Subscription Status | Yes / No |
| Shipping Type | Express, Free Shipping, Standard |
| Discount Applied | Yes / No |
| Promo Code Used | Yes / No |
| Previous Purchases | Number of past purchases |
| Payment Method | Cash, Credit Card, PayPal, Venmo, Bank Transfer |
| Frequency of Purchases | Weekly, Fortnightly, Monthly, Annually |

---

## 🔄 4. Approach / Methodology

### **Step 1: Data Loading**
- Imported CSV into Excel  
- Verified structure and data types  

### **Step 2: Data Cleaning**
- Standardized text fields (Location, Size, Color, Season)  
- Ensured numeric fields were valid (Age, Purchase Amount, Ratings)  
- Cleaned Yes/No fields  
- Removed duplicates using **Customer ID + Item Purchased**  
- Converted data into an Excel Table  

### **Step 3: Data Preprocessing**
- Created derived fields:
  - **Age Group:** Young (≤25), Adult (26–50), Senior (>50)  
  - **Revenue:** Purchase Amount (USD)  
  - **Subscription Flag:** Yes = 1, No = 0  
- Prepared data for pivot analysis  

### **Step 4: Dashboard & Visualization**
Built the following PivotTables and Charts:

| Dashboard Element | Fields Used | Insights Provided |
|------------------|-------------|-------------------|
| Revenue by Category | Category (Rows), Purchase Amount (Sum) | Best­selling product category |
| Revenue by Season | Season (Rows), Revenue (Sum) | Seasonal performance |
| Revenue by Age & Gender | Age Group, Gender | Buying demographics |
| Shipping Type vs Revenue | Shipping Type, Revenue | High-value shipping preferences |
| Payment Method Analysis | Payment Method, Revenue | Popular payment modes |
| Discounts & Promo Codes | Discount Applied / Promo Used | Impact on revenue |
| Review Ratings Distribution | Review Rating | Customer satisfaction |
| Purchase Frequency Analysis | Frequency, Revenue | Behaviour patterns |
| Customer Loyalty | Previous Purchases vs Spend | Repeat customer value |

---

## 📊 5. Excel Dashboard
The dashboard includes:

- Slicers for dynamic filtering  
- PivotCharts for category, season, age, gender, shipping, payment, discount, and frequency  


Screenshots are available in the **/screenshots** folder.

---

##  ● Insights & Findings (Based on Dashboard)

### 1. **Clothing is the highest revenue-generating category**  
Clothing shows the largest revenue share compared to footwear, accessories, and outerwear.

### 2. **Summer season brings the most revenue**  
Customers spend more during summer, making it the peak season.

### 3. **Adult customers (26–50) are the main buyers**  
Adults contribute the highest revenue, followed by Seniors. Young buyers spend the least.

### 4. **Female customers spend more than male customers**  
Across all age groups, female customers consistently have higher purchase amounts.

### 5. **Free Shipping and Express Shipping generate higher revenue**  
Customers selecting these shipping options tend to spend more.

### 6. **Credit Card and PayPal payments drive the highest revenue**  
These methods show the largest purchase amounts.

### 7. **Purchases with NO discounts generate more revenue**  
Full-priced items contribute more to total revenue than discounted purchases.

### 8. **Customer reviews are generally positive (4–5 stars)**  
Most ratings fall between 3.5 and 4.5, showing high satisfaction.

### 9. **Monthly and Bi-Weekly buyers spend the most**  
These customers show strong retention and higher purchasing power.

### 10. **Repeat customers tend to spend more**  
A strong correlation exists between previous purchases and total spend.

---

## ⭐ 7. Five-Line Project Summary

- Clothing and Summer season generate the highest revenue.  
- Adults and Females form the core buying segment.  
- Free Shipping, Express Shipping, Credit Card, and PayPal show higher spending.  
- Customers give mostly positive reviews (4–5 stars).  
- Monthly and Bi-Weekly buyers contribute more revenue, showing strong loyalty.  

---

## 📂 8. Project Folder Structure

Amazon-Sales-Analysis-Excel-Dashboard
│
├── data
│ ├── amazon_sales_raw.csv
│ └── amazon_sales_cleaned.xlsx
│
├── excel-files
│ └── amazon_pivots.xlsx
│
├── dashboard
│ └── Amazon_Sales_Dashboard.xlsx
│
└── screenshots
└── dashboard_overview.png

yaml
Copy code

---

## 📝 9. How to Use This Project

1. Download the Excel Dashboard from `/Dashboard`.  
2. Open it in Microsoft Excel.  
3. Use the slicers to interact with customer segments.  
4. Explore PivotTables in `/Excel-file`.  
5. View raw and cleaned datasets in `/Data`.  

---

## 👨‍💻 10. About This Project

This project demonstrates practical **Excel data analytics** skills including:

- Data cleaning  
- Pivot-based analysis  
- Dashboard building  
- Insight generation  
- Consumer behaviour analysis  

Useful for data analyst portfolios, interviews, and recruiter visibility.
