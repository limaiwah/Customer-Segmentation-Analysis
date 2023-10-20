## Customer Segmentation Analysis

### Introduction
The goal is of this project is to perform customer segmentation analysis based on the online transaction history of an e-commerce platform to observe the trend and pattern of the customer purchase. Data used for this analysis is over the period of one year, from 01/12/2010 to 09/12/2011. 

### Project Scope
Project is divided into 3 sections:
1. Exploring and cleaning of data
2. Data Analysis and Visualisation 
3. Cohort Analysis, RFM Analysis and KMean Analysis

There are 2 extra sections in the project:
1. Data Exploration using SQL to answer business questions
2. Visualization of the Summary of the data using Tableau


### Dataset Overview
The following attributes are extracted from 2 different tables (stock_description and online_transactions) in AWS Redshift:
- **stock_code**: product code
- **description**: description of the product
- **quantity**: quantity purchased by customer
- **invoice_date**: the date and time transactions was generated
- **price**: unit price of the product
- **customer_id**: customer number assigned to each customer
- **country**: name of country where customer is from

### File Descriptions
- Notebooks
  - 01_exploring_and_cleaning_data
  - 02_data_analysis_and_visualization
  - 03_cohort_rfm_kmeans_analysis
  - analysing_data_with_sql

### Requirements
- Jupyter notebook
- AWS Redshift connection details

### View Summary of Data in [Tableau](https://public.tableau.com/app/profile/ai.wah.lim/viz/CustomerSegmentationAnalysis_16974510680840/Dashboard1?publish=yes)# Customer-Segmentation-Analysis
