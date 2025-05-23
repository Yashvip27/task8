# 📊 Task 8: Simple Sales Dashboard – Superstore Sales

## 🎯 Objective  
Design an *interactive sales dashboard* in *Power BI* to visualize performance by *Product Category, **Region, and **Month-Year*.

---

## 🗂 Dataset Used  
*Filename:* Superstore_Sales.csv  
*Relevant Columns:*
- Order Date – Date of Purchase  
- Region – Sales Region  
- Category – Product Category  
- Sales – Revenue Generated  
- Profit – Profit Earned

---

## 🛠 Tools & Technologies  
- *Power BI Desktop*  
- *Power Query Editor* for data cleaning and transformation

---

## 🔧 Data Preparation Steps (Power Query)  
1. *Filtered columns* to retain only:
   - Order Date, Region, Category, Sales, Profit
2. **Converted Order Date** to the correct Date data type.  
3. **Created a custom Month-Year column** using DAX:
   DAX
   Month-Year = FORMAT([Order Date], "MMM YYYY")
   
4. *Verified data types* for all columns:
   - Order Date → Date  
   - Sales, Profit → Decimal Number  
   - Region, Category, Month-Year → Text

---

## 📊 Dashboard Components  
- *Line Chart:* Sales over Month-Year  
- *Bar Chart:* Sales by Region  
- *Donut Chart:* Sales by Category  
- *Slicers (Filters):* Region, Year  

---

## 📈 Key Insights  
- 🏆 The *West region* consistently outperformed others in monthly sales.  
- 🖥 *Technology* was the top-performing category in terms of overall revenue.  
- 📅 *Q4* showed a notable sales spike, likely driven by the holiday season.  
- 🌍 The *South region* had lower sales, suggesting potential for strategic growth.

---

## 📦 Deliverables 
- ✅ The Sales Story Summary (ppt)
- ✅ Cleaned dataset (Superstore_Sales.csv)  
- ✅ Power BI dashboard file (.pbix)  
- ✅ Dashboard screenshot  
- ✅ This README.md file

---

## 📝 Dashboard Title  
*"The Sales Story: A Regional & Category View"*
