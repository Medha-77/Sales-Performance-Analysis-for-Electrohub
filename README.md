
# 📊 Electrohub Sales Data Analysis - Power BI Dashboard  

## 📌 Overview  
This project provides an **interactive Power BI dashboard** for analyzing sales data of **Electrohub**, a fictional electronics retailer. 🛒 The dashboard delivers **actionable insights** into sales performance, product trends, customer behavior, and promotion effectiveness. By **visualizing key metrics** and enabling **dynamic exploration**, Electrohub can make **data-driven decisions** to **optimize business strategies** and **drive growth**. 📈  

---

## ❓ Problem Statement  
Electrohub needs **deeper insights** into its sales data to **optimize business strategies** and **achieve sustainable growth**. 🏆 This dashboard addresses key business questions such as:  

✅ **Top/Bottom 5 Products by Sales/Profit/Quantity Sold.**  
✅ **How do sales trends vary over time?** (Daily, Monthly, Quarterly, Annually) 📅  
✅ **Relationship between Sales & Profit.** 💰  
✅ **Compare Sales/Profit/Quantity Sold between two periods selected by the user.**  
✅ **Average discount offered in each discount category.** 🎯  
✅ **Total number of orders.** 📦  
✅ **Show Sales, Profit, Discount, Net Sales, and all other fields per order with filters.**   
✅ **Sales breakdown by different cities.** 🏙️  

By answering these questions, Electrohub can **identify opportunities**, **capitalize on winning strategies**, and **enhance profitability** in the **competitive electronics retail market**. 🚀  

---

## 🔍 Steps Followed  

The development of this **Power BI dashboard** involved the following key steps:  

### 🗂 1. Data Acquisition  
📥 Extracted **sales data** from Electrohub’s **data sources**.  

### 🔄 2. Data Transformation & Cleaning (Power Query)  
🧹 Used **Power Query** to **clean**, **transform**, and **prepare data** for analysis:  
- Removed **duplicates** & handled **missing values**.  
- Ensured **data consistency** & accuracy.  

### 🔗 3. Data Modeling (Power BI Desktop)  
📊 Designed a **star schema model**, linking **fact tables** with **dimension tables** for efficient analysis.  
![Image](https://github.com/user-attachments/assets/433665f6-7046-4160-b922-6a2a5bf235b5)  

### ✍️ 4. DAX Measure Creation  
🧠 Developed **DAX measures** for key performance indicators (**KPIs**):  
- **Total Revenue**  
- **Profit & Profit Margin**  
- **Year-over-Year (YOY) Growth** 📈  

### 🎨 5. Dashboard Design & Visualization  
💡 Created an **intuitive, interactive dashboard** with **Power BI’s visualization tools**.  

### 🎛️ 6. Interactive Features Configuration  
📌 Implemented **slicers & cross-filtering** to enhance **user experience**.  

### 🛠️ 7. Testing and Refinement  
✅ Conducted **thorough testing** for accuracy, performance, and usability.  
✅ Made **iterative refinements** based on feedback.  

---

## 📊 Dashboard Components  

### 1️⃣ **Overview**  
![Image](https://github.com/user-attachments/assets/13424651-feca-4ada-9b0d-128beaa2fc67)  
📍 **Summary of key business metrics** like:  
- **Total Revenue**  
- **Units Sold**  
- **Year-over-Year Growth** 📊  

### 2️⃣ **TOP/BOTTOM ANALYSIS**  
![Image](https://github.com/user-attachments/assets/74fb6b76-9176-44ee-aaa9-3e2568c27735)  
📍 Identifies the **Top 10 & Bottom 10 performing products** based on **Revenue & Profit Margin**. 🛒  

### 3️⃣ **Comparison: Sales, Profit & Quantity Sold**  
![Image](https://github.com/user-attachments/assets/b8609170-c9f3-468a-8928-7bcc9ed6a4c9)  
📍 Compares **Sales, Profit & Order Quantity** across different **Regions & Product Categories**. 🌍  

### 4️⃣ **Edit Interactions**  
![Image](https://github.com/user-attachments/assets/71160cbd-0576-4613-8209-d2bcba11c543)  
📍 **Cross-filtering visuals**: Selecting data in one chart updates all related visuals.  

### 5️⃣ **Table-Visual**  
![Image](https://github.com/user-attachments/assets/6cd02777-7156-4411-b3c4-f489b5c4feee)  
📍 **Detailed table view** with slicers for:  
- **Date** 📅  
- **Customer Name** 👤  
- **Product Name** 🏷️  
- **Promotion Name** 🎉  

---

## 🛠️ Technologies/Tools Used  
🖥️ **Power BI Desktop** – For **data modeling, visualization, and dashboard design**.  
🔍 **Power Query Editor** – For **data cleaning and transformation**.  
📂 **GitHub** – For **version control & project hosting**.  

---

## 📥 How to Use  

📌 **Step 1: Download Data & `.pbix` file**  
🔗 **Download the Excel Data**: [`Store Data.xlsx`](https://github.com/Medha-77/Sales-Performance-Analysis-for-Electrohub/blob/main/Store%2BData.xlsx)  
🔗 **Download the Power BI Report**: [`Electrohub.pbix`](https://github.com/Medha-77/Sales-Performance-Analysis-for-Electrohub/blob/main/Electrohub.pbix)  

📌 **Step 2: Open in Power BI Desktop**  
🖥️ **Ensure you have Power BI Desktop installed** before opening the `.pbix` file.  

📌 **Step 3: Explore the Dashboard**  
📊 Navigate through pages like **Overview, Top/Bottom Analysis, and Comparison** using the bottom tabs.  

📌 **Step 4: Interact with Visuals**  
🎛️ Use **slicers** to filter data by **Date, Customer, Product, or Promotion** and explore insights dynamically.  

---

## 🚀 Conclusion & Next Steps  
🔹 This **interactive Power BI dashboard** empowers Electrohub to **analyze sales trends, identify opportunities, and enhance profitability**. 💡  
🔹 **Next Steps**:  
- Integrate **live data sources** for real-time analysis.  
- Implement **predictive analytics** for demand forecasting. 📈  
- Automate **data refreshes** for up-to-date insights.  

---

