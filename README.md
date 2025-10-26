

## 📘 Project Overview
The **Supermarket Sales Dashboard** is an interactive Power BI report designed to analyze and visualize supermarket transaction data.  
It helps monitor **sales performance, profit trends, customer behavior, and product line analysis** across multiple branches.

This project demonstrates data transformation, modeling, and visualization using **Power BI Desktop**.

---

## 📊 Key Features
- 📆 **Time-based analysis** — View total sales and gross income by **month and year**.  
- 🏪 **Branch comparison** — Compare sales performance across supermarket branches.  
- 👥 **Customer insights** — Analyze data by **gender, customer type**, and **payment method**.  
- 🧾 **Product line performance** — Discover best-selling product categories.  
- 💰 **KPIs** — Total Sales, Gross Income, Average Rating, and Profit Margin.  
- 🎯 **Interactive filters** — Slicers for City, Branch, Gender, Date, and Payment Type.  
- 📈 **Dynamic visuals** — Bar charts, pie charts, cards, and trend lines.  

---

## 🧮 Techniques Used
- **Power Query Editor** for cleaning and transforming raw data.  
- **DAX (Data Analysis Expressions)** for calculated columns and measures:
  - `Total Sales = SUMX(Sales, Sales[Unit price] * Sales[Quantity])`
  - `Month Year = FORMAT(Sales[Date], "MMM YYYY")`
- **Data modeling** to connect fact and dimension tables.  
- **Custom formatting** for a professional dashboard layout.  
- **Drill-through pages** for deeper insights.  

---

## 🧰 Tools & Technologies
- 🧠 **Power BI Desktop**  
- 📊 **Excel / CSV Dataset** (Supermarket Sales Data)  
- 🧾 **DAX Functions:** `SUMX()`, `CALCULATE()`, `FILTER()`, `FORMAT()`, `YEAR()`, `MONTH()`  

---

## 📂 Dataset Details
The dataset includes transaction-level supermarket data with the following fields:

| Column | Description |
|--------|--------------|
| Invoice ID | Unique ID for each transaction |
| Branch | Store branch (A, B, C) |
| City | Location of the branch |
| Customer Type | Member / Normal |
| Gender | Male / Female |
| Product Line | Product category |
| Unit Price | Price per item |
| Quantity | Number of units sold |
| Total | Total amount (Unit Price × Quantity) |
| Tax | 5% VAT |
| Gross Income | Profit from each transaction |
| Date | Purchase date |
| Time | Purchase time |
| Payment | Payment method |
| Rating | Customer rating (1–10) |

---

## 🚀 Insights Gained
- 🏆 **Branch A** achieved the highest total sales.  
- 👩‍🦰 **Female customers** contributed slightly more revenue than male customers.  
- 💳 **E-wallet** was the most preferred payment method.  
- 🍔 **Food and Beverages** was the top-performing product line.  
- 🌆 **Evening hours** showed peak sales activity.  

---

## 📸 Dashboard Preview


<img width="604" height="343" alt="supermarket" src="https://github.com/user-attachments/assets/8338f1fb-45c3-4b32-a1cc-c435487cc5cd" />
<img width="1920" height="1080" alt="image 7" src="https://github.com/user-attachments/assets/d9e1e1ce-8136-4300-9489-7d97d4d09db5" />
<img width="1920" height="1080" alt="image 6" src="https://github.com/user-attachments/assets/595e123f-9e91-4b49-8eaa-55f59b30dd52" />
<img width="1920" height="1080" alt="image 3" src="https://github.com/user-attachments/assets/a618e54e-0fdc-4ee3-b167-13a3d0b627d3" />




---

## 🧩 How to Use
1. Download the `.pbix` file from this repository.  
2. Open it in **Power BI Desktop**.  
3. Interact with filters and visuals to explore insights.  

---

## 👨‍💻 Author
**Your Name**  

💼 *Power BI | Data Analyst | Business Intelligence Enthusiast*  

---

⭐ **If you found this project useful, consider giving it a star on GitHub!**
