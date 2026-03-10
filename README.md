# 📊 Exploratory Data Analysis (EDA) in Banking Using Python

> **CodeAlpha Data Analytics Internship — Task 1: Exploratory Data Analysis**

---

## 🎯 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on the **UCI Bank Marketing Dataset** using Python and Pandas.

The objective of this analysis is to understand customer behavior and identify patterns that can help banks design more effective marketing campaigns for term deposits.

---

## 🧠 Skills Demonstrated

This project demonstrates the following Data Analytics skills:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Data Preparation
- Statistical Data Exploration
- Data Visualization
- Business Insight Generation
- Python Data Analysis using Pandas

These skills are essential for real-world data analysis and data-driven decision making.

---

## 📁 Dataset

- **Source:** [UCI Machine Learning Repository — Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Reference:** Moro et al., 2014

| Detail | Value |
|--------|-------|
| Full Dataset Size | 41,188 records × 21 features |
| Sample Used in Notebook | 4,119 records (10% sample — `bank-additional.csv`) |
| Target Variable | `y` — Has the client subscribed a term deposit? (yes/no) |

> **Note:** The notebook uses `bank-additional.csv`, which is a randomly selected 10% sample of the full dataset. This sample is included in the repository.

---

## ❓ Business Questions Answered

1. What percentage of clients subscribed to the term deposit?
2. What are the average values of numerical features among subscribed clients?
3. What is the average call duration for subscribed clients?
4. What is the average age among unmarried subscribed clients?
5. How do age and call duration vary across different job types?
6. Which months produce the highest campaign conversion rates?
7. Which job types and education levels convert the most?

---

## 🔄 Project Workflow

### 1️⃣ Problem Understanding
Understanding the business objective of improving bank marketing campaigns.

### 2️⃣ Data Exploration
Analyzing dataset structure, data types, and missing values.

### 3️⃣ Data Cleaning
Handling missing values and preparing the dataset for analysis.

### 4️⃣ Data Analysis
Using filtering, sorting, grouping, and pivot tables to explore patterns.

### 5️⃣ Data Visualization
Creating visualizations to uncover relationships and trends in the data.

### 6️⃣ Insight Generation
Identifying actionable insights that can improve marketing performance.

---

## 📊 Analysis Performed

**Dataset Exploration**
- Dataset shape and structure
- Data types analysis
- Missing value detection
- Summary statistics

**Sorting & Filtering**
- Identify top contacted clients
- Find youngest and oldest customers
- Multi-column sorting

**Pivot Tables**
- Marital status vs subscription rate
- Job type vs conversion
- Education vs conversion

---

## 📈 Key Visualizations Created

| Visualization | Purpose |
|--------------|---------|
| Histogram | Age distribution of clients |
| Boxplots | Age by marital status and housing loan |
| Correlation Heatmap | Relationship between numerical variables |
| Pie Chart | Target distribution (Subscribed vs Not Subscribed) |
| Bar Chart | Subscription rate by job category |
| KDE Plot | Age distribution of subscribed vs non-subscribed clients |
| Box Plot | Call duration vs subscription outcome |
| Count Plot | Monthly campaign analysis |
| Bar Chart | Education level vs subscription rate |

---

## 🔑 Key Insights

| # | Finding | Actionable Insight |
|---|---------|-------------------|
| 1 | Only **11.3%** of clients subscribed | Campaigns need better targeting |
| 2 | **Students & Retired** clients convert best (~30% & ~25%) | Prioritize these groups in campaigns |
| 3 | **Call duration** strongly impacts conversion | Train agents to improve engagement |
| 4 | Clients **under 30 & over 60** convert more | Use age-targeted marketing strategies |
| 5 | **March, Sep, Oct, Dec** have best conversion rates | Schedule major campaigns in these months |
| 6 | **University-educated** clients convert more | Use digital marketing for this segment |
| 7 | High **euribor3m** rate reduces subscriptions | Monitor economic indicators before campaigns |

---

## 💡 Business Impact

The insights generated from this analysis can help banks improve marketing campaigns by:

- Targeting customer segments with higher conversion probability
- Scheduling campaigns during high-performing months
- Training call agents to increase engagement duration
- Designing marketing strategies tailored to specific age groups

These improvements can increase conversion rates and marketing ROI.

---

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data manipulation, pivot tables, groupby |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Advanced statistical visualizations |

---

## 🚀 How to Run the Project

### Option 1 — Google Colab (Recommended)
1. Upload `Proj1_EDA_Pandas_Banking.ipynb` and `bank-additional.csv` to [Google Colab](https://colab.research.google.com)
2. Run all cells

### Option 2 — Run Locally

```bash
# Clone the repository
git clone https://github.com/DebashisSen2025/codealpha_tasks

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Launch the notebook
jupyter notebook Proj1_EDA_Pandas_Banking.ipynb
```

---

## 📂 Repository Structure

```
codealpha_tasks/
│
├── Task1_EDA_Banking/
│   ├── Proj1_EDA_Pandas_Banking.ipynb     # Main EDA notebook
│   └── bank-additional.csv                # Dataset (10% sample, 4,119 records)
│
├── Task2_DataVisualization_Banking/
│   └── Task3_Data_Visualization_Banking.ipynb
│
└── README.md
```

---

## 🏢 Internship Information

This project was completed as part of the **CodeAlpha Data Analytics Internship Program**.

- 🌐 Website: [www.codealpha.tech](https://www.codealpha.tech)
- 📧 Email: services@codealpha.tech

---

## 👤 Author

**Debashis Sen**

- 🔗 LinkedIn: [debashis-sen25](https://www.linkedin.com/in/debashis-sen25)
- 🐙 GitHub: [DebashisSen2025](https://github.com/DebashisSen2025)

*Aspiring Data Analyst passionate about transforming raw data into meaningful insights using Python, SQL, and Power BI.*

---

*If you found this project useful, please ⭐ star the repository!*
