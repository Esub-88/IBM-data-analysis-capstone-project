# Developer Technology Trends & Dashboard Analysis  
**IBM Data Analyst Capstone Project**

This project analyzes a large subset of the Stack Overflow 2023 Developer Survey to uncover current technology usage, emerging future trends, and global developer demographics. The analysis includes end-to-end data cleaning, feature engineering, dashboard development, and presentation of insights, forming the final capstone for the IBM Data Analyst Professional Certificate.

---

## Project Overview

The goal of this project was to transform raw survey data into actionable insights about:

- Current programming language, database, platform, and web framework usage  
- Anticipated technology adoption for the next year  
- Demographic patterns among global developers  
- Job market demand across several technologies  

The final deliverables include a multi-page presentation and three interactive dashboards built using Google Looker Studio.

---

## Data Cleaning & Preparation

Data wrangling was performed using **Python (pandas)**, including:

- Cleaning and normalizing categorical fields (Age, Education Level, Languages, Platforms, Databases)
- Engineering additional fields such as:
  - `AgeClean` (clarified age categories)
  - `AgeOrder` (numerical sort key for dashboards)
  - `EdLevelClean` (cleaned education labels)
- Splitting semicolon-delimited technology lists for dashboard aggregation
- Standardizing values to ensure compatibility with visualization tools
- Preparing top-10 datasets across technology categories

Additional cleaning steps were applied to enable Looker Studio functionality, including geo-field recognition through Google Sheets.

---

## Dashboards

Three dashboards were built in **Google Looker Studio**, each organized in a 2×2 layout:

### Current Technology Usage
- Top 10 Languages Used  
- Top 10 Databases Used  
- Top Platforms Used  
- Top Web Frameworks Used  

### Future Technology Trends
- Top 10 Languages Desired Next Year  
- Top 10 Databases Desired Next Year  
- Top Platforms Desired Next Year  
- Top Desired Web Frameworks  

### Demographics
- Respondents by Age  
- Respondents by Country (Geo Chart)  
- Respondent Distribution by Education Level  
- Age × Education Level (Stacked Bar Chart)

Dashboard screenshots are included in this repository.

---

## Job Market Analysis

The project includes a job postings visualization created from **job-postings.xlsx**, gathered during the Data Collection module via API.  
The bar chart displays job postings per technology keyword, sorted in descending order.

---

## Tools Used

- **Python** (pandas, regex)
- **Google Looker Studio**  
- **Google Sheets**  
- **Microsoft Excel**  
- **Matplotlib**  
- **Stack Overflow 2023 Developer Survey dataset**  

---

## Final Deliverables

This repository contains:

- **Final Presentation (PDF and PPTX)**  
- **Dashboard screenshots**  
- **Cleaned demographic datasets**  
- **Job postings visualization**  
- **Project documentation and insights**  

---

## Key Insights

- JavaScript, SQL, and Python remain central to modern development, with TypeScript rapidly rising in adoption.  
- PostgreSQL leads relational databases, while Redis and MongoDB show strong expected growth.  
- Cloud platforms such as AWS and Google Cloud dominate both current usage and future interest.  
- Demographics skew toward early-career developers aged 25–34, primarily with Bachelor’s or Master’s degrees.  
- The job market reflects high demand for technologies tied to data workflows, cloud computing, and scalable architectures.

---

## About the Project

This project represents the final capstone for the **IBM Data Analyst Professional Certificate**, demonstrating practical experience in:

- Data wrangling  
- Dashboard creation  
- Exploratory analysis  
- Data storytelling  
- Communicating insights for decision-making  

---
