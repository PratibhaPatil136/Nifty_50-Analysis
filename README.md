# 📊 NIFTY-50 Stock Market Dashboard (2000–2021)

This Power BI dashboard provides an insightful analysis of the NIFTY-50 stock market from 2000 to 2021, covering stock trends, sector-wise performance, and company-level financial metrics. The dashboard is designed to assist analysts, investors, and stakeholders in making informed decisions.

---

## 📁 Dataset
- Source: [Kaggle – NIFTY-50 Stock Market Data (2000–2021)](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data)
- Total CSV files: 52 (each representing one stock)
- Additional Data: Stock metadata and combined NIFTY-50_all.csv

---

## 📌 Dashboard Pages

### 📍 1. **Overview**
- **Goal**: Present overall trends across all stocks in the NIFTY-50.
- **KPIs**:
  - Total Stocks Tracked
  - Average Close Price
  - Average Volume
  - Top 5 Stocks by Volume and Close Price
- **Visuals**:
  - Line chart of price trends
  - Treemap by stock
  - Slicers by Date, Company, and Industry

---

### 📍 2. **Company Performance Insights**
- **Goal**: Deep dive into company-specific stock behavior and comparison.
- **KPIs**:
  - Highest Closing Price
  - Maximum Turnover
  - Highest Deliverable %
- **Visuals**:
  - Bar chart for closing prices by company
  - Line chart of price movement over time
  - Matrix showing delivery % by company
  - Slicers: Date, Industry, Company Name

---

### 📍 3. **Sector Performance Overview**
- **Goal**: Compare key metrics across industries.
- **KPIs**:
  - Average Deliverable %
  - Average Closing Price
  - Average Trading Volume
- **Visuals**:
  - Table with sector-level KPIs
  - Sector comparison bar charts
  - Pie chart for sector-wise distribution
  - Slicers: Industry, Date

---

## 🧰 Tools Used
- **Power BI Desktop**
- **DAX**
- **Excel**
- **Kaggle Dataset**

---

## 📈 Key Features
- Multi-page navigation using bookmarks & buttons
- Branded dark theme with colored KPIs
- Interactive slicers and dynamic charts
- Responsive layout for presentation/demo use

---

## 🔗 View Screenshots
> 📎 Screenshots included in the repository

---

## 📂 File Structure
```bash
nifty50-stock-dashboard/
│
├── dashboard.pbix               # Power BI file
├── README.md                    # Project documentation
├── screenshots/                 # Dashboard images
│   ├── overview.png
│   ├── company_insights.png
│   └── sector_performance.png
