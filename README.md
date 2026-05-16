# 💼 Data Science Job Salary Analysis — Tableau Dashboard

An interactive Tableau dashboard that analyzes global Data Science job salaries across experience levels, company sizes, job titles, employment types, and employee residency using real-world salary data.

---

## 📸 Dashboard Preview

![Data Science Job Salary Analysis](https://raw.githubusercontent.com/29Rajeswari/YOUR_REPO_NAME/main/DataScience_Job_Salary.png)

---

## 📊 Key Insights at a Glance

| Insight | Finding |
|---|---|
| Highest Earning Experience | Mid-level (MI) — ~100M total salary |
| Top Company Size by Salary | Large (L) — 11,75,51,772 |
| Top Country by Salary | United States — 6,66,39,171 |
| Dominant Employment Type | Full-Time (FT) — 19,47,01,278 |
| Top Employee Residency | United States (300+) |
| Second Highest Location | India (IN) — 4,95,64,997 |

---

## 🗂️ Dashboard Visualizations

| # | Chart | Type | Description |
|---|---|---|---|
| 1 | **Experience Level** | Horizontal Bar | Total salary by experience: MI, SE, EN, EX |
| 2 | **Company Size** | Pie Chart | Salary split across Small (S), Medium (M), Large (L) companies |
| 3 | **Location based on Salaries** | Bar Chart | Top countries by total salary — US, IN, JP, CA, GB, DE, FR, ES, GR, AU |
| 4 | **Avg Salary by Experience & Job Title** | Dot Plot | Average salary across FL / FT / PT employment types per job title |
| 5 | **Salary Distribution across Type** | Bubble Chart | Full-Time dominates with 19,47,01,278 in total salary |
| 6 | **Employee Residency** | Horizontal Bar | Count of employees by country of residence |

---

## 🔍 Detailed Findings

### 🎓 Experience Level
| Level | Code | Total Salary |
|---|---|---|
| Mid-level | MI | ~100M (Highest) |
| Senior | SE | ~60M |
| Entry | EN | ~15M |
| Executive | EX | ~10M |

### 🏢 Company Size
| Size | Total Salary |
|---|---|
| Large (L) | 11,75,51,772 |
| Medium (M) | 4,77,66,335 |
| Small (S) | 3,13,49,931 |

### 🌍 Top Countries by Salary
| Country | Total Salary |
|---|---|
| United States (US) | 6,66,39,171 |
| India (IN) | 4,95,64,997 |
| Japan (JP) | 2,04,52,000 |
| Canada (CA) | 34,59,200 |
| Great Britain (GB) | 29,27,856 |

### 💼 Job Titles Covered
- AI Scientist
- Big Data Engineer
- Data Analyst
- Data Architect
- Data Engineer
- Data Science Manager
- Data Scientist
- Machine Learning Engineer
- Machine Learning Scientist
- Research Scientist

---

## 🗃️ Dataset Details

| Property | Details |
|---|---|
| Source | [Data Science Job Salaries — Kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) |
| Records | 607 entries |
| Fields | work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size |
| Years Covered | 2020 – 2022 |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau Desktop / Tableau Public** | Dashboard creation & visualization |
| **Microsoft Excel / CSV** | Data source |
| **Kaggle** | Dataset source |

---

## 📁 Repository Structure

```
DataScience-Job-Salary-Analysis/
│
├── DataScience_Job_Salary.png       # Dashboard screenshot
├── ds_salaries.csv                  # Source dataset (optional)
├── DataScience_Job_Salary.twbx      # Tableau packaged workbook
└── README.md
```

---

## 🚀 How to View the Dashboard

### Option 1 — Tableau Public (Recommended)
> *(Publish your workbook to Tableau Public and paste the link here)*

🔗 [View Live Dashboard](#) ← *Replace with your Tableau Public link*

### Option 2 — Tableau Desktop
1. Download the `.twbx` file from this repo
2. Open with **Tableau Desktop** (free trial available)
3. Interact with all filters and views

### Option 3 — Tableau Public (Free)
1. Download `.twbx` from this repo
2. Open with **Tableau Public** (free desktop app)
3. Download from [https://public.tableau.com/](https://public.tableau.com/)

---

## 🎨 Design Theme

| Element | Details |
|---|---|
| Background | White / Light gray |
| Primary Color | Teal (`#2E8B8B`) |
| Chart Colors | Green, Pink, Red, Blue, Orange (multi-series) |
| Layout | Single-page dashboard with 6 panels |
| Title Style | Bold, centered, teal header band |

---

## 💡 Possible Improvements

- Add a **Year filter** to see salary trends from 2020 to 2022
- Include a **Remote Ratio** breakdown (fully remote vs hybrid vs on-site)
- Add **salary in USD** normalization for fair country comparison
- Use a **map visualization** for geographic salary distribution
- Add **tooltips** with detailed stats on hover

---

## 👤 Author

**Rajeswari**
🔗 GitHub: [@29Rajeswari](https://github.com/29Rajeswari)

---

> **Dataset:** Data Science Job Salaries — available on [Kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
