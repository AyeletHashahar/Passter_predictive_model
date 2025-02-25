# PASSTER: Decision Support System for Tourist Entry Evaluation

## Overview
PASSTER is a predictive decision-support system designed to assist the Israeli Population and Immigration Authority in evaluating the likelihood of tourists overstaying their visas. The system processes pre-arrival data and uses machine learning to enhance entry decision-making, ensuring greater accuracy and efficiency in border control operations.

## Team Members
- **Nir Yekuel** – Computer Science Student
- **Ayelet Hashahar Cohen** – Data Engineering Student
- **Orel Jaraian** – Data Engineering Student
- **Einav Cohen** – Public Policy Student with a Bachelor's in Economics

## Problem Statement
Currently, there is no pre-arrival registration for tourists visiting Israel. As a result:
- Authorities lack advance knowledge about visitors.
- The system relies on manual evaluations at entry points.
- An estimated **25,000** tourists overstay their visas annually (CBS, 2022).

## Solution: PASSTER Decision Support System
### Key Features
1. **Pre-Arrival Registration (ETA-IL)** – Tourists fill out an online form before arriving, managed by the Population and Immigration Authority.
2. **Automated Data Processing** – The system extracts relevant information from submitted forms.
3. **Predictive Model for Decision Support** – The system evaluates the risk level of each visitor based on historical data and various socio-economic factors.
4. **Continuous Model Improvement** – As more data is collected, the system refines its predictions over time.

### Data Utilized
- **193** Countries of origin
- **10** Years of historical data
- **1,496,927** Tourist records
- **12** Features per record, including:
  - Security risk indices
  - Economic indicators
  - Visa overstay trends
  - Past visit history

## Addressing Data Gaps
Since data limitations exist, the system uses external risk assessment sources:
- **Democracy Index (Economist)**
- **Human Development Index (UNDP)**
- **Security Threats Index (theglobaleconomy.com)**

## Model Performance
- **70% Recall** – Effectively identifies high-risk cases.
- **88% Accuracy** – Provides reliable assessments.
- **25% Increase in model precision** due to additional metrics.

## Ethical Considerations
- Ensuring fairness in decision-making while avoiding discrimination.
- Transparent and responsible AI-driven immigration policies.

## Impact
- **Enhances border security** with data-driven insights.
- **Reduces administrative workload** for immigration officers.
- **Improves tourist processing efficiency** and accuracy.

## Acknowledgments
Special thanks to the **Israeli Population and Immigration Authority** for supporting the research and implementation of this project.

---
**Developed by:** PASSTER Team

