# Loan Portfolio Analytics  

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-2b3137?logo=github)](https://github.com/yourusername/loan-portfolio-analytics)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-YourName-blue?logo=linkedin)](https://www.linkedin.com/in/your-linkedin/)  
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-gold?logo=powerbi)](https://app.powerbi.com/)  
[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-View%20Dashboard-%23003366?logo=tableau)](https://public.tableau.com/)  

---

## Table of Contents
- [Project Overview](#project-overview)  
- [Objectives](#objectives)  
- [Data Source](#data-source)  
- [Methodology](#methodology)  
- [Key Insights and Findings](#key-insights-and-findings)  
- [Tools and Technologies Used](#tools-and-technologies-used)  
- [Future Work](#future-work)  
- [Data Visualization Interfaces](#data-visualization-interfaces)  
- [Terminologies Used in Data](#terminologies-used-in-data)  
- [Getting Started](#getting-started)  
- [Contribution](#contribution)  
- [Conclusion](#conclusion)  
- [MIT License](#mit-license)  

---

## Project Overview
This project performs an in-depth analysis of a bank’s loan portfolio using SQL for querying and data extraction, with further visualization in Power BI, Excel, and Tableau. The goal is to uncover insights about loan applications, disbursements, repayments, and borrower demographics across temporal, geographical, and categorical dimensions.  

---

## Objectives
- Assess the bank’s loan portfolio performance.  
- Identify patterns in loan applications, approval rates, and repayments.  
- Measure financial indicators such as total funded amount, interest rates, and repayment statuses.  
- Support data-driven strategies for credit and loan product improvements.  

---

## Data Source
The project uses a financial loan dataset stored in SQL Server, covering loan amounts, issue dates, borrower details, repayment statuses, interest rates, and debt-to-income ratios.  

---

## Methodology
1. **Data Ingestion & Storage** – Database creation in SQL Server for structured storage.  
2. **SQL Queries** – Extracted KPIs such as loan applications, funded amounts, and interest rates.  
3. **Excel Processing** – Data cleaning, validation, and initial insights.  
4. **Loan Categorization** – Classified loans as *Good* or *Bad* based on repayment status.  
5. **Dimensional Analysis** – Explored performance across time, geography, purpose, term, and employment details.  
6. **Visualization** – Designed dashboards in Power BI and Tableau for stakeholder reporting.  

---

## Key Insights and Findings
- Breakdown of monthly loan applications (MTD vs PMTD).  
- Comparison of funded vs received amounts to evaluate liquidity.  
- Borrower financial health analyzed through average interest rate and DTI ratios.  
- Loan categorization highlighted performing vs non-performing segments.  
- In-depth breakdowns by loan purpose, status, geography, and term.  

---

## Tools and Technologies Used
- **SQL Server** – Database queries and KPI extraction.  
- **Excel** – Data cleaning and preliminary analysis.  
- **Power BI** – Interactive dashboard creation.  
- **Tableau** – Advanced visualizations and data exploration.  

---

## Future Work
- Develop predictive models for loan default risk.  
- Perform demographic-driven loan product analysis.  
- Assess repayment variations across short- vs long-term loans.  

---

## Data Visualization Interfaces
Dashboards created in **Power BI** and **Tableau** allow interactive exploration of loan performance, borrower demographics, and repayment behaviors.  

| Tool        | Link | Features |
|-------------|------|----------|
| **Power BI** | [![Power BI](https://img.shields.io/badge/Power%20BI-Open%20Dashboard-gold?logo=powerbi)](https://app.powerbi.com/) | • Explore loan trends <br> • Interactive filters <br> • Drill-down insights |
| **Tableau** | [![Tableau Public](https://img.shields.io/badge/Tableau-Open%20Viz-%23003366?logo=tableau)](https://public.tableau.com/) | • Advanced charts <br> • Borrower demographics <br> • Portfolio performance |

---

## Terminologies Used in Data
- **Loan ID** – Unique loan identifier.  
- **Grade & Sub-Grade** – Risk classification based on creditworthiness.  
- **DTI (Debt-to-Income Ratio)** – Measure of borrower debt burden.  
- **Loan Status** – Current repayment condition (paid, default, etc.).  
- **Purpose** – Reason for loan (education, debt consolidation, etc.).  
- **Term** – Loan repayment duration in months.  
- **Interest Rate** – Cost of borrowing as a percentage.  

---

## Getting Started

### Prerequisites
- SQL Management Server  
- Excel  
- Power BI Desktop  
- Tableau Desktop  

### Installation & Setup
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/loan-portfolio-analytics.git
