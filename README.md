# 📊 Lead Management Analysis

## 🚀 Project Overview

This project focuses on analyzing lead data to understand customer conversion behavior, identify high-performing lead sources, and generate actionable business insights to improve revenue.

The goal is to simulate a real-world business scenario where companies track leads through different stages and optimize their sales funnel.

---

## 🎯 Objectives

* Analyze lead conversion rates
* Identify best-performing lead sources
* Understand revenue trends over time
* Perform funnel analysis to detect drop-offs
* Generate business insights and recommendations

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **Data Visualization** (Matplotlib, Seaborn)
* **Jupyter Notebook**

---

## 📂 Project Structure

```
lead-management-analysis/
│
├── data/                # Dataset (CSV file)
├── notebook/            # Jupyter notebooks
├── visuals/             # Graphs & charts
├── README.md            # Project documentation
```

---

## 📊 Dataset

* Synthetic dataset generated using Python
* ~1000 records of lead data
* Includes realistic business logic:

  * Revenue generated only for converted leads
  * Different conversion probabilities based on lead source

### 🔑 Key Columns:

* `lead_id`
* `source` (Facebook, Google, Website, Referral)
* `campaign`
* `date`
* `status` (Contacted, Qualified, Converted, Lost)
* `revenue`
* `region`

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning

* Converted date column to datetime
* Checked for missing values
* Created new feature: `month`

---

### 2. Exploratory Data Analysis (EDA)

* Total leads and conversion rate
* Lead distribution by source
* Conversion rate by source
* Revenue contribution by source

---

### 3. Funnel Analysis

Analyzed how leads move through stages:

```
Contacted → Qualified → Converted
```

Identified major drop-offs in the conversion process.

---

### 4. Time-Based Analysis

* Monthly revenue trends
* Performance variation over time

---

## 📈 Visualizations

* Conversion Rate by Source
* Revenue by Source
* Monthly Revenue Trend
* Lead Funnel Distribution

---

## 💡 Key Insights

* Google leads showed higher conversion rates compared to Facebook
* Referral leads generated higher revenue per conversion
* Significant drop observed between “Qualified” and “Converted” stage
* Revenue increased sharply in later months, indicating improved campaign performance

---

## 📌 Business Recommendations

* Invest more in high-converting sources like Google
* Improve lead nurturing strategies for qualified leads
* Optimize low-performing channels like Facebook
* Strengthen final conversion strategies to reduce drop-offs

---

## 🧠 Learning Outcomes

* Hands-on experience with real-world data analysis workflow
* Strong understanding of funnel analysis and conversion metrics
* Ability to derive business insights from data
* Improved skills in Pandas, visualization, and analytical thinking

---

## 🚀 Future Improvements

* Build a predictive model for lead conversion
* Create an interactive dashboard (Power BI / Tableau)
* Use real-world datasets for deeper insights

---

## 👨‍💻 Author

**Ankush Rawat**
Aspiring Data Analyst | MERN Stack Developer transitioning into Data Science

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!
