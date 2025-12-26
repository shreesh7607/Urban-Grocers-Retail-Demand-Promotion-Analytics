# Urban Grocers Retail Demand & Promotion Analytics (Analytica Case Study)

This repository contains the complete analysis and deliverables for the **Analytica - Data Analysis Case Study** with **Urban Grocers Pvt. Ltd.**, a fast growing supermarket chain based in Hyderabad.  
The objective is to analyse transaction level retail data, uncover demand patterns, evaluate promotional effectiveness, and build a baseline demand forecast for operational planning.

---

## Project Overview

- Analysed **240,000 transaction level rows (2023-2024)** across 4 stores and 5 major categories:
  - Bread  
  - Milk  
  - Fruits  
  - Vegetables  
  - Meat  
- Performed extensive data cleaning, feature engineering, and exploratory analysis in `analytica.ipynb`.
- Engineered features including:
  - Sales  
  - Profit  
  - Month  
  - DayType (Weekend/Holiday/Weekday)  
- Conducted analyses on:
  - Seasonal trends  
  - Promotion impact  
  - Holiday/weekend effects  
  - Store level volatility  
- Built a **30 day moving average forecasting model** for Milk category demand for the next quarter.

---

## Key Analyses & Insights

### **1. Sales Trends**
- Monthly sales exhibit clear seasonality with **mid year peaks** and a gentle decline toward year end.
- Indicates the need for **season aware pricing, replenishment, and stocking decisions**.

### **2. Holiday & Weekend Impact**
- Holidays and weekends show a slight **increase in units sold**, particularly for:
  - Bread  
  - Meat  
- Suggests value in **targeted stocking and staff planning** during these high footfall periods.

### **3. Promotions**
- Promotions improve average units sold by only **~0.04 units per transaction**.
- Indicates **low ROI** for blanket discounting.
- Recommends shifting toward **targeted, data driven promotional strategies**.

### **4. Store Level Volatility**
- Average sales across the four stores are similar, but:
  - **Store A** has the **highest demand volatility** (largest coefficient of variation).
- Calls for **tighter forecasting, safety stock, and operational buffers**.

### **5. Demand Patterns**
- Units per transaction remain **highly stable** across stores and categories.
- Small variations exist by store category combinations but do not significantly impact overall patterns.

### **6. Forecasting**
- A **30 day moving average model** delivers a smooth, stable daily demand forecast for Milk.
- Suitable as a **baseline inventory planning tool** for the next 90 days.

---
