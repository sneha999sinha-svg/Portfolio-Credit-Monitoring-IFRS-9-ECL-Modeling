# Portfolio Credit Monitoring & IFRS 9 ECL Modeling

## Project Overview

This project demonstrates the design and implementation of a **portfolio-level credit monitoring and IFRS 9 Expected Credit Loss (ECL) framework**.
It integrates borrower monitoring, staging logic, and forward-looking macroeconomic scenarios to support **proactive risk management and provisioning analysis**.

---

## Key Objectives

* Monitor a large credit portfolio to identify **early warning signals and emerging risks**
* Develop a **stage-wise IFRS 9 ECL engine** aligned with regulatory principles
* Quantify **12-month and lifetime ECL** using probability-weighted scenarios
* Support **risk-aware decision-making** at portfolio and desk level

---

## Scope of Analysis

* Portfolio size: **10,000+ credit exposures**
* Coverage across borrower financials, sectoral risks, and macroeconomic conditions
* Focus on **credit risk monitoring, staging, and loss estimation**

---

## Methodology

### 1. Portfolio Credit Monitoring

* Tracked borrower financial performance, earnings updates, and industry news
* Identified **early warning indicators (EWS)** and sector-specific risk trends
* Enabled timely escalation of **emerging credit risks**

### 2. IFRS 9 ECL Framework

* Built a **stage-wise ECL model** covering Stage 1, Stage 2, and Stage 3 exposures
* Incorporated:

  * PD term structures
  * LGD and EAD estimates
  * Time value of money through discounting

### 3. SICR & Forward-Looking Adjustments

* Implemented **Significant Increase in Credit Risk (SICR)** logic for staging transitions
* Applied **forward-looking macroeconomic scenarios** with probability-weighted PDs
* Calculated **12-month and lifetime expected credit losses**

### 4. Portfolio-Level Insights

* Aggregated ECL at portfolio level for **provisioning analysis**
* Generated insights to support **trading desk decisions and risk oversight**

---

## Risk & Controls Relevance

* Aligns with **IFRS 9 regulatory expectations** and credit risk governance
* Emphasizes **early risk identification, transparent assumptions, and scenario analysis**
* Supports ongoing **portfolio monitoring and control frameworks**

---

## Tools & Technologies

* Python / Excel for modeling and analysis
* Credit risk concepts: PD, LGD, EAD, SICR, scenario weighting
* Financial statement and macroeconomic analysis

---

## Disclaimer

This project is for **educational and demonstration purposes only**.
Inputs, assumptions, and outputs are illustrative and do not represent live portfolios or regulatory submissions.
