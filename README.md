# Financial Transactions Dataset Analysis

## Overview

This project involves analyzing a financial transactions dataset to uncover insights into customer spending behavior and credit card usage over a two-year period. The dataset, sourced from Kaggle, includes a variety of transaction types and customer spending patterns. It also reveals potential security vulnerabilities, providing ample opportunities for exploration. The project was carried out in five main phases, from importing and cleaning the data to performing analysis and creating visualizations to reveal trends and anomalies.

## Objectives

- To understand customer spending habits by grouping expenses based on merchant category codes (MCC) and client IDs.
- To identify fraud patterns across various transaction types such as chip, swipe, and online transactions.
- To leverage data visualization techniques to make the analysis more interpretable and actionable.
- To explore the possibilities of enhancing fraud detection and segmentation of customers based on their transaction behavior.

## Summary of Work

1. **Data Import/Export**  
   The dataset was imported from Kaggle using its API, and cleaned data was exported using SQLite for better processing and analysis.
   
2. **Data Cleaning**  
   This phase involved handling missing values, removing unnecessary columns, and correcting inconsistencies in the data to ensure a clean dataset ready for analysis.
   
3. **Data Analysis**  
   Various analyses were performed to understand customer behavior, including identifying personal spending habits, detecting fraudulent transactions, and uncovering trends across different merchant categories.
   
4. **Data Visualization**  
   Graphs and plots were created to visualize customer spending patterns, fraud detection, and the distribution of transaction types, providing clear insights into the data.

## Key Findings

- **Customer Spending Analysis**:  
  Spending was evaluated across different categories, with significant amounts in "Women’s Ready to Wear Stores" and "Wholesale Clubs."
  
- **Top MCC Categories**:  
  The highest volume of transactions occurred in the "money transfer" category, which includes one-to-one payment services and wire transfers. Other notable categories included groceries and drug pharmacy stores.
  
- **Fraud Analysis**:  
  Fraudulent activity was identified in all transaction types, including chip, swipe, and online transactions.

## Dataset Details

The dataset was chosen for its wide range of transaction types, spending habits, and potential security risks. It provides a solid foundation for further investigation, especially for fraud detection and customer segmentation.

The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Financial Transactions Dataset: Analytics](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets/data)

## Challenges Faced

- Effectively handling missing and duplicate data during the cleaning process.
- Interpreting unexpected trends in fraud data and spotting potential false positives.
- Importing large datasets directly from Kaggle using APIs, which required managing the size and complexity of the data.
- Integrating Python-based analysis with SQL for data storage, enabling more advanced querying and exploration.

## Topics Researched

- How MCC codes categorize financial transactions and influence spending patterns.
- Using statistical techniques (with pandas and other libraries) to clean, summarize, and visualize transaction data.

## Potential Project Expansions

- **Enhanced Fraud Detection Systems**: Develop systems that can predict fraudulent activity in real time.
- **Customer Segmentation**: Apply clustering algorithms to categorize customers based on spending behaviors, identifying distinct spending patterns.
- **Seasonal Analysis**: Analyze transaction data across different states and create heatmaps to gain a better understanding of consumer behavior throughout the year.
- **SQL-based Analysis**: Further integrate the cleaned dataset into a more complex SQL-based system to enable deeper analysis and reporting.
