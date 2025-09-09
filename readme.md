# 🏈 Project: *“The I in Team” – NFL Top Offensive Players & Team Success*

## Overview
This project analyzes the top offensive NFL players (QB, RB, WR, TE) from the last 13 seasons (2012–2024) and explores how their performance correlates with team success.

## Data Preparation & Cleaning
- **Positions studied**: QB, RB, WR, TE  
- **Top players per season**: Top 3 in each position  
- **Timeframe**: Last 13 NFL seasons (~2012–2024)  
- **Metrics for ranking**:
  - Total touchdowns (rushing + receiving)  
  - Yards (Passing for QBs, Rushing for RBs, Receiving for WRs/TEs)  
  - Fantasy points (standard scoring)  

### Data Sources
- Kaggle datasets:  
  - [NFL Stats 2012–2024](https://www.kaggle.com/)  
  - [1926–2024 NFL Scores](https://www.kaggle.com/)  

---

## Tools & Methods
- **Python (Pandas)** – preprocessing & ranking top players  
- **Tableau** – interactive dashboards for playoff outcomes vs. player stats  
- **Jupyter Notebooks** – workflow documentation (`01_overview`, `02_eda`)  

---

## Key Deliverables
- Tableau dashboards (QB, RB, WR, TE, and summary)  
- KPIs:  
  - Cleaned datasets (top3_stats.pkl)
  - Jupyter notebooks for data prep and EDA
  - End-to-end project workflow demonstrating: data prep, KPI design, and dashboard building
  # Dashboards
    - [Position adjusted by Season&Stat Playoff Results](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/Adj_BarCharts)
    - [Pie Binary Playoff Results ](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/PlayoffPieCharts)
    - [QB Overview](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/QB-Overview)
    - [RB Overview](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/RB-Overview)
    - [WR Overview](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/WR-Overview)
    - [TE Overview](https://public.tableau.com/app/profile/philip.grossweiler/viz/NFL_Top3_Project/TE-Overview)

---

## Next Steps
- Add machine learning models to predict playoff outcomes 

Note: Raw weekly stats CSV files are not included due to GitHub file size limits. Zipped data available.

