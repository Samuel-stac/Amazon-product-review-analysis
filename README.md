# Amazon-product-review-analysis
This is my final project that i carried out to improve my skill in Data Analysis and the various tools that will be use during this process and to also secure my spot in the Data field


# 📊 Amazon Product Review Analysis — Excel Capstone Project

This project is part of my Data Analysis Capstone.  
It demonstrates my ability to clean raw data, build calculated columns, use Pivot Tables, analyze trends, and create a clear, actionable Dashboard — all using **Microsoft Excel**.

---

## 📌 **Project Overview**

The dataset contains Amazon product listings including:
- Product names
- Categories
- Selling prices
- Discount %
- Ratings
- Number of reviews

The goal is to transform raw, messy data into clear insights about:
- Product pricing strategies
- Customer feedback patterns
- Revenue opportunities

---

## ✅ **Key Steps**

**1️⃣ Data Cleaning**
- Removed duplicates  
- Standardized text (uppercase for product IDs, consistent case for categories)
- Rounded inconsistent rating values to one decimal place
- Used Excel formulas to calculate new fields

---

**2️⃣ Key Calculated Columns**

- **Estimated Price (Original Price)**  
  *Formula:*

=IF([@[Estimated Price]] < 500, "<₹500",
IF([@[Estimated Price]] <= 1500, "₹500–₹1,500",
IF([@[Estimated Price]] <= 5000, "₹1,500–₹5,000",
">₹5,000")))

*Explanation:* Groups products into practical price bands.

- **Combined Score**  
*Formula:*  
Combined Score = Average Rating × Rating Count

*Explanation:* Ranks products by popularity and quality combined.

*CountIF*

---

## 📊 **Analysis & Questions Answered**

Below are the key business questions I answered using Pivot Tables, helper columns, and charts:

1️⃣ **Average Discount % by Category**  
 - *Insight:* Fashion has the highest average discounts.

2️⃣ **Number of Products per Category**  
 - *Insight:* Electronics and Home categories have the widest product variety.

3️⃣ **Total Reviews per Category**  
 - *Insight:* Electronics leads in total customer engagement.

4️⃣ **Products with Highest Average Ratings**  
 - *Insight:* Premium accessories and branded gadgets score the highest.

5️⃣ **Average Original Price vs Discounted Price by Category**  
 - *Insight:* Original prices are often 2–3x the discounted selling price, especially in Fashion.

6️⃣ **Products with Highest Number of Reviews**  
 - *Insight:* Popular gadgets and budget-friendly items attract massive review counts.

7️⃣ **How many products have a discount of 50% or more?**  
 - *Result:* 746 products (approx. 51%) offer deep discounts.

8️⃣ **Distribution of Product Ratings**  
 - *Insight:* Most products cluster around 4.0–4.5 star range.

9️⃣ **Total Potential Revenue by Category**  
 - *Insight:* Electronics category shows the highest potential revenue opportunity.

10️⃣ **Number of Unique Products per Price Bucket**  
  - *Insight:* Majority of products fall in the ₹500–₹1,500 range.

11️⃣ **Relationship between Rating and Discount**  
  - *Insight:* Scatter plot shows no strong direct relationship — high discounts don’t always mean higher ratings.

12️⃣ **How many products have fewer than 1,000 reviews?**  
  - *Result:* 520 products have low review counts, showing room for marketing push.

13️⃣ **Categories with Highest Discounts**  
  - *Insight:* Fashion and Accessories show the largest average discounts.

14️⃣ **Top 5 Products by Combined Rating & Reviews**  
  - *Insight:* These products are the biggest drivers of customer trust and brand visibility.

---

## 📊 **Key Visuals**

The Dashboard includes:
- Clustered bar charts for category-level insights
- Column charts for price buckets and rating distribution
- Scatter plot for rating vs discount trends
- KPI Cards for single key numbers (50%+ discount count, products with <1,000 reviews)
- Top 5 Products table/bar

---

## ⚙️ **Excel Features Used**

- Data cleaning: Remove Duplicates, Text Standardization, TRIM, UPPER, PROPER functions
- Calculated Columns: IF, VALUE, ROUND, and custom formulas
- Pivot Tables: Count, Sum, Average calculations
- Pivot Charts: Bar, Column, Scatter, Pie
- Slicers for category filtering (optional)
- KPI Cards using shapes and text boxes

---

## 📌 **Key Insights**

✅ Fashion is aggressively discounted, likely to boost seasonal sales.  
✅ Electronics generates the highest total potential revenue and reviews — a high-trust category.  
✅ Over 50% of products have discounts over 50% — showing price competition is intense.  
✅ Most products sit in the affordable mid-range — ₹500–₹1,500.  
✅ Products with fewer reviews are opportunities for better marketing and promotions.

---

## 📌 **Key Insights Summary**

| # | Question | Key Insight |
|---|-------------------------------|----------------------------------------------------------------|
| 1 | Average Discount % by Category | Fashion has the highest average discounts. |
| 2 | Number of Products per Category | Electronics and Home categories have the widest variety of products. |
| 3 | Total Reviews per Category | Electronics leads in total customer engagement. |
| 4 | Products with Highest Avg. Ratings | Premium accessories and branded gadgets have the best ratings. |
| 5 | Avg. Original Price vs Discounted Price | Original prices are often 2–3× the discounted selling price. |
| 6 | Products with Highest Number of Reviews | Popular gadgets and budget-friendly items get the most reviews. |
| 7 | Products with 50%+ Discount | 746 products (about 51%) offer deep discounts. |
| 8 | Distribution of Product Ratings | Most products are rated between 4.0–4.5 stars. |
| 9 | Total Potential Revenue by Category | Electronics has the highest potential revenue opportunity. |
| 10 | Products per Price Bucket | Majority of products fall in the ₹500–₹1,500 range. |
| 11 | Rating vs Discount Relationship | No strong direct link — high discounts don’t guarantee higher ratings. |
| 12 | Products with <1,000 Reviews | 520 products have low review counts, showing marketing opportunity. |
| 13 | Categories with Highest Discounts | Fashion and Accessories show the largest average discounts. |
| 14 | Top 5 Products by Combined Score | These products drive trust & strong brand visibility. |

## 📁 **Files**

[Amazon  Excel Project.xlsx](https://github.com/user-attachments/files/21052046/Amazon.Excel.Project.xlsx)

<img width="923" alt="Excel project" src="https://github.com/user-attachments/assets/7541ae4d-cd95-490d-82ef-3e140d07450d" />
![Raw data ](https://github.com/user-attachments/assets/96845c11-12fb-4f9b-b0ca-eace9254da38)
![Pivot table 2](https://github.com/user-attachments/assets/74ebc9dc-3e78-4272-bfce-6ed4b42d0)
![Pivot table 1](https://github.com/user-attachments/assets/b52aa914-7b2d-4a7b-a893-e14e6397900c)
419)





