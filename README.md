# 👥 HR Analytics Dashboard

> **Multi-page HR analytics dashboard built on Power BI — analyzing workforce composition, attrition, compensation, and employee satisfaction**

---

## 📌 Overview

This dashboard provides a complete picture of an organization's human resource metrics. It helps HR managers and leadership teams make data-driven decisions around workforce planning, compensation strategy, and employee retention.

---

## 🎯 Business Problem

The HR team needed a centralized dashboard to:
- Monitor overall workforce composition and headcount
- Track employee attrition and identify risk areas
- Analyze compensation across departments and job roles
- Measure employee satisfaction and work-life balance

---

## 🔄 Data Pipeline

```
📥 Source              ⚙️ Processing          📊 Visualization
──────────             ─────────────          ────────────────
Excel File   ──────►   Power BI Desktop  ───►  Power BI Dashboard
```

---

## 📊 Dashboard Pages

### 1. 🏠 HR Analytics — Overview
| Metric | Value |
|--------|-------|
| Total Employees | 1,470 |
| Active Headcount | Tracked |
| Male Employees | 882 (60%) |
| Female Employees | 588 (40%) |
| Attrition Rate | 16% |
| Avg. Years at Company | 7.01 |
| Avg. Job Satisfaction | 2.73 / 4 |

**Visuals included:**
- Gender percentage breakdown
- Employees by Job Role (bar chart)
- Employees by Educational Field
- Employees by Job Level
- Employees by Distance From Home
- Employees by Performance Rating (84.63% rated 3, 15.37% rated 4)

---

### 2. 👷 Workforce Analysis
- Headcount distribution across all job roles
- Job level breakdown (Level 1–5)
- Distance from home analysis
- Performance rating distribution

---

### 3. 💰 Income & Compensation
| Job Role | Avg. Monthly Income |
|----------|-------------------|
| Manager | $17,200 |
| Research Director | $16,000 |
| Healthcare Representative | $7,500 |
| Manufacturing Director | $7,300 |
| Sales Executive | $6,900 |
| Human Resources | $4,200 |
| Research Scientist | $3,200 |
| Laboratory Technician | $3,200 |
| Sales Representative | $2,600 |

**Also includes:**
- Avg. Income by Department (Sales, HR, R&D)
- Avg. % Salary Hike by Department (~15% across all)
- Employees by Salary Slab (50.88% earn up to $5K)

---

### 4. 😊 Satisfaction Analysis
**Employees by Job Satisfaction (1–4 scale):**
- Score 4: 461 employees
- Score 3: 444 employees
- Score 2: 282 employees
- Score 1: 293 employees

**Satisfaction Metrics by Department** (Spider/Radar Chart):
- Job Satisfaction, Work Life Balance, Relationship Satisfaction, Environment Satisfaction, Job Involvement tracked across Sales, R&D, and HR

**Employees by Work Life Balance:**
- Score 3 (Good): 899 employees — majority
- Score 2: 346 employees
- Score 4: 154 employees
- Score 1: 81 employees

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data source — raw HR records |
| Power BI Desktop | Data modelling, DAX measures & dashboard |
| DAX | Custom calculations and KPI measures |

---

## 📸 Dashboard Preview

![HR Analytics Dashboard](./dashboard_preview.png)

[📄 View Full Dashboard PDF](./HR%20Analytics%20Dashboard.pdf)

---

## 💡 Key Insights Delivered

- **16% attrition rate** flagged — HR team initiated retention strategy review
- **Sales Representatives** earn the least ($2.6K avg) despite high performance pressure — compensation gap identified
- **Work-life balance score 3** dominates (899 employees) — workforce is generally satisfied but room for improvement
- Salary hike % is nearly equal across departments (~15%) — no significant compensation bias found
- **61% of employees earn under $5K/month** — majority fall in the lowest salary slab


---

## 👤 Author

**Mirza Wajeeh Baig** — Data Analyst
[![GitHub](https://img.shields.io/badge/GitHub-mirzawajeehbaig-181717?style=flat&logo=github)](https://github.com/mirzawajeehbaig)
