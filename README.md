# Fetch Rewards Data Analysis Project

## Project Overview
This project involves a comprehensive analysis of transaction data for Fetch Rewards, focusing on identifying data quality issues, generating insights, and communicating findings to stakeholders. The analysis includes SQL queries, data exploration, visualization, and reporting based on three datasets provided in CSV format.

## Project Structure
- **USER_TAKEHOME.csv**: Contains user data, including demographics and account details.
- **TRANSACTION_TAKEHOME.csv**: Includes transaction-level data with details such as product purchases, dates, and sales amounts.
- **PRODUCTS_TAKEHOME.csv**: Lists products with details like brand, manufacturer, and product categories.

### Additional Files
- **email.pdf**: The final email/Slack message summarizing the analysis results, data quality issues, and insights communicated to stakeholders.
- **fetch_assignment.ipynb**: A Jupyter Notebook containing visualizations, data quality checks, and insights based on the exploration and analysis of the provided datasets.
- **fetch_assignment.pdf**: Document answering questions related to data quality, trends, and actionable insights.

## Project Requirements
This project uses:
- **Python 3.x**
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **SQLAlchemy** or a similar SQL query runner for executing queries
- **Jupyter Notebook** for interactive data exploration

## Key Tasks
### Data Exploration and Quality Check
- Conducted a thorough review of all datasets to identify data types, missing values, and anomalies.
- Highlighted inconsistencies, such as unexpected data types (e.g., dates stored as strings) and fields with excessive missing values (e.g., MANUFACTURER and BRAND fields in PRODUCTS_TAKEHOME.csv).
- Summarized findings on data quality issues and areas needing improvement, documented in the final email (see email.pdf).

### Closed-Ended SQL Queries
- Executed SQL queries to answer specific business questions, such as identifying top brands by receipts and analyzing sales percentages by generation.
- SQL scripts to answer each question were designed to handle data inconsistencies and missing values.
- Query results were verified and cross-referenced for accuracy (see code and results in fetch_assignment.ipynb).

### Open-Ended Analysis and Visualization
- Generated insights on power users and top-performing brands in specific product categories.
- Visualized data trends, including demographic preferences in spending categories, using graphs in the Jupyter Notebook.
- Addressed open-ended questions with reasonable assumptions where data was ambiguous, documented for transparency.

### Stakeholder Communication
- Prepared a stakeholder-friendly summary (see email.pdf), outlining:
  - Data quality issues
  - An interesting data trend (e.g., high millennial spending in Health & Wellness)
  - Follow-up questions and requests for additional data clarification

## Getting Started
### Setup
1. Clone this repository.
2. Install necessary packages using the following command:
   ```bash
   pip install -r requirements.txt
