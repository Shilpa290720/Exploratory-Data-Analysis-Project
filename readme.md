# 📊 Exploratory Data Analysis (EDA) – Layoffs 2022 Dataset

This project performs Exploratory Data Analysis (EDA) on the **Layoffs 2022** dataset, which captures global layoffs in the tech sector over recent years. Using SQL, we analyze trends, identify key patterns, and uncover interesting insights such as companies most affected, industries hit hardest, and the timeline of layoffs.

---

## 📁 Dataset Overview

- **Source**: [Kaggle – Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
- **Table Used**: `layoffs_staging2` (a cleaned version of the raw dataset)

### Key Columns:
- `company`: Company name
- `location`: City or region
- `industry`: Type of business/sector
- `total_laid_off`: Number of employees laid off
- `percentage_laid_off`: % of company laid off
- `funds_raised_millions`: Funding received
- `stage`: Company stage (e.g., Series A, Public)
- `country`: Country where the layoff occurred
- `date`: Date of layoff

---

## 🎯 Project Goals

- Uncover **layoff trends over time**
- Identify **companies, industries, and countries** most affected
- Track **layoff spikes** and **outlier events**
- Gain insight into the **impact of funding vs. layoffs**
- Analyze **company shutdowns** (100% layoffs)

---

## 🔍 Analysis Highlights

### 🏢 Companies
- Identified companies with the **most layoffs overall** and **per year**
- Found startups that **laid off 100% of staff**, often signaling a shutdown
- Ranked top affected companies by year using window functions

### 🌎 Locations & Countries
- Aggregated layoffs by **city** and **country**
- Highlighted regions most impacted during the layoff waves

### 📈 Time Trends
- Analyzed layoffs by **year** and **month**
- Created a **rolling total** of layoffs over time to visualize the cumulative impact
- Found peak months and possible correlation with economic downturns

### 🏭 Industries & Stages
- Ranked industries by total layoffs (e.g., Consumer, Crypto, Transportation)
- Analyzed company stages (e.g., Series B, Series C, Public) to see which stage was most affected

---

## 📌 Key Insights

- A number of well-funded companies went under despite raising hundreds of millions
- Public companies and growth-stage startups were hit hardest during economic downturns
- The U.S. had the highest concentration of layoffs
- Some industries (like Crypto) showed volatility with multiple complete shutdowns
- Layoffs surged in specific months, hinting at macroeconomic triggers

---

## 🧠 Skills & Concepts Used

- Aggregation and grouping (`GROUP BY`)
- Date and time analysis
- Window functions (`DENSE_RANK`, `ROLLING SUM`)
- CTEs (Common Table Expressions)
- Ranking and filtering
- Trend and outlier detection

---

## 🚀 Next Steps

- Visualize trends in tools like Tableau, Power BI, or Python
- Build dashboards for interactive exploration
- Use data to predict future layoffs or correlate with macroeconomic data

---


