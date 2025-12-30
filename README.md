Markdown# Online Retail II UCI - Power BI Analysis

**Interactive Power BI dashboard** analyzing the Online Retail II UCI dataset (UK-based online gift retailer, Dec 2009–Dec 2011). Features comprehensive sales trends, top products/countries, and advanced **RFM customer segmentation**.

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Highlights
- Total Revenue: **£17.33M** from 37K orders and 11M units sold
- Distinct Customers: **5,852**
- Key Insight: **Champions** (top 8% of customers) generate **48% of total revenue**
- Strong seasonal peaks in Q4 (Christmas gift rush)
- Vintage/retro home decor and practical gifts dominate top sellers

## Report Pages
1. **Key Insights** – Executive summary of overall business
2. **Sales Dashboard** – Interactive sales exploration
3. **Customer RFM Segmentation** – Detailed technical RFM view
4. **RFM Insights** – Customer segmentation summary with actionable recommendations

## Files in This Repository
- `report/Online_Retail_Analysis.pbix` → Full interactive Power BI report (open in Power BI Desktop)

## Data Files (Hosted on Google Drive – Large Files)
Due to GitHub file size limits, the raw and cleaned datasets are provided via Google Drive:

- **[Raw Dataset (original from Kaggle)](https://drive.google.com/file/d/1cy9yjfcLuTlJeaath6AnwmhhNZEDOApE/view?usp=drive_link)**  
- **[Cleaned Dataset (.xlsx)](https://docs.google.com/spreadsheets/d/1qCE37dFifX3tDgYIPQe4KEbRPC_64Frq/edit?usp=drive_link&ouid=107482627894370432387&rtpof=true&sd=true)**  
  (Blank CustomerIDs removed, dates fixed, ready for import)

> Tip: If you want to explore the data model or modify the report, download the cleaned .xlsx and refresh the data source in Power BI.

## Screenshots

### Sales Dashboard
![Sales Dashboard](screenshots/sales_dashboard.png)

### Key Insights
![Key Insights](screenshots/key_insights.png)

### Customer RFM Segmentation
![Customer RFM Segmentation](screenshots/rfm_analysis.png)

### RFM Insights
![RFM Insights](screenshots/rfm_insights.png)

## How to Use
1. Download **Power BI Desktop** (free): https://powerbi.microsoft.com/desktop/
2. Open the `.pbix` file from the `report/` folder
3. Explore the four pages and interact with slicers

## Tech Stack
- Excel (initial data cleaning)
- Power BI Desktop (transformations, DAX modeling, visualizations)
- Advanced DAX for RFM calculated table and quintile scoring

## Full Project Documentation
See `docs/Project_Documentation.md` for detailed steps, DAX code, findings, troubleshooting, and conclusion.

## Future Enhancements
- Cohort analysis for customer retention
- Time-series forecasting
- Publish to Power BI Service for web sharing

## License
MIT License – feel free to fork, modify, and use!

---

Built as a portfolio project demonstrating end-to-end business intelligence workflow.

⭐ Star this repo if you found it helpful!
