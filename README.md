# 🚓 Data-Driven Public Safety Planning at UNT

**Business Analytics Capstone Project | Power BI**

This project delivers a data-driven analytics solution for the **University of North Texas Police Department**, designed to support operational planning, crime analysis, and community engagement through interactive dashboards.

---

## 🎥 Project Demo Video

Click the image below to watch a short walkthrough of the dashboard and key insights.

[![Watch Demo](images/demo_thumbnail.png)](https://www.linkedin.com/posts/achyutha-ravula_businessanalytics-powerbi-dataanalytics-activity-7407663127913435136-JERE/)

---

## 📌 Project Overview
The UNT Police Department manages multiple datasets related to calls for service, reported offenses, and community engagement activities. These datasets existed in silos, making it difficult to extract actionable insights.

This project consolidates and transforms these data sources into a **single Power BI dashboard** to enable evidence-based decision-making for staffing, patrol planning, and outreach initiatives.

---

## 🎯 Objectives
- Analyze patterns in calls for service by time, day, and location  
- Identify crime hotspots and offense trends  
- Evaluate effectiveness of community engagement events  
- Support proactive public safety planning through analytics  

---

## 📊 Data Sources
The analysis integrates three internal datasets (2023–2025):

- **Calls for Service** – call type, priority, date, time, and location  
- **Offenses** – reported incidents and offense categories  
- **Community Engagement** – event attendance, audience type, and officer participation  

⚠️ *Raw data is confidential and not included in this repository.*

---

## 🧹 Data Preparation
- Text normalization and standardization (addresses, audience names)
- Time parsing and feature engineering
- Reshaping offense data from wide to long format
- Star-schema data modeling in Power BI
- Automated refresh using SharePoint integration

---

## 📈 Dashboard Modules

### 1️⃣ Calls for Service
- Peak demand occurs on **Wednesdays**
- Highest volume during **night shifts (9 PM – 5 AM)**
- Most frequent call type: **Traffic Stops (TSTOP)**

### 2️⃣ Offenses
- Property offenses dominate incident volume
- Clear spatial and temporal crime hotspots
- Higher offense concentration during nighttime hours

### 3️⃣ Community Engagement
- Strong participation in **parent-focused events**
- Attendance distributions are right-skewed, requiring median-based analysis
- Event timing impacts turnout significantly

---

## 💡 Key Insights
- Operational demand is not evenly distributed across time
- Certain locations consistently emerge as crime hotspots
- Strategic scheduling improves engagement outcomes
- Analytics can proactively guide patrol and staffing decisions

---

## ✅ Business Recommendations
- Increase officer coverage during mid-week night shifts
- Focus preventive strategies on identified hotspot locations
- Align engagement events with academic calendar peaks
- Use forecast trends for short-term patrol planning

---

## 🛠 Tools & Technologies
- **Power BI** (Dashboards, DAX, Data Modeling)
- **Power Query (M)** for ETL
- **Python** (select preprocessing tasks)
- **SharePoint** for automated data updates
- **CRISP-DM** analytics framework

---

## 🔒 Data Privacy & Ethics 
No personally identifiable or sensitive operational data is included.

---

## 📌 Outcome
This project provides UNT Police leadership with a **centralized, decision-ready analytics platform**, enabling a shift from reactive reporting to proactive public safety planning.




