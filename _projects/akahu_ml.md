---
title: "Exploring the Art of Financial Data Analysis through Machine Learning"
excerpt: "Analysing monthly spending trends using Machine Learning to Categorise Transactions"
collection: projects
---

Ever pondered how machine learning can streamline financial data analysis? Immerse yourself in our innovative project where we employ sophisticated techniques to automatically categorize financial transactions. Using the robust Naive Bayes classification method, we decode transaction descriptions into actionable categories such as income, expenses, fees, and more. Witness how we transform raw data into insightful metrics, enhancing financial management with intuitive clarity. Embark on a journey where data science meets everyday finance, paving the path to smarter financial decisions.

## Project Workflow:

In this project, I seamlessly connected to the Akahu API to retrieve transaction data using Python scripts. Establishing a secure link between banking apps and Akahu enabled seamless data extraction via API, presenting transaction details in a structured JSON format. To safeguard sensitive information, I leveraged Windows environment variables to store API and user keys, ensuring privacy and security.

## Data Processing:

Using Python, I developed a script (connect_to_akahu.py) that intelligently appends new transactions to an existing file (transactions.json) rather than retrieving all data afresh. Subsequently, I implemented natural language processing and keyword matching techniques to categorize transactions without predefined labels, generating valuable training data for the Naive Bayes classification model.

## Insightful Reporting:

The cleaned and categorized data is seamlessly integrated into a Power BI report, leveraging a star schema for optimal performance. The report offers comprehensive insights into key performance indicators (KPIs) such as total spending trends, average daily expenditures, maximum transactions, and frequency of transactions. These metrics provide a detailed overview of monthly transactions with comparative analysis to previous months, facilitating informed decision-making on spending habits.

## Automation for Efficiency:

To ensure consistent updates, I established a scheduled task in Windows Task Scheduler, automating the execution of scripts on a monthly basis. This automated workflow guarantees timely data refreshment ahead of reporting, maintaining data accuracy and relevance.

# Report
<br/><img src='/images/akahu_monthly_report.png'>"

# Github Repo
[Link to github repo](https://github.com/Pirunthan-bot/akahu-ml-transactions)