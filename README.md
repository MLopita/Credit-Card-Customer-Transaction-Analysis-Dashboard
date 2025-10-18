# Credit Card Customer & Transaction Analysis Dashboard

## Project Overview
This project involves building **two interactive Power BI dashboards** to analyze credit card **customer profiles** and **transaction behavior**.  
It provides actionable insights into customer demographics, income levels, spending patterns, and credit usage trends.

The dashboards were designed as part of a Power BI analytics project to demonstrate data modeling, DAX calculations, and dashboard storytelling skills.


## Objectives
- To visualize **key customer metrics** such as demographics, income, and card usage.  
- To analyze **transaction trends** by expenditure type, week, and card category.  
- To enable interactive exploration through **filters and slicers** for:
  - Gender (Male / Female)
  - Age Group (18–25, 26–35, 36–45, 46–55, 56+)
  - Income Group (Low, Medium, High)
  - Card Category
  - Transaction Week
  - Expense Type  


## Datasets Used
1. **Customer Data** – Includes details such as:
   - Customer ID, Gender, Age, Income, Credit Score, Education, Job Type
   - Card details (Card Category, Credit Limit, Annual Fees)
2. **Transaction Data** – Contains:
   - Transaction Date, Amount, Category, Type (Swipe / Chip / Online), and linked Customer ID  


## Data Modeling & Transformations
- Merged customer and transaction datasets using **Customer_ID** as the primary key.
- Performed data cleaning and transformation in **Power Query**.
- Created calculated columns and measures using **DAX**, including:
  - `Age Group`
  - `Income Group`
  - `Total Revenue`
  - `Credit Usage %`
  - `Week Number`
  - `Current Week Revenue`
  - `Previous Week Revenue`
  - `WoW Growth %`

---

## Dashboards Created

### **Customer Analysis Dashboard**
**Purpose:** Understand customer distribution, income segmentation, and card preferences.

**Key Metrics:**
- Total Customers  
- Average Income  
- Active Card Holders  
- Average Credit Score  

**Key Visuals:**
- Total Customers by Age Group  
- Total Customers by Gender  
- Age Group & Gender Distribution  
- Average Income by Job Type  
- Average Credit Limit by Income Group  
- Total Customers by Card Category  
- Average Annual Fees by Gender  
- Total Customers by Education Level  

**Insights:**
- Majority of customers are aged **36–55**, with **females (58%)** dominating the user base.  
- **Blue cards** are the most common category among customers.  
- **Businessmen** and **White-collar** professionals earn the highest average income.  
- High-income customers enjoy **higher credit limits (~14K)**.

---

### **Credit Card Transaction & Revenue Dashboard**
**Purpose:** Analyze revenue generation, spending categories, and transaction frequency trends.

**Key Metrics:**
- Total Revenue: **45.52M**  
- Total Transactions: **0.67M**  
- Credit Usage %: **27.46%**  
- Week-over-Week Growth: **35.04%**

**Key Visuals:**
- Total Revenue by Month  
- Revenue by Expense Type  
- Transactions by Card Category  
- Transactions by Use Type (Swipe / Chip / Online)  
- Revenue Summary Table by Gender and Age Group  

**Insights:**
- **Blue Card** customers generate nearly **89%** of total transactions.  
- **Bills, Entertainment, and Fuel** are the top spending categories.  
- **Online transactions** are steadily increasing (~27% of total).  
- Male customers contribute slightly higher total revenue, while female customers have a higher **average income per transaction**.

## Tools & Technologies
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel** (for initial data formatting)
- **Data Modeling & Relationships**
- **Interactive Filters & Slicers**

## 🏁 Results & Learnings
- Built two fully interactive, visually clean Power BI dashboards.  
- Improved understanding of **data modeling**, **DAX**, and **Power BI storytelling**.  
- Learned how to create **insight-driven visuals** for business intelligence use cases.

## Author
**Lopita Mishra**  


## 📂 Repository Structure
