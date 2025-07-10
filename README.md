# 🏏 India vs South Africa Cricket Dashboard | Power BI Project

This project analyzes cricket performance statistics of India and South Africa using live data scraped via Power BI’s Web Connector from [ESPN Cricinfo](https://www.espncricinfo.com).

## 📊 Project Highlights

- Pulled **Batting, Bowling, and Fielding stats** from Cricinfo using **Power BI’s Web data import** feature.
- Cleaned raw tables using **Power Query** (removed junk rows, promoted headers, parsed numbers).
- Categorized players based on Strike Rate (0–200) into "Very Low" to "Explosive".
- Used **DAX** to:
  - Rank players (`RANKX`)
  - Define conditional columns for category
  - Create KPIs for runs, wickets, average, economy
- Designed interactive dashboard using:
  - **Bar charts** for player stats
  - **Donut/pie charts** for category roles
  - **Card KPIs** and slicers for Team/Role filters

## 📁 Folder Structure
📂 cricket-powerbi-dashboard/
├── 📊 Cricket.pbix
├── 📎 Data Summary.xlsx
└── 📄 README.md

## 🛠 Tools Used

- Power BI (Power Query, DAX, Visualizations)
- Web Data Connector
- ESPN Cricinfo (Data Source)

## ✅ Insights Delivered

- Ranked top batsmen and bowlers by SR and wickets
- Highlighted differences between India and South Africa player roles
- Strike rate vs performance impact across categories

## 📌 How to Use

1. Open `Cricket.pbix` in Power BI Desktop.
2. Refresh data to pull latest from ESPN Cricinfo.
3. Use filters to explore performance by team, category, or player.

   


