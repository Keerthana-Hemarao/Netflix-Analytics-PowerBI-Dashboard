# Netflix Analytics Dashboard  
A comprehensive data analytics project exploring Netflix's movie catalog using interactive Power BI dashboards, EDA, and feature-engineered insights. This project uncovers trends in content performance, audience engagement, financial outcomes, and global distribution patterns.

---

## Project Overview
The Netflix Analytics Dashboard is designed to help stakeholders understand:
- Which genres deliver the highest **revenue, profit, and ROI**
- Which countries produce the most **popular and profitable** content
- How **directors, ratings, and audience votes** influence movie success
- Trends in **content production, financial growth, and audience engagement** over time

The project includes:
- **Executive Summary Dashboard**
- **Content & Popularity Insights**
- **Financial Performance Analysis**
- **Exploratory Data Analysis (EDA)** in notebooks

---

## Dashboard Sections

### **1. Executive Summary**
Provides a high-level overview:
- Total Movies  
- Total Revenue  
- Total Profit  
- Total ROI  
- Average Rating  
- Movies by Release Year  
- Ratings by Genre  
- Titles Count by Country  

### **2. Content & Popularity Insights**
Highlights content performance patterns:
- Top Directors by Profit  
- Voting vs Popularity Correlation  
- Top Genres by ROI  
- Popularity by Country  

### **3. Financial Performance Analysis**
Explores revenue & cost behavior:
- Budget vs Revenue by Year  
- ROI Category Distribution  
- Profit Margin by Genre  
- ROI Trend Over Time  

---

## Dataset Overview
The dataset (cleaned + feature engineered) includes:
- Movie metadata  
- Genre classifications  
- Popularity & voting metrics  
- Budget, revenue, profit, ROI, profit margin  
- Release trends & regional contributors  
- Derived fields such as movie_age, roi_category, profit margin, scaled metrics  

---

## Tech Stack
- **Power BI** – Dashboard visualization  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Exploratory Data Analysis  
- **Google Colab** – Notebook environment  
- **Excel / CSV** – Data storage & preprocessing  

---

## EDA Notebook
A full Exploratory Data Analysis (EDA) was performed covering:
- Data cleaning
- Missing value treatment
- Feature engineering
- Outlier checks
- Distribution analysis
- Correlation analysis
- Trend analysis

The notebook is included under:  
`[/notebooks/netflix_eda.ipynb](https://colab.research.google.com/drive/1Joc-rfxsePAvk6wO6ZBOVvKuiBvgKrDs?usp=sharing)`

---

## Dashboard Screenshots
```
![Home Page](images/netflix_home.png)
![Summary Dashboard](images/netflix_summary.png)
![Insights Dashboard](images/netflix_insights.png)
![Finance Dashboard](images/netflix_finance.png)
```

## Key Insights Summary
- Drama, Action & Animation show strongest financial performance  
- USA & UK dominate content production & popularity  
- Top directors (Nolan, Yates, Russo brothers) deliver extremely high profits  
- Voting behavior strongly correlates with popularity  
- ROI fluctuates year to year but blockbuster titles significantly lift profitability  

---
