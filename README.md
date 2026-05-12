# 🛍️ Vrinda Store Annual Sales Analysis — 2022

An end-to-end data analysis project on Vrinda Store's 2022 sales data using Microsoft Excel.

---

## 📌 Objective

To analyze Vrinda Store's annual sales data for 2022 and generate insights that help the store understand its customers better and grow sales in 2023.

---

## 🗂️ Dataset Overview

| Detail | Info |
|---|---|
| **Store** | Vrinda Store |
| **Year** | 2022 |
| **Total Orders** | 28,663 |
| **Total Revenue** | ₹1,95,54,344 |
| **Total Columns** | 21 |
| **Tool Used** | Microsoft Excel |

### Columns in Raw Data
`Order ID` | `Customer ID` | `Gender` | `Age` | `Age Group` | `Date` | `Month` | `Status` | `Channel` | `SKU` | `Category` | `Size` | `Quantity` | `Currency` | `Amount` | `Ship City` | `Ship State` | `Ship Postal Code` | `Ship Country` | `B2B`

---

## 🔄 Process

### 1. 🧹 Data Cleaning
- Removed duplicate records
- Fixed inconsistent gender entries (e.g. "women", "W" → "Women")
- Handled null and missing values
- Corrected data types for date and amount columns

### 2. ⚙️ Data Processing
- Created `Age Group` column (Teenager / Adult / Senior) from Age
- Extracted `Month` from Date column for time-based analysis
- Added calculated fields for better segmentation

### 3. 📊 Data Analysis
- Used Pivot Tables to summarize sales by month, gender, state, age group, and channel
- Compared order count vs. revenue trends across months
- Analyzed order delivery status distribution

### 4. 📈 Data Visualization
- Monthly Sales vs. Orders
- Sales by Gender
- Order Status Distribution
- Top 5 States by Sales
- Sales by Age Group & Gender
- Sales by Channel
- Interactive Dashboard with Slicers

---

## 💡 Key Insights

### Sales vs Orders by Month
| Month | Orders | Revenue (₹) |
|---|---|---|
| January | 2,702 | 18,20,601 |
| February | 2,750 | 18,75,932 |
| **March** | **2,819** | **19,28,066** |
| April | 2,685 | 18,29,263 |
| May | 2,617 | 17,97,822 |
| June | 2,597 | 17,50,966 |
| July | 2,579 | 17,72,300 |
| August | 2,617 | 18,08,505 |
| September | 2,490 | 16,88,871 |
| October | 2,424 | 16,66,662 |
| November | 2,383 | 16,15,356 |

> March recorded the highest sales and orders of the year.

---

### Sales by Gender
| Gender | Revenue (₹) | Share |
|---|---|---|
| Women | 1,25,20,788 | ~64% |
| Men | 70,33,556 | ~36% |

> Women contribute nearly 2/3rd of total revenue.

---

### Order Status
| Status | Count |
|---|---|
| ✅ Delivered | 26,476 (~92%) |
| ❌ Cancelled | 793 |
| 🔄 Returned | 911 |
| 💰 Refunded | 483 |

> 92% of orders were successfully delivered.

---

### Top 5 States by Sales
| State | Revenue (₹) |
|---|---|
| Maharashtra | 27,53,533 |
| Karnataka | 24,31,676 |
| Uttar Pradesh | 19,37,621 |
| Telangana | 15,72,664 |
| Tamil Nadu | 15,53,483 |

> Maharashtra, Karnataka, and Uttar Pradesh together contribute ~35% of total sales.

---

### Sales by Channel
| Channel | Orders | Share |
|---|---|---|
| Amazon | 10,259 | 35.8% |
| Myntra | 6,647 | 23.2% |
| Flipkart | 6,155 | 21.5% |
| Ajio | 1,784 | 6.2% |
| Nalli | 1,370 | 4.8% |
| Meesho | 1,283 | 4.5% |
| Others | 1,165 | 4.1% |

> Amazon, Myntra, and Flipkart together drive ~80% of all orders.

---

### Sales by Age Group
| Age Group | Contribution |
|---|---|
| Adult (30–49 yrs) | ~50% |
| Teenager (18–29 yrs) | ~30% |
| Senior (50+ yrs) | ~20% |

> Adult women aged 30–49 are the biggest buyers.

---

## ✅ Conclusion

**Target:** Women aged **30–49 years** in **Maharashtra, Karnataka, and Uttar Pradesh**

**Strategy:** Run targeted ads, offers, and coupons on **Amazon, Flipkart, and Myntra** to reach this customer segment, which drives the maximum sales for Vrinda Store.

---

## 📁 Files

| File | Description |
|---|---|
| `Raw_Data/Vrinda_Store_Raw_Data.xlsx` | Original unprocessed sales data |
| `Report/Vrinda_Store_Sales_Report_2022.pdf` | Final analysis report with dashboard |
