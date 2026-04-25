#  India Migration Analysis Dashboard (Power BI)

 ## 1.  Project Title / Headline
India Migration Trend Analysis Dashboard using Power BI

---

## 2.  Short Description / Purpose
This project analyzes internal migration patterns in India using Census data.  
The dashboard provides insights into migration trends across states, reasons (work, marriage, education), gender distribution, and duration of stay.  
It helps understand demographic movement and supports data-driven decision-making.

---

 ## 3. Tech Stack
- Power BI (Dashboard Development)
- Power Query (Data Cleaning & Transformation)
- DAX (Basic Calculations & Measures)
- Data Visualization

---

 ## 4.  Data Source


### Raw Dataset (Source: Census of India 2011)
- Rows: 67,505
- Columns: ~32
- Description: Migration data by residence, duration, and reason

### Processed Dataset (Used in Dashboard)
- Rows: [88200]
- Columns: [8]
- Transformations:
  - Selected relevant columns
  - Cleaned missing values
  - Renamed columns
  - Filtered required categories
  - Processed in Power BI (Power Query)
- Includes:
  - State & District
  - Migration Type (Interstate / Intrastate)
  - Reason for Migration
  - Gender (Male/Female)
  - Duration of Residence



## 5.  Features / Highlights
- 📊 Built a **3-page interactive dashboard** (Overview, Reasons, Duration)
- 🔍 Analyzed **~93% intrastate migration dominance**
- 👩‍💼 Explored **gender-based migration trends** (Male → Jobs, Female → Marriage)
- 🎓 Identified **top states for education migration**
- ⏳ Studied **short-term vs long-term migration patterns**
- 🧹 Performed **data cleaning & transformation using Power Query**
- 🎛 Added **interactive filters (State, Gender, Reason)** for dynamic analysis
- 🗺 Included **map visualization for state-wise migration distribution**


---

## 📊 Dashboard Structure

### 🔹 Page 1: Migration Overview
- KPI Cards:
- Total Migrants
- Interstate Migrants
- Intrastate Migrants
- % Interstate
- Donut Chart: Interstate vs Intrastate
- Map: State-wise migration distribution
- Bar Charts:
- Top States in Migration
- Top States in Interstate Migration

---

### 🔹 Page 2: Reasons & Demographics
- Stacked Bar: Migrants by Reason
- Donut Chart: % Share by Reason
- Clustered Bar: Migration by Gender & Reason
- Bar Chart: Top States for Education Migration
- Filters: State, Gender

---

### 🔹 Page 3: Duration Analysis
- Bar Chart: Migrants by Duration of Stay
- Stacked Chart: Duration vs Migration Reason
- Insights Section:
- Short-term vs long-term migration patterns
- Reason-wise variation across durations

---

## 🔍 Key Insights
- ~93% of migration in India is **intrastate**
- Marriage is the **leading reason** for migration
- Male migration is dominated by **employment**
- Female migration is largely driven by **marriage**
- Long-term migration (10+ years) indicates **permanent relocation trends**
- Migration is concentrated in states like **Maharashtra & Uttar Pradesh**

---

## 🎨 Features
- Interactive filters (State, Gender, Reason)
- Clean and modern UI design
- Multi-page analytical dashboard
- Dynamic data exploration

---

## ⚠️ Limitations
- Dataset is from a single year (2011), so no trend analysis (YoY)
- No detailed origin-destination mapping available
- No urban vs rural classification in dataset

---

## 🚀 Future Improvements
- Add multi-year data for trend analysis
- Integrate origin-destination mapping
- Include urban vs rural migration insights
- Advanced anomaly detection using DAX

---

## 📸 Dashboard Preview
*(Add screenshots here)*

---

## 📌 Conclusion
This dashboard provides a comprehensive view of migration patterns in India, helping stakeholders understand demographic shifts and key migration drivers.

---

## 👩‍💻 Author
Simran Choudhary

---
