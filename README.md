# Hospital-Management-System
A comprehensive system for managing hospital operations and patient records.

##  Hospital Performance & Readmission Analytics Dashboard
### 1. Overview Dashboard

### 2. Readmission Analysis Dashboard

### 3. Cost and Outcome Analysis Dashboard

---

##  Project Overview

This project analyzes healthcare data from **1,000 patients** to uncover patterns in **patient volume, readmissions, length of stay, treatment costs, diagnoses, and patient outcomes**.

The goal was to transform raw hospital data into meaningful insights that can help management identify **high-risk patient groups, departments requiring attention, seasonal readmission patterns, and opportunities to improve resource utilization and patient outcomes**.

The analysis revealed an overall **21% readmission rate**, an average patient stay of **7.46 days**, and an average treatment cost of approximately **₦330.28K**.

---

##  Business Objectives

The analysis focused on answering key healthcare management questions:

* Which departments have the highest patient volumes?
* Which departments contribute most to readmissions?
* Which age groups have the highest readmission risk?
* Which months experience the highest readmission rates?
* Does length of stay influence readmission?
* Are higher treatment costs associated with better patient outcomes?
* Which departments have high treatment costs among poor-outcome patients?
* Which patient groups require greater post-discharge follow-up?
* Where should management prioritize clinical and operational improvements?

---

##  Dashboard KPIs

| KPI                         |        Result |
| --------------------------- | ------------: |
|  Total Patients           |     **1,000** |
|  Average Length of Stay   | **7.46 days** |
|  Average Treatment Cost   |  **₦330.28K** |
|  Overall Readmission Rate |       **21%** |

These indicators highlight opportunities to reduce avoidable readmissions and optimize hospital resource utilization.

---

##  Key Insights

###  Patient Volume by Department

The **Emergency Department** recorded the highest patient volume with **192 patients**, followed by:

* Surgery — **153**
* Cardiology — **137**
* Orthopedics — **130**
* Pediatrics — **120**
* Neurology — **101**
* ICU — **85**
* Oncology — **82**

The high Emergency volume indicates potential pressure on **staff, beds, and hospital resources**.

---

###  Readmissions Are a Significant Concern

The overall hospital readmission rate was **21%**, meaning approximately **1 in every 5 patients** was readmitted.

The departments with the highest readmission rates were:

| Department          | Approx. Readmission Rate |
| ------------------- | -----------------------: |
|  Cardiology       |                  **28%** |
|  Oncology        |                  **25%** |
|  ICU              |                  **24%** |
|  Hospital Overall |                  **21%** |

Patients aged **61+ recorded a 38% readmission rate**, substantially higher than other age groups.

**Business implication:**
Older patients and high-readmission departments should receive greater attention through discharge planning, medication monitoring, and post-discharge support.

---

###  Disease Burden, Length of Stay & Cost

The analysis identified several recurring diagnoses contributing significantly to patient volume:

* Malaria
* Diabetes
* COVID-19
* Kidney Disease
* Fractures

The average length of stay was **7.46 days**, suggesting an opportunity to investigate potential drivers such as procedure delays, bed availability, and discharge processes.

Average treatment cost was approximately **₦330.28K**, highlighting the need to understand cost drivers by department, diagnosis, and patient group.

---

### September Recorded the Highest Readmission Rate

**September** recorded the highest monthly readmission rate at approximately **29–30%**.

Other high-readmission months included:

* October — ~26%
* December — ~25.5%
* January — ~25%

This suggests that discharge follow-up and post-discharge support may need to be strengthened ahead of these periods.

---

###  Shorter Stays & Readmissions

Among readmitted patients:

* **53.33%** had a shorter previous stay of **1–6 days**
* **46.67%** had a longer previous stay of **7–14 days**

The analysis suggests a modest association between shorter stays and readmissions, highlighting the need to review discharge-readiness criteria and post-discharge support rather than assuming shorter stays automatically represent greater efficiency.

---

###  Higher Treatment Cost Did Not Guarantee Better Outcomes

One of the most important findings was that **higher treatment costs were not consistently associated with better patient outcomes**.

The **Deceased** outcome group recorded the highest average treatment cost.

Average costs for the other outcome groups included:

| Outcome   | Average Treatment Cost |
| --------- | ---------------------: |
| Improved  |           **₦334.48K** |
| Recovered |           **₦332.30K** |
| Referred  |           **₦285.29K** |

This indicates that treatment expenditure should be evaluated alongside **clinical complexity, complications, and patient outcomes**, rather than being treated as a direct measure of quality of care.

---

###  High-Cost Departments with Poor Outcomes

Patient outcomes were grouped into:

🟢 **Good Outcome:** Recovered + Improved

🔴 **Poor Outcome:** Referred + Deceased

When the dashboard was filtered to poor-outcome patients, three departments stood out:

| Department     | Poor-Outcome Treatment Cost |
| -------------- | --------------------------: |
|  Surgery     |                     **₦6M** |
|  Oncology   |                     **₦4M** |
|  Orthopedics |                     **₦4M** |

**Surgery** was the highest priority because it recorded the largest treatment cost among poor-outcome patients.

---

##  Priority Areas

### Departments Requiring Attention

**1. Cardiology**

* Highest overall readmission rate — approximately **28%**

**2. Oncology**

* Approximately **25% readmission rate**
* ₦4M treatment cost among poor-outcome patients

**3. Surgery**

* Highest poor-outcome treatment cost — **₦6M**

**4. Orthopedics**

* ₦4M treatment cost among poor-outcome patients

### Patient Groups Requiring Follow-Up

*  **Patients aged 61+** — 38% readmission rate
*  **Diabetes patients**
*  **Kidney Disease patients**
*  **Malaria patients**

---

##  Data-Driven Recommendations

Based on the findings, the following actions were recommended:

### 1. Reduce Readmissions

Conduct root-cause reviews beginning with **Cardiology and Oncology**, where readmission rates are highest.

### 2. Prepare for Seasonal Readmission Peaks

Increase discharge-planning capacity and post-discharge outreach ahead of **September, October, December and January**.

### 3. Review Early Discharge

Evaluate discharge-readiness criteria for patients with **1–6 day stays** and consider structured follow-up within **48–72 hours**.

### 4. Strengthen Care for Older Patients

Implement structured post-discharge support for patients aged **61+**, including medication reviews and follow-up scheduling.

### 5. Investigate Cost vs. Outcome

Audit high-cost and high-mortality cases to distinguish unavoidable clinical complexity from potentially avoidable cost drivers.

### 6. Review High-Cost Poor-Outcome Departments

Prioritize **Surgery, Oncology and Orthopedics**, with Surgery receiving the highest priority.

### 7. Address Disease Burden

Develop preventive-care and patient-education initiatives around:

* Malaria
* Diabetes
* COVID-19
* Kidney Disease
* Fractures

### 8. Establish Continuous Monitoring

Create a monthly KPI monitoring system covering:

* Readmission by month
* Readmission by department
* Readmission by age
* Readmission by length of stay
* Cost-to-outcome performance

---

##  Tools & Skills

### Data Analytics

* Data Cleaning & Preparation
* Exploratory Data Analysis
* KPI Development
* Healthcare Analytics
* Trend Analysis
* Performance Analysis
* Data Storytelling

### Visualization

* Interactive Dashboard Development
* KPI Cards
* Departmental Analysis
* Monthly Trend Analysis
* Comparative Analysis
* Filtering & Drill-down Analysis

### Analytical Techniques

* Aggregation
* Segmentation
* Comparative Analysis
* Outcome Classification
* Readmission Analysis
* Cost Analysis
* Length-of-Stay Analysis

---

##  Business Impact

This project demonstrates how healthcare data can move beyond descriptive reporting to support **action-oriented decision-making**.

The analysis identified specific:

* Departments requiring intervention
* Patient groups requiring additional follow-up
* Months with elevated readmission risk
* Potential early-discharge concerns
* High-cost poor-outcome departments
* Opportunities to improve resource utilization

The overall objective is to help hospital management **reduce avoidable readmissions, improve patient outcomes, and make more informed resource-allocation decisions**.

---

##  Key Takeaways

> **21% overall readmission rate** highlights a significant opportunity for improvement.

> **Patients aged 61+ recorded a 38% readmission rate**, making them the primary follow-up group.

> **Cardiology recorded the highest departmental readmission rate at approximately 28%.**

> **September recorded the highest monthly readmission rate at approximately 29–30%.**

> **Surgery recorded ₦6M in treatment costs among poor-outcome patients**, making it the highest-priority department for cost and outcome review.

> **Higher treatment costs did not consistently result in better outcomes**, reinforcing the need to evaluate cost alongside clinical complexity and patient outcomes.

---

##  Conclusion

The hospital dashboard revealed five major priorities:

1. **Reduce avoidable readmissions**, particularly in Cardiology and Oncology.
2. **Improve outcomes for patients aged 61+** and investigate early-discharge risks.
3. **Address the cost-outcome mismatch** in Surgery, Oncology and Orthopedics.
4. **Strengthen post-discharge planning** around high-risk months and patient groups.
5. **Monitor cost and outcomes together** rather than treating treatment cost as a proxy for healthcare quality.

By focusing interventions on the **patients, departments, and periods identified through the data**, hospital management can improve quality of care while reducing unnecessary hospital utilization and costs.

---

##  Author

**Oluwafemi Amodu**  
Data Analyst | Business Intelligence  
[LinkedIn](https://linkedin.com/in/oluwafemitheanalyst0) · [Portfolio](https://Oluwafemiemmanuel551.github.io) · [Email](https://mail.google.com/mail/u/0/#inbox)
· [Chat on Whatsapp](https://wa.me/+2349022131055)

Passionate about transforming raw data into actionable insights, building interactive dashboards, identifying business problems, and supporting data-driven decision-making.


Feel free to **star ⭐ the repository** and explore the analysis.
