# 🎮 Global Video Game Sales Analysis Dashboard

An interactive **Power BI project** analyzing **global video game sales data** from 1980–2020, providing insights into platform performance, genre trends, publisher dominance, and market forecasts.  
This project demonstrates **data modeling, DAX measures, visualization design, and storytelling** using Power BI.

---

## 💡 Project Objective

To design a **three-page interactive dashboard** that reveals insights about the gaming industry through:
- **Descriptive Analysis** – understanding total and regional sales.
- **Diagnostic Analysis** – identifying which platforms, publishers, and genres drove performance.
- **Predictive Analysis** – forecasting future trends in the gaming market.

---

## 🧠 Key Features

🔹 **Cleaned and Transformed Dataset**
- Converted Year column to Whole Number for accurate time intelligence.
- Built a `DimYear` table to support DAX-based time calculations.

🔹 **Data Modeling**
- Star Schema: `vgsales` (fact table) linked to `DimYear`.

🔹 **DAX Measures Created**
- Total Global, Regional, and Platform Sales  
- Year-over-Year (YoY) Growth and Percentage  
- Cumulative and Rolling 3-Year Averages  
- Forecast and Trend Analytics

🔹 **Dashboard Pages**
1. **Global Overview** – KPIs, Total Sales, and Regional Breakdown.  
2. **Platform & Genre Analysis** – Performance comparison by platform, publisher, and genre.  
3. **Trends & Forecasts** – Yearly trends, rolling averages, and predictive forecasting.

🔹 **Custom Visualization Theme**
- Applied a **neon gaming theme (JSON)** with dark gradients for a futuristic aesthetic.  
- Interactive slicers linked by `Year`, `Platform`, and `Genre`.

---

## 📊 Insights & Impact

✅ **PlayStation 2** emerged as the most successful platform globally.  
✅ **Action** and **Sports** genres dominated the global gaming market.  
✅ **2008–2010** marked the industry’s revenue peak.  
✅ Forecasts indicate stable growth in upcoming years.  
✅ Improved storytelling through advanced DAX and visualization.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Power BI** | Data visualization and dashboard design |
| **Power Query Editor** | Data cleaning and transformation |
| **DAX** | Time intelligence and calculated measures |
| **JSON Theme** | Custom UI styling |
| **GitHub** | Project version control and documentation |

---

🎮 Global-Video-Game-Sales-Analysis-Dashboard/
│
├── 📁 Data/
│   └── [vgsales.csv](https://github.com/user-attachments/files/23319401/vgsales.csv)
│
├── 📁 Theme/
│   └── [gaming_theme_fixed.json](https://github.com/user-attachments/files/23319405/gaming_theme_fixed.json)
│
├── 📁 Dashboard_Screenshots/
│   ├── <img width="1155" height="653" alt="Page1_GlobalOverview" src="https://github.com/user-attachments/assets/a3c392e3-9e06-4594-b787-8eead1f0793c" />
│   ├── <img width="1149" height="647" alt="Page2_PlatformGenreAnalysis" src="https://github.com/user-attachments/assets/d239813d-e888-4923-82c9-1e41517fd6ed" />
│   └── <img width="1151" height="644" alt="Page3_TrendsForecasts" src="https://github.com/user-attachments/assets/32280435-9dcc-413d-aad6-ebd6454a3a4b" />
│
├── 📁 Report/
│   ├── Video_Game_Sales_Analysis_Dashboard.pbix
│   └── README_Project_Report.pdf   (optional)
│
└── 📄 README.md





