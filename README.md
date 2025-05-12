# SQL_Farmers_Insurance_Analysis (2018–2021)

This repository contains SQL queries and an executive summary focused on analyzing data from the **Pradhan Mantri Fasal Bima Yojana (PMFBY)**. The project explores agricultural insurance coverage trends across Indian states and districts from 2018 to 2021, highlighting the number of farmers insured, premium contributions, and policy effectiveness.

---

### Project Overview

The analysis is based on real-world insurance data involving over **45 million farmer records** from 26 Indian states/UTs. The SQL scripts investigate:

* Farmer participation levels
* Distribution of premium funding (farmer vs. government)
* Coverage by land area
* Anomalies in reported sums
* Year-wise changes in insured land area

The goal is to support policy decision-making and assess the effectiveness of government-backed crop insurance schemes.

---

###  Key Features

#### 1. **State & District-Level Analysis**

* Identify top-performing states in terms of farmer coverage and insured value.
* Explore districts with unusually low or high premiums or coverage.

#### 2. **Premium Funding Insights**

* Break down the proportion of premiums paid by farmers vs. subsidies.
* Highlight states with negligible participation.

#### 3. **Land Area & Population Coverage**

* Analyze trends in insured land area over time.
* Evaluate penetration rates relative to state/district populations.

#### 4. **Data Quality Checks**

* Flag potential inconsistencies (e.g., Karnataka’s reported insured amounts).
* Support recommendations for data auditing and policy optimization.

---

###  Assumptions

* Monetary figures were normalized by converting from lakh INR to full INR.
* Land area is measured in hectares.
* Population data used as-is for coverage ratio calculations.

---

###  Files in This Repository

* `SQL_Assg_Farmers_Insurance_Questions_Starter.sql` – Set of SQL queries used for data exploration and insight generation.
* `Executive_Summary_Report.pdf` – Written summary with key findings, patterns, and policy recommendations.

---

###  Sample Queries Included

* State-wise farmer coverage and premium contributions
* Top districts by total premiums
* States with the lowest and highest insured sums
* Year-wise trend of insured land area
* Population-based penetration metrics
* Coverage grouped by land size brackets

---

###  Requirements

To run the SQL queries, you will need:

* A SQL engine (e.g., MySQL, PostgreSQL, or similar)
* A dataset structured to match the columns used in the queries
* SQL client software such as DBeaver, pgAdmin, or MySQL Workbench

---

###  Reference

Data insights are derived from PMFBY data (2018–2021).
Learn more about the scheme here: [https://pmfby.gov.in](https://pmfby.gov.in)

---

Author
- Manish Atwal
