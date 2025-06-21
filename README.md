## 📊 Online Retail Sales Dashboard (Dec 2010 – Dec 2011)

This project analyzes online retail transactions from Dec 2010 to Dec 2011 using **Python** for data cleaning and **Power BI** for building a professional dashboard that provides key business insights.

---

### 📁 Project Structure

```
Online-Retail-Dashboard/
│
├── data/
│   └── online_retail_raw.csv         # Original dataset
│   └── online_retail_cleaned.xlsx    # Cleaned dataset used in Power BI
│
├── notebooks/
│   └── clean_data.ipynb              # Python cleaning script
│
├── dashboard/
│   └── Online_Retail_Dashboard.pbix  # Power BI Dashboard file
│   └── dashboard_screenshot.png      # Dashboard preview image
│
└── README.md
```

---

### 🧰 Tools & Technologies

* **Python** (Pandas, Datetime)
* **Power BI** (Interactive Visualizations, DAX)
* **Excel** (Formatting support)

---

### 📌 Objectives

* Clean and prepare the online retail dataset
* Create interactive visuals to analyze:

  * Sales over time
  * Best-selling products
  * Sales by country
* Provide slicers to explore trends across dimensions

---

### 📂 Dataset

* Source: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
* Features include: `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `UnitPrice`, `CustomerID`, `Country`, `InvoiceDate`

---

### 🧹 Data Cleaning (Python)

Key steps performed in `clean_data.ipynb`:

* Removed cancelled orders (`InvoiceNo` starting with "C")
* Removed missing `CustomerID` and negative values
* Created new features: `TotalSales`, `Date`, `Time`, `MonthYear`
* Saved cleaned data to `.xlsx` for Power BI

---

### 📈 Power BI Dashboard Features

* **Line Chart**: Monthly Sales Trend
* **Donut Chart**: Total Sales by Country
* **Bar Chart**: Top 10 Products by Revenue
* **KPIs**: Total Sales, Total Customers, Total Quantity
* **Slicers**: Country, Month-Year

---

### 📷 Dashboard Preview

(![Screenshot 2025-06-21 110834](https://github.com/user-attachments/assets/a678494b-d22b-4f69-aa22-5d9742cd87c9))

---

### 🔍 Key Insights

* 🇬🇧 UK contributed over **84%** of total revenue
* 🛍️ **Top Products** include Paper Craft, Cake Stand, Hanging Heart
* 📈 Highest revenue in **November 2011**

---

### 🧑‍💼 About Me

**Nilesh Sadhu**
Aspiring Data Analyst | Python & Power BI Enthusiast
📫 [Connect on LinkedIn](https://www.linkedin.com/in/nileshsadhu)

---

### 🗂️ License

This project is for educational and portfolio purposes only.
