# 📊 IT Support Ticket Performance Analysis

## 📌 Project Overview

This project analyzes **97,498 IT support tickets** recorded between **2016 and 2020** to evaluate IT support performance, identify operational bottlenecks, and generate data-driven recommendations for improving ticket resolution and employee satisfaction.

The analysis focuses on **ticket volume, resolution time, ticket categories, agent performance, satisfaction rates, SLA compliance, and software/tool effectiveness**.

The project was developed using **Microsoft Excel**, including Pivot Tables, Power Query, formulas, and data visualization techniques.

---

## 🎯 Business Objective

The primary objective of this project is to understand IT support operations and answer key business questions such as:

* How is ticket volume changing over time?
* Which ticket categories generate the highest workload?
* Which categories require the most time to resolve?
* How does agent performance vary?
* What factors affect employee satisfaction?
* Where are SLA and assignment bottlenecks occurring?
* Should the organization invest in additional staff, training, or better ticket-management tools?

---

## 📂 Dataset

The dataset contains **97,498 IT support ticket records** covering the period **2016–2020**.

### Key Attributes

* Ticket ID
* Date
* Employee ID
* Agent ID
* Request Category
* Issue Type
* Severity
* Priority
* Resolution Time
* Satisfaction Rate
* Agent Name
* Agent Age
* Performance Ratio
* SLA Status
* Email

The project also includes IT-agent information such as name, email, and date-of-birth details.

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                          |
| ------------------- | -------------------------------- |
| **Microsoft Excel** | Data analysis and visualization  |
| **Power Query**     | Data cleaning and transformation |
| **Pivot Tables**    | Aggregation and analysis         |
| **Pivot Charts**    | Data visualization               |
| **Excel Formulas**  | Calculations and derived metrics |
| **PowerPoint**      | Project presentation             |

The project methodology includes Pivot Tables, Power Query-based cleaning, statistical analysis, trend analysis, cross-tabulation, and visualization.

---

## 🔄 Data Preparation

The dataset was prepared before analysis by:

* Checking for missing and inconsistent values
* Checking for duplicate records
* Formatting date fields
* Creating agent date-of-birth fields
* Calculating agent age
* Creating derived performance metrics
* Handling unclassified severity levels

For example, agent age was calculated using Excel's `DATEDIF` function.

---

# 📈 Key Analysis & Insights

## 1. Ticket Volume Analysis

The total ticket volume increased significantly during the five-year period.

| Year | Tickets |
| ---- | ------: |
| 2016 |  13,051 |
| 2017 |  14,915 |
| 2018 |  18,954 |
| 2019 |  21,490 |
| 2020 |  29,088 |

The project identifies a **123% increase** in ticket volume from 2016 to 2020.

Average daily ticket volume was approximately **53.4 tickets per day**.

---

## 2. Ticket Category Analysis

The major ticket categories were:

| Category     |    Tickets |
| ------------ | ---------: |
| System       |     39,002 |
| Login Access |     29,193 |
| Software     |     19,570 |
| Hardware     |      9,733 |
| **Total**    | **97,498** |

System and Login Access tickets together account for a major share of the overall workload.

---

## 3. Resolution Time Analysis

Average resolution time varied considerably by ticket category.

| Category     | Avg. Resolution Time |
| ------------ | -------------------: |
| Hardware     |           ~7.63 days |
| System       |           ~6.62 days |
| Software     |           ~5.24 days |
| Login Access |           ~0.31 days |

Hardware tickets had the highest average resolution time, while Login Access tickets were resolved much faster.
