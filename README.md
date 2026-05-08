# HR Analytics Dashboard — Employee Attrition Analysis

**Tools:** Power BI, DAX  
**Domain:** HR Analytics | Workforce Management | Attrition Analysis  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes employee attrition data across 1,470 employees to identify which factors — age, salary, education, job role, and tenure — most strongly predict employee departure. The dashboard enables HR teams to pinpoint high-risk segments and design targeted retention interventions based on data-driven insights.

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16% |
| Average Age | 37 |
| Average Salary | $6,500 |
| Average Years at Company | 7 |

---

## Dashboard Features

- **Travel filter** — Non-Travel / Travel Frequently / Travel Rarely
- **Department filter** — Human Resources / Research & Development / Sales
- **Gender filter** — Male / Female
- **Attrition by Age** — bar chart across 5 age bands
- **Attrition by Education** — donut chart by education field
- **Attrition by Salary** — bar chart across 4 salary bands
- **Years at Company** — line chart showing attrition peak by tenure year
- **Attrition by Job Role** — horizontal bar chart
- **Job Satisfaction by Job Role** — matrix of satisfaction scores 1–4 per role

---

## Attrition by Age Group

| Age Group | Attrition Count |
|---|---|
| 26–35 | 116 |
| 18–25 | 44 |
| 36–45 | 43 |
| 46–55 | 26 |
| 55+ | 8 |

---

## Attrition by Education Field

| Education Field | Share |
|---|---|
| Life Sciences | 38% |
| Medical | 27% |
| Marketing | 15% |
| Technical Degree | 14% |
| Other | 5% |

---

## Attrition by Salary Band

| Salary Band | Attrition Count |
|---|---|
| Up to $5K | 163 |
| $5K–$10K | 49 |
| $10K–$15K | 20 |
| $15K+ | 5 |

---

## Attrition by Job Role

| Job Role | Attrition Count |
|---|---|
| Laboratory Technician | 62 |
| Sales Executive | 57 |
| Research Scientist | 47 |
| Sales Representative | 33 |

---

## Job Satisfaction Matrix (Score 1–4 per Role)

| Job Role | Score 1 | Score 2 | Score 3 | Score 4 | Total |
|---|---|---|---|---|---|
| Laboratory Technician | 20 | 8 | 21 | 13 | 62 |
| Sales Executive | 16 | 9 | 18 | 14 | 57 |
| Research Scientist | 13 | 10 | 15 | 9 | 47 |
| Sales Representative | 7 | 10 | 9 | 7 | 33 |

---

## Key Findings

**1. 26–35 age group accounts for 49% of all attrition (116 of 237)**
Early-career employees in their late 20s and early 30s are the highest attrition risk — likely driven by better external opportunities, career growth impatience, or compensation gaps at this stage.

**2. 69% of attrition comes from employees earning under $5K (163 of 237)**
The salary-attrition relationship is stark and clear — low compensation is the single biggest attrition driver. Raising floor salaries for high-risk roles would directly impact retention.

**3. Life Sciences graduates leave the most (38%) — despite being the most common education field**
The overrepresentation of Life Sciences attrition suggests either role-education misalignment or that Life Sciences graduates have strong external market demand pulling them away.

**4. Attrition peaks dramatically at Year 1 (59 employees) then drops sharply**
The Years at Company chart shows a massive spike at the 1-year mark — indicating onboarding and early experience failure is critical. Employees who survive Year 1 are significantly more likely to stay.

**5. Laboratory Technicians (62) and Sales Executives (57) account for 50% of all attrition**
Two job roles alone drive half of all departures — these roles require targeted retention programs, compensation reviews, and workload assessments immediately.

**6. Research Directors have near-zero attrition (2 total)**
Senior leadership roles show minimal attrition — confirming that tenure, seniority, and compensation stability at senior levels effectively retain employees.

---

## Technical Highlights

- Travel, Department, and Gender filters with cross-visual filtering
- Job Satisfaction matrix combining role and score dimensions
- Tenure-based attrition line chart identifying Year 1 spike
- DAX measures for attrition rate %, average salary, and satisfaction distribution
- Multiple simultaneous attrition breakdowns enabling multi-factor root cause analysis

---

## Data Source

HR Analytics Dataset — IBM HR Analytics Employee Attrition Dataset, Kaggle.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
