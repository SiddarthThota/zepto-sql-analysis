# 🛒 Zepto SQL Data Analysis Project

## 📌 Objective

This project analyzes product-level data from Zepto to uncover insights related to pricing, discounts, inventory, and category performance.

---

## 🧱 Dataset Overview

The dataset contains:

* Product name and category
* MRP and discounted price
* Discount percentage
* Stock availability
* Product weight

---

## 🔍 Key Steps Performed

### 1. Data Exploration

* Checked total number of rows
* Identified NULL values
* Explored distinct product categories

### 2. Data Cleaning

* Removed products with zero price
* Converted price from paise to rupees

### 3. Data Analysis

* Top 10 products with highest discounts
* High MRP products that are out of stock
* Revenue estimation by category
* Products with low discount but high price
* Categories with highest average discounts
* Price per gram analysis
* Product grouping by weight (Low, Medium, Bulk)
* Total inventory weight per category

---

## 📊 Key Insights

* Certain categories contribute more to total revenue
* High discount does not always mean better value
* Inventory distribution varies significantly across categories

---

## 🛠 Tools Used

* MySQL Workbench
* SQL

---

## 📁 Project Files

* `zepto_analysis.sql` → All queries (cleaned & structured)

---

## 🚀 How to Run

1. Create the table using the provided SQL script
2. Import your dataset
3. Run queries step-by-step

---

## 👨‍💻 Author

SIDDARTH THOTA.
