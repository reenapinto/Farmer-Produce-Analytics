# 🌱 Farmer Question–Answer Analytics & Seasonal Insights (Producers Direct)

## 📌 Problem Statement

Smallholder farmers increasingly rely on digital advisory platforms to ask questions about crops, pests, weather, markets, and livelihoods. However, understanding **who asks questions, who responds, when engagement happens, and what topics dominate across seasons and regions** is critical for improving advisory quality, expert allocation, and farmer support systems.

This project analyzes **15M+ English-language farmer questions and responses** to uncover **demographic, seasonal, behavioral, and financial patterns**, enabling data-driven decisions for agricultural platforms and rural development initiatives.

---

## 📂 Dataset

**Source:** Producers Direct – Farmer Question & Answer Platform  
**Records:** 15M+ interactions  
**Countries Covered:** Kenya, Uganda, Tanzania  
**Language Filter:** English only  

### Key Fields
- User demographics (gender, DOB, country)
- Account creation timestamps
- Question & response timestamps
- Question and response topics
- Derived metrics (account age, birth year, seasonality)

> ⚠️ Raw data is not shared due to size and privacy constraints. Schema and feature descriptions are provided instead.

---

## 🛠️ Approach & Methodology

### 1️⃣ Data Understanding & Exploratory Data Analysis (EDA)
- Filtered dataset to English questions and responses
- Analyzed platform participation:
  - Questioners vs responders
  - Engagement intensity
- Explored trends over time (monthly, yearly)
- Examined country-level and demographic distributions

---

### 2️⃣ Data Cleaning & Preparation
- Standardized datetime fields
- Handled missing values (DOBs, account creation dates)
- Removed duplicate records
- Ensured data consistency across large-scale datasets

---

### 3️⃣ Feature Engineering
Created analytical features including:
- **Account Age at Interaction (Days)** for questioners and responders
- **Birth Year & Age Buckets**
- **Seasonal Labels** based on country-specific farming calendars
- **Topic Groupings** (crop-specific vs general)
- **Financial Topic Categories** (market prices, credit/loans, livelihood)

---

### 4️⃣ KPI Development (Dashboard-Ready Metrics)

Key metrics computed for the English dataset:
- Total unique questioners and responders
- Average questions per unique questioner
- Average responses per unique responder
- Country-wise participation share (%)
- Gender distribution (Q & R)
- Birth year and account age density patterns

---

### 5️⃣ Visualization & Analysis
Developed clear, stakeholder-ready visuals:
- **Birth Year Density:** Questioners vs Responders
- **Account Creation Age Pattern**
- **Seasonal Question Trends by Country**
- **Financial Topic Peaks by Season**
- **Question–Answer Network Graph** highlighting community leaders

---

### 6️⃣ Network & Community Analysis
- Built a Question–Responder interaction network
- Identified highly connected responders acting as **community experts**
- Observed strong knowledge transfer from experienced users to newer farmers

---

## 📊 Key Insights

- Responders are generally **older and more experienced** than questioners
- Newer accounts ask most questions, while older accounts provide answers
- Pest and crop-health questions spike during rainy seasons
- Market price and loan-related queries increase before planting periods
- A small group of expert responders contributes a significant share of answers
- Financial and livelihood questions reflect broader economic challenges beyond farming

---

## 💡 Business Impact

This analysis supports:
- Improved **seasonal content planning**
- Identification of **expert farmers** for incentives or recognition
- Better timing of **financial products** (credit, insurance, market information)
- Stronger data-driven strategies to improve farmer engagement and retention

---

## 🚀 Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- NetworkX  
- NLP (Keyword-based classification)  
- Jupyter Notebook  

---

## 📌 Final Output

The project delivers:
- Actionable KPIs for farmer engagement
- Clear demographic and seasonal behavior patterns
- Insightful dashboards for stakeholders
- A scalable framework for future predictive modeling (e.g., forecasting question demand)

---

## 🧠 Author

**Reena Pinto**  
Aspiring Data Scientist | Analytics, EDA & Applied NLP  
Focused on agriculture, social impact, and large-scale data analysis
