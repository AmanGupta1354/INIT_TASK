# INIT_TASK

**Aman Gupta**

---

##  Project Overview
This project performs **exploratory data analysis (EDA)** and **customer segmentation** using transactional, customer, and product datasets.  
It includes data cleaning, transformation, aggregation, and business insights such as monthly revenue trends, top-performing products, and customer RFM segmentation.

---

##  Key Steps

### **Part A: Data Loading & Exploration**
- Loaded three datasets (Transactions, Customers, Products)
- Checked data types, missing values, duplicates, and date range

### **Part B: Data Preprocessing**
- Converted timestamps to datetime format  
- Extracted hour, day, and month  
- Handled missing values  
  - Numeric → filled with **median**  
  - Categorical → filled with **mode**

### **Part C: Analysis**
- **C1:** Merged all datasets into a single `full_data` dataframe  
- **C2:** Time-based analysis — monthly revenue, unique customers, order value, MoM growth  
- **C3:** Product performance — Top 10 by revenue, quantity sold, and profit margin  
- **C4:** Customer segmentation using **RFM (Recency, Frequency, Monetary)**  
  - Binned each metric into **Low / Medium / High**  
  - Assigned descriptive customer segments

 ##  Dependencies

| Library | Purpose |
|----------|----------|
| `pandas` | Data manipulation and analysis |
| `numpy` | Numerical operations |
