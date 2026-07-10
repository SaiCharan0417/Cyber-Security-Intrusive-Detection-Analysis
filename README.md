# (CS-IDS) Cyber Security Intrusive Detection Analysis

## Project Overview

This project focuses on developing a robust intrusion detection and analysis framework by analyzing network traffic data. Utilizing a combination of Python, SQL, and Power BI, the aim is to identify malicious activities such as Brute Force, Cross-Site Scripting (XSS), and SQL Injection attacks within the CICIDS2017 dataset. The primary objective is to enhance cybersecurity threat visibility, improve understanding of attack patterns, and provide efficient identification of suspicious entities through comprehensive reporting and visualization.


## Features
- Data Cleaning and Preprocessing: Robust handling of duplicate records, missing values, and data standardization.

•Exploratory Data Analysis (EDA): In-depth analysis of attack distribution, traffic volume, protocol usage, and packet behavior.

•SQL-based Threat Analytics: Execution of SQL queries to identify specific attack distributions, analyze source and destination IP activity, and pinpoint high-risk IPs.

•Interactive Dashboards: Development of Power BI dashboards for executive overview, traffic analysis, and attack analysis.

•Python Visualizations: Generation of key insights through Matplotlib and Seaborn visualizations.

•Comprehensive Reporting: Detailed documentation of findings and security recommendations.


Technologies Used

•Programming Language: Python 3.x

•Libraries: Pandas, NumPy, Matplotlib, Seaborn

•Database: MySQL

•Visualization Tools: Power BI Desktop, Matplotlib, Seaborn

•Development Environment: Jupyter Notebook, VS Code


Methodology

The project adopted a structured approach to cybersecurity intrusion detection analysis, encompassing the following key steps:

1.Dataset Collection: Acquired the CICIDS2017 Thursday Web Attacks dataset.

2.Data Cleaning: Performed data cleaning, including removal of duplicates, handling missing values, and standardizing data.

3.Exploratory Data Analysis (EDA): Conducted statistical and visual analysis to understand dataset characteristics and identify patterns.

4.SQL Analysis: Executed SQL queries for detailed threat analysis, focusing on attack distributions, IP activity, and protocol usage.

5.Power BI Dashboard Development: Designed and implemented interactive dashboards for comprehensive data presentation.

6.Algorithm Implementation: Followed a systematic algorithm for processing network traffic data and deriving actionable intelligence.

7.Experiment Process: Divided into distinct phases for systematic building and evaluation of the intrusion detection system.


Key Results

•Analyzed over 170,000 network traffic records, identifying more than 2,180 attacks.

•Brute Force attacks were the most prevalent (69.13%), followed by XSS (29.91%) and SQL Injection (0.96%).

•Identified high-risk IP addresses and major communication channels (DNS, HTTPS) with heavily utilized TCP and UDP protocols.

•Developed a framework that offers enhanced threat visibility and improved understanding of attack behaviors.


Repository Structure

•CyberSecurityIntrusionDetectionAnalysis_With_SQL_Screenshots.pdf: The original report document.

•cyber_analysis_python.ipynb: Jupyter Notebook containing Python code for data cleaning, EDA, and visualization generation.

•cleaned_cybersecurity_dataset.csv: Cleaned dataset used for analysis.

•Updated_CyberSecurityIntrusionDetectionAnalysis.pdf: The updated report with Python visualizations and refined layout.

•README.md: This file.


How to Use/Setup

1.Clone the repository:
git clone https://github.com/SaiCharan0417/Cyber-Security-Intrusion-Detection-Analysis.git

2.Navigate to the project directory:
cd Cyber-Security-Intrusion-Detection-Analysis

3.
Install necessary Python libraries:
pip install pandas numpy matplotlib seaborn

4.Set up MySQL database: Ensure MySQL is installed and configured. The cyber_analysis_python.ipynb notebook assumes a cleaned_cybersecurity_dataset.csv file is available for import into MySQL.

5.Run the Jupyter Notebook: Open cyber_analysis_python.ipynb in Jupyter and execute cells to reproduce data cleaning, EDA, and Python visualizations.

6.Review Reports: Examine the PDF reports for detailed analysis and findings.

