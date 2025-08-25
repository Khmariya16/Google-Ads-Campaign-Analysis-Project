# Google-Ads-Campaign-Analysis-Project

# 📊 Google Ads Campaign Analysis  

## 📌 Problem Statement  
Businesses invest heavily in online advertising, but not all campaigns or keywords perform equally. Without proper analysis, money may be wasted on low-performing ads.  

The goal of this project is to analyze **Google Ads campaign data** to:  
- Identify the most effective campaigns and keywords.  
- Calculate key performance metrics (**CTR, CPC, CVR, CPA, ROI**).  
- Provide actionable recommendations to optimize ad spend and maximize ROI.  

---

## 🔍 Methods  

### 1. Data Cleaning & Preprocessing  
- Removed missing values and handled inconsistent formats (dates, costs, text variations).  
- Standardized categorical variables (device, location, campaign names, keywords).  

### 2. Feature Engineering  
Created key marketing metrics for deeper insights:  

- **CTR (Click-Through Rate)** = Clicks ÷ Impressions × 100  
- **CPC (Cost Per Click)** = Cost ÷ Clicks  
- **CVR (Conversion Rate)** = Conversions ÷ Clicks × 100  
- **CPA (Cost Per Acquisition)** = Cost ÷ Conversions  
- **ROI (Return on Investment)** = (Revenue − Cost) ÷ Cost × 100  

### 3. Exploratory Data Analysis (EDA)  
- Distribution of impressions, clicks, and conversions.  
- Campaign-level performance comparison.  
- Keyword-level analysis to find top and underperforming keywords.  
- Visualizations: CTR trends, Cost vs Conversions, ROI distribution.  

### 4. Insights & Recommendations  
- Identified high CTR but high CPC keywords.  
- Highlighted keywords with best ROI and conversion efficiency.  
- Suggested **budget reallocation** strategies.  

---

## 📊 Results  

### 🔥 Top-Performing Campaign  
- **Highest CTR & CPC**: *Data Analytics Course*  
- Delivered best balance of **conversions** and **ROI**.  

### 🔑 Keyword Insights  
- *Data Analytics Course* → **Highest Conversions (3785)** but also high cost.  
- *Data Analytics Online* → Strong CTR & conversions with slightly lower cost.  
- *Data Analytics Training* → Lower conversions → optimization opportunity.  

### 📌 Metric Highlights  
- High **CTR but poor ROI** → Strong interest but inefficient spend.  
- High **CVR + Low CPA** → Best keywords for scaling.  

---

## 📈 Recommendations  

- ✅ Reallocate budget toward **Data Analytics Course** and **Data Analytics Online**.  
- ⚠️ Reduce spend on low ROI keywords (*Data Analytics Training*).  
- 🛠️ Optimize ad creatives & targeting for **high CTR but low conversion** keywords.  
- 📉 Continuously monitor **CPA vs ROI** for cost efficiency.  

---

## 🛠️ Tech Stack  

- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook** for analysis & visualization  
- **Dataset**: Simulated Google Ads campaign data  

---

## 📂 Repository Structure  

├── Google_Ads_Campaign_Analysis_Project.ipynb # Main notebook with analysis
├── data/ # Dataset (raw & cleaned)
├── README.md # Project documentation



---

## 🚀 Conclusion  

This project demonstrates how **data-driven insights** can improve digital marketing ROI by analyzing campaign performance and identifying optimization opportunities.  

👉 Future improvements could include:  
- A/B testing analysis.  
- Predictive modeling for keyword performance.  
- Dashboard creation with Plotly/Streamlit for real-time monitoring.  
