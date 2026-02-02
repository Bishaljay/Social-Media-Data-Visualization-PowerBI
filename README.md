📊 Social Media Data Visualization in Power BI  
### Meta Ad Performance Analysis

## 📌 Project Overview
This project focuses on analyzing **paid social media advertising performance** for **Facebook and Instagram (Meta platforms)** using **Power BI**.  
The dashboard provides end-to-end visibility into the advertising funnel — from **reach and engagement** to **conversions and budget utilization** — enabling data-driven marketing decisions.

---

## 🎯 Business Objective
The objective of this project is to help the marketing team:
- Identify the most effective advertising platform (Facebook vs Instagram)
- Track campaign performance and ROI
- Optimize budget allocation across campaigns and ad formats
- Understand audience engagement patterns across demographics, geography, and time

---

## 📂 Scope of the Analysis

### ✅ In Scope
- Paid advertising campaigns on **Facebook and Instagram**
- Metrics related to reach, engagement, conversions, and budget

### ❌ Out of Scope
- Messenger and Audience Network
- Organic (non-paid) engagement

---

## 🗂️ Dataset & Data Model
The dataset is modeled after real-world **Meta Ads data** and follows a **star schema**:

- **Fact Table**
  - `ad_events`: Event-level data (Impressions, Clicks, Shares, Comments, Purchases)

- **Dimension Tables**
  - `ads`: Ad creatives, platform, ad type, targeting
  - `campaigns`: Campaign details and budgets
  - `users`: Demographics and user interests

This structure ensures efficient filtering and accurate KPI calculations.

---

## 📈 Key KPIs & Metrics
- Impressions  
- Clicks  
- Shares & Comments  
- Purchases (Conversions)  
- Engagements (Clicks + Shares + Comments)  
- CTR (Click-Through Rate)  
- Engagement Rate  
- Conversion Rate  
- Purchase Rate  
- Total Budget  
- Average Budget per Campaign  

All KPIs are created using **DAX measures** and respond dynamically to slicers.

---

## 📊 Dashboard Visuals
The Power BI report includes:

- KPI Overview Cards  
- Gender-wise performance (Donut Chart)  
- Age group engagement (Bar Chart)  
- Country-wise analysis (Map)  
- Weekly and hourly engagement trends  
- Calendar heatmap for seasonal patterns  
- Ad type performance comparison (Matrix/Table)  

Dynamic slicers allow users to filter by **platform, date range, and selected metrics**.

---

## 🔍 Key Insights
- High **CTR (11.76%)** and **Engagement Rate (13.56%)** indicate strong ad creatives
- **Purchase Rate (0.61%)** highlights a drop in the lower funnel
- Best-performing audience: **Females aged 18–30**
- Best-performing formats: **Video and Story ads**
- Peak engagement during **afternoon and evening hours**

---

## ✅ Recommendations
- Optimize landing pages and checkout flow to improve conversions  
- Implement retargeting for users who clicked but did not purchase  
- Reallocate more budget to **Video and Story ads**  
- Schedule ads during peak engagement hours  
- Segment campaigns by geography for volume vs value optimization  

---
## 🛠 Tools & Technologies
- **Power BI Desktop**
- **DAX**
- CSV datasets
- Data modeling (Star Schema)

---
## 📦 Deliverables
- Multi-page **Power BI report (.pbix)**
- Clean star-schema data model
- DAX measures for all KPIs
- Interactive visuals with slicers
- Walkthrough PDF documenting insights and recommendations

---

## 📁 Repository Structure
```text
Social-Media-Data-Visualization-PowerBI/
│
├── README.md
│
├── pbix/
│   └── Social_Media_Data_Visualization.pbix
│
├── screenshots/
│   ├── 01_KPI_Overview.png
│   ├── 02_Gender_Age_Analysis.png
│   ├── 03_Geographic_Analysis.png
│   ├── 04_Time_Trends.png
│   ├── 05_Ad_Type_Performance.png
│
├── walkthrough/
│   └── Walkthrough.pdf
│
├── datasets/
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
│
├── images/
│   ├── instagram_icon.png
│   ├── facebook_icon.png
│   ├── whatsapp_icon.png
│   ├── meta_logo.png
│   └── trends_image.png
````
## 🚀 Project Status

✅ **Completed | Fully Aligned with Business Requirements**

---

## 👤 Author

**Bishal Jaysawal**

⭐ If you find this project useful, feel free to star the repository!


