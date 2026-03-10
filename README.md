# 📊 Exploratory Data Analysis (EDA) in Banking Using Python

> **CodeAlpha Data Analytics Internship — Task 2: Exploratory Data Analysis**

---

## 🎯 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on the **UCI Bank Marketing Dataset** using Python and Pandas. The goal is to analyze customer behavior and identify patterns that can help a bank run more effective term deposit marketing campaigns.

---

## 📁 Dataset

- **Source:** [UCI ML Repository — Bank Marketing Dataset](https://archive.ics.uci.edu/ml/citation_policy.html)
- **Reference:** [Moro et al., 2014]
- **Size:** 41,188 records × 21 features
- **Target Variable:** `y` — Has the client subscribed a term deposit? (yes/no)

---

## ❓ Business Questions Answered

| # | Question |
|---|----------|
| 1 | What is the share of clients attracted (subscribed)? |
| 2 | What are the mean values of numerical features among attracted clients? |
| 3 | What is the average call duration for attracted clients? |
| 4 | What is the average age among attracted and unmarried clients? |
| 5 | What is the average age and call duration for different job types? |
| 6 | Which months have the best campaign conversion rates? |
| 7 | Which job types and education levels convert most? |

---

## 📊 Analysis Sections

1. **Dataset Exploration** — shape, dtypes, null check, describe, value counts
2. **Sorting & Filtering** — top contacts, youngest clients, sorting by multiple columns
3. **Pivot Tables** — cross-tabulation by marital status, job, education
4. **Visualization**
   - Scatter Matrix (pairwise numeric features)
   - Age Histogram
   - Box Plots (age by marital status, housing)
   - 🔥 Correlation Heatmap (Seaborn)
   - 🔥 Pie Chart — Target Distribution
   - 🔥 Bar Chart — Subscription Rate by Job Type
   - 🔥 KDE Plot — Age Distribution: Subscribed vs Not
   - 🔥 Box Plot — Call Duration vs Subscription
   - 🔥 Count Plot — Monthly Campaign Analysis
   - 🔥 Bar Chart — Subscription Rate by Education
5. **Key Insights & Final Conclusion**

---

## 🔑 Key Findings

| # | Finding | Actionable Insight |
|---|---------|-------------------|
| 1 | Only **11.3%** of clients subscribed | Dataset is imbalanced; campaigns need better targeting |
| 2 | **Students & Retired** clients convert best (~30% & ~25%) | Prioritize these groups in campaigns |
| 3 | **Call duration** is the strongest predictor | Train agents to keep prospects engaged longer |
| 4 | Clients **under 30 & over 60** convert more | Age-targeted messaging improves ROI |
| 5 | **March, Sep, Oct, Dec** have best conversion rates | Schedule high-effort campaigns in these months |
| 6 | **University-educated** clients subscribe more | Use digital/educated messaging channels |
| 7 | High **euribor3m** rate = fewer subscriptions | Monitor macroeconomics before launching campaigns |

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data manipulation, pivot tables, groupby |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Advanced statistical visualizations |

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Upload `Proj1_EDA_Pandas_Banking_FINAL.ipynb` to [Google Colab](https://colab.research.google.com)
2. Run all cells (the dataset downloads automatically via `wget`)

### Option 2 — Local Setup
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/CodeAlpha_EDA_Banking

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the notebook
jupyter notebook Proj1_EDA_Pandas_Banking_FINAL.ipynb
```

---

## 📂 Repository Structure

```
CodeAlpha_EDA_Banking/
│
├── Proj1_EDA_Pandas_Banking_FINAL.ipynb   # Main notebook (complete EDA)
└── README.md                              # Project documentation
```

---

## 🏢 About This Internship

This project was completed as part of the **CodeAlpha Data Analytics Internship Program**.

- 🌐 Website: [www.codealpha.tech](https://www.codealpha.tech)
- 📧 Email: services@codealpha.tech

---

## 👤 Author

**[Your Name]**
- LinkedIn: [Your LinkedIn Profile]
- GitHub: [Your GitHub Profile]

---

*If you found this project useful, please ⭐ star the repository!*
