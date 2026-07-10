# (CS-IDS) Cyber Security Intrusive Detection Analysis

## Project Overview
This project focuses on developing a robust intrusion detection and analysis framework by analyzing network traffic data. Utilizing a combination of Python, SQL, and Power BI, the aim is to identify malicious activities such as Brute Force, Cross-Site Scripting (XSS), and SQL Injection attacks within the CICIDS2017 dataset. The primary objective is to enhance cybersecurity threat visibility, improve understanding of attack patterns, and provide efficient identification of suspicious entities through comprehensive reporting and visualization.


## Features
- **DATA CLEANING AND PREPROCESSING**:   Robust handling of duplicate records, missing values, and data standardization.
- **EXPLORATORY DATA ANALYSIS (EDA)**:   In-depth analysis of attack distribution, traffic volume, protocol usage, and packet behavior.
- **SQL- BASED THREAT ANALYTICSs:**   Execution of SQL queries to identify specific attack distributions, analyze source and destination IP activity, and pinpoint high-risk IPs.
- **INTERACTIVE DASHBOARD:** Development of Power BI dashboards for executive overview, traffic analysis, and attack analysis
- **PYTHON VISUALISATION:** Generation of key insights through Matplotlib and Seaborn visualizations.
- **COMPREHENSIVE REPORTING:** Detailed documentation of findings and security recommendations.


## Technologies Used
- PROGRAMMING LANGUAGE: Python
- LIBRARIES: Pandas, NumPy, Matplotlib, Seaborn
- DATABASE: MySQL
- VISUALISATION TOOLS: Power BI Desktop, Matplotlib, Seaborn
- DEVELOPMENT ENVIRONMENT: Jupyter Notebook, VS Code


## Methodology
The project adopted a structured approach to cybersecurity intrusion detection analysis, encompassing the following key steps:

- DATASET COLLECTION: Acquired the CICIDS2017 Thursday Web Attacks dataset.
- DATA CLEANING: Performed data cleaning, including removal of duplicates, handling missing values, and standardizing data.
- EXPLORATORY DATA ANALYSIS (EDA): Conducted statistical and visual analysis to understand dataset characteristics and identify patterns.
- SQL ANALYSIS: Executed SQL queries for detailed threat analysis, focusing on attack distributions, IP activity, and protocol usage.
- POWER BI DASHBOARD: Designed and implemented interactive dashboards for comprehensive data presentation.

## Key Results
- Analyzed over 170,000 network traffic records, identifying more than 2,180 attacks.
- Brute Force attacks were the most prevalent (69.13%), followed by XSS (29.91%) and SQL Injection (0.96%).
- Identified high-risk IP addresses and major communication channels (DNS, HTTPS) with heavily utilized TCP and UDP protocols.
- Developed a framework that offers enhanced threat visibility and improved understanding of attack behaviors.

## Repository Structure
- CyberSecurityIntrusionDetectionAnalysis_With_SQL_Screenshots.pdf: The original report document.
- cyber_analysis_python.ipynb: Jupyter Notebook containing Python code for data cleaning, EDA, and visualization generation.
- cleaned_cybersecurity_dataset.csv: Cleaned dataset used for analysis.
- Updated_CyberSecurityIntrusionDetectionAnalysis.pdf: The updated report with Python visualizations and refined layout.
- README.md: This file.

## How to Use/Setup

- CLONE THE REPOSITORY: git clone https://github.com/SaiCharan0417/Cyber-Security-Intrusion-Detection-Analysis.git

- NAVIGATE TO THE PROJECT DIRECTORY:''' bash cd Cyber-Security-Intrusion-Detection-Analysis'''

- INSTALL NECESSARY PYTHON LIBRARIES: pip install pandas numpy matplotlib seaborn

- SET UP MYSQL DATABASE: Ensure MySQL is installed and configured. The cyber_analysis_python.ipynb notebook assumes a cleaned_cybersecurity_dataset.csv file is available for import into MySQL.

- RUN THE JUPYTER NOTEBOOK: Open cyber_analysis_python.ipynb in Jupyter and execute cells to reproduce data cleaning, EDA, and Python visualizations.

- REVIEW REPORTS: Examine the PDF reports for detailed analysis and findings.

## Author
- Sai Charan
- Student, NGIT CSE’29
- LINKEDIN📧- [https://www.linkedin.com/in/sai-charan-rapolu-18552036b/]
