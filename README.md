<div align="center">

# 📈 Advertisement Campaign Analysis with A/B Testing & Regression  

</div>

## 📘 Project Overview  
This project analyzes and optimizes digital advertising performance using **A/B testing** and **regression analysis**.  
It compares **Facebook Ads** and **Google AdWords** across clicks, conversions, and cost-efficiency to support **data-driven budget decisions**.

---

## 📑 Table of Contents  
- [📘 Project Overview](#-project-overview)  
- [📂 Data Sources](#-data-sources)  
- [🧹 Data Cleaning](#-data-cleaning)  
- [🛠️ Data Modeling](#️-data-modeling)  
- [📊 Statistical & Predictive Analysis](#-statistical--predictive-analysis)  
- [📈 Data Visualization](#-data-visualization)  
- [📌 Key Insights](#-key-insights)  
- [💻 Tools & Technologies Used](#-tools--technologies-used)  
- [📎 Outcome](#-outcome)  
- [🚀 Future Scope](#-future-scope)  
- [⭐ Contribute & Support](#-contribute--support)

---

## 📂 Data Sources  
The dataset includes daily campaign metrics for both platforms from **January 1 to December 31, 2019**, covering:

- **Date** – Daily campaign log  
- **Ad Views** – Total impressions  
- **Ad Clicks** – Total clicks  
- **Ad Conversions** – Completed conversion events  
- **Cost per Ad** – Daily ad spend  
- **CTR (Click-Through Rate)** – Clicks ÷ Views  
- **Conversion Rate** – Conversions ÷ Clicks  
- **CPC (Cost per Click)** – Cost ÷ Clicks  

---

## 🧹 Data Cleaning  
Performed cleaning and preprocessing to ensure data reliability:

- Standardized date formats  
- Converted numerical fields to correct data types  
- Handled missing values and removed duplicates  
- Ensured consistency across both platform datasets  

---

## 🛠️ Data Modeling  
Prepared and structured datasets for comparative and predictive analysis:

- Added **platform identification columns**  
- Recalculated CTR, CPC, and Conversion Rate for uniformity  
- Created additional KPIs and analytical flags  
- Merged platform data for unified modeling  

---

## 📊 Statistical & Predictive Analysis  

### **A/B Testing**
- Conducted **t-tests** to compare Facebook vs. Google AdWords on:  
  - CTR  
  - CPC  
  - Conversion Rate  

### **Regression Modeling**
- Developed a **linear regression model** for predicting conversions from clicks  
- Evaluated accuracy using **R²** and **MSE**  

### **Correlation & Cointegration**
- Assessed long-term relationships between:  
  - Ad spend and conversions  
  - Platform-level performance patterns  

---

## 📈 Data Visualization  
Created insightful dashboards using **Matplotlib** and **Seaborn**, including:

- Line plots: CTR, CPC, and conversion trends  
- Scatter plots: Click–Conversion relationships  
- Box plots: KPI distributions across platforms  
- Time-series plots: Seasonal and temporal patterns  

---

## 📌 Key Insights  

### **Platform Performance**
- **Facebook** demonstrated **higher conversion rates** and **lower CPC**, outperforming Google AdWords in overall efficiency.

### **Budget Optimization**
- Results suggest reallocating a greater share of budget toward Facebook for improved ROI.

### **Seasonal Behavior**
- Conversion performance peaked during **Q2** and **Q4**, emphasizing the impact of timing on ad strategy.

---

## 💻 Tools & Technologies Used  
- **Python** – Core analysis  
- **Pandas & NumPy** – Data processing  
- **Matplotlib & Seaborn** – Visualizations  
- **SciPy** – Statistical testing (t-tests, cointegration)  
- **Scikit-learn** – Regression modeling  

---

## 📎 Outcome  
This project provides a comprehensive, **data-driven framework** for evaluating digital ad platforms.  
It supports:

- Strategic **budget allocation**  
- Improved **ROI measurement**  
- Better understanding of seasonal performance drivers  

Designed for marketing analysts and teams aiming to maximize advertising effectiveness.

---

## 🚀 Future Scope  
Potential enhancements include:

- Time-series forecasting (ARIMA, Prophet)  
- Multi-channel attribution modeling  
- Interactive dashboards (Streamlit, Power BI)  
- Automated A/B testing evaluation  
- Advanced ML models (Random Forest, Gradient Boosting)  

---

## ⭐ Contribute & Support  
If this project was useful:

- ⭐ **Star the repository**  
- 🐛 Open issues for bugs or enhancements  
- 🤝 Submit pull requests anytime  

---
