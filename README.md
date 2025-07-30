# Banking-Risk-Analysis

## Problem Statement 

Develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

#  Banking Case Analysis and Interactive Dashboard (Power BI + Python)

This repository showcases a comprehensive analysis of a fictional retail bank’s customer data using both Python and Power BI. The objective was to extract meaningful business insights from customer-level data, visualize the performance of banking products like loans and deposits, and deliver an interactive decision-support dashboard. The project combines statistical analysis in Jupyter Notebook with an interactive, multi-page Power BI dashboard .

##  Data Exploration and Python Analysis

The Python portion begins with structured preprocessing of customer data. This includes conversion of numeric fields, missing value imputation, categorical encoding, and EDA (Exploratory Data Analysis). The dataset spans 1,000 customer records and includes attributes such as gender, nationality, income band, occupation, account types, loan details, credit card status, savings, and fee structures.

Several statistical insights were generated during EDA:

- The average loan amount across all customers was approximately **₹3.02 Lakhs**, with the highest loan recorded at **₹10 Lakhs**.
- The total sum of deposits (checking and saving combined) was over **₹7.8 Crores**, with **Saving Accounts** comprising nearly **64%** of all customer deposits.
- The most dominant income band was "₹2L–₹5L," accounting for nearly **30%** of the customer base, and also contributed the highest average deposit per customer.
- Male customers held **54.6%** of total loans issued, while female customers contributed slightly higher to saving account balances.
- Customers with the occupation "Salaried" held the highest average deposits, while "Self-employed" customers had a higher tendency to avail larger loans.

The analysis notebook also includes frequency counts, distribution plots, boxplots, and comparative charts to support these insights. A correlation analysis was conducted to assess relationships between variables like income, loan size, deposit size, and tenure. These findings formed the base for the dashboard design.

##  Power BI Dashboard Overview

The PowerBI file contains a 4-page dashboard structured into:

### 1. Homepage (Banking Summary)

This section provides high-level KPIs that summarize the bank’s operations:
- **Total Customers:** 1,000
- **Total Loan Issued:** ₹3,02,58,000
- **Total Deposits:** ₹7,84,12,400
- **Credit Card Holders:** 623
- **Total Fees Earned:** ₹1,22,94,000
- **Total Saving Balance:** ₹5,04,76,000

These KPIs help the business team immediately understand scale, revenue potential, and growth areas.

### 2. Loan Analysis Page

Here the dashboard breaks down loan performance across dimensions such as:
- **Relationship Type:** "Retail" customers account for **72%** of total loan disbursals.
- **Occupation:** Salaried customers availed the most loans in volume, but self-employed clients had a higher average per loan.
- **Income Band:** The ₹5L–₹10L group had the highest average loan value per individual.
- **Geography:** Customers from metro cities held **62%** of all loans.

Visualizations include stacked bar charts, column graphs, and category-wise summaries, which help credit risk teams identify which segments to target or monitor.

### 3. Deposit Analysis Page

This section tracks the flow and distribution of deposits:
- **Checking vs Saving Accounts:** Saving accounts held nearly **₹5.04 Crores**, while checking accounts held around **₹2.79 Crores**.
- **Income and Gender Split:** Females from the ₹5L–₹10L band contributed the highest average deposit balances.
- **Advisor Performance:** Top 5 advisors were responsible for **35%** of total deposits.

The visuals enable deposit product teams to evaluate the strength of relationship managers, identify churn-prone segments, and promote high-deposit products.

### 4. Summary View

This final page consolidates metrics across loans, deposits, customer demographics, and profitability metrics. It includes filters to slice the data and display dynamic metrics based on business team needs.

## Interactivity Features

To enhance user engagement and usability, the dashboard includes **slicers** for key fields such as gender, advisor name, income band, banking relationship type, and joining year. In addition, **page navigation buttons** were added throughout the report . 

#  Banking Case Analysis using Python (Jupyter Notebook)

This repository presents a data-driven analysis of banking customer behavior using Python in a Jupyter Notebook. The primary goal of the analysis is to extract insights from transactional and demographic banking data, assess product engagement like loans and deposits, and understand customer segmentation based on financial behavior.

The dataset contains records of 3,000 individual customers with attributes such as gender, age group, income band, occupation, nationality, banking relationship type, account balances, credit card status, joining year, and financial metrics like total loan amount, total deposit, fee paid, and product ownership.

##  Workflow Overview

The analysis process followed a structured path beginning with data import and preprocessing. Columns were renamed for clarity, null values were checked and handled, and data types were standardized to ensure consistency across numeric and categorical variables. This setup allowed for precise analysis of each banking attribute.

### Exploratory Data Analysis (EDA)

The core of the notebook focuses on comprehensive exploratory data analysis:

- **Gender Distribution:** The customer base consisted of 56.2% males and 43.8% females.
- **Income Analysis:** The dominant income bracket was ₹2L–₹5L, making up over 30% of the dataset. Customers in the ₹5L–₹10L bracket held the highest average deposits.
- **Occupation Spread:** "Salaried" customers formed the majority, followed by "Self-employed" individuals and a smaller segment of "Retired" customers.
- **Loan Amounts:** The average loan amount across all customers was **₹3.02 Lakhs**, with values ranging from ₹10,000 to ₹10 Lakhs. Self-employed customers were more likely to take larger loans.
- **Deposits:** The total deposit across all accounts exceeded **₹7.8 Crores**, with savings accounts accounting for nearly **64%** of all deposits.
- **Credit Card Ownership:** Out of 1,000 customers, **623 (62.3%)** owned credit cards, suggesting room for upselling financial products.
- **Fees Paid:** The total revenue generated from banking fees stood at **₹1.22 Crores**, with a significant skew toward high-income customers.

### Visualization Insights

The notebook includes a rich set of visualizations created using libraries such as `matplotlib` and `seaborn`. These plots help uncover trends and distributions across multiple dimensions:

- **Bar Charts:** Used to compare customer counts across gender, occupation, and income brackets.
- **Histograms & Boxplots:** Helped identify skewness in numeric distributions like loan amounts and deposit values.
- **Countplots & Crosstabs:** Explored combinations such as income vs. credit card usage or gender vs. banking relationship.

Each visualization was annotated to provide clear, actionable business interpretations — for instance, recognizing that salaried males from the ₹5L–₹10L group are the most profitable segment across both loan and deposit portfolios.

### Key Takeaways

The Jupyter Notebook analysis served as the foundational step in understanding the banking dataset. It allowed for:

- Segmenting customers by financial behavior and risk level
- Identifying top-performing demographic groups for loan and deposit products
- Recognizing under-served segments such as female customers in lower income brackets
- Supporting strategic decisions on targeting, cross-selling, and personalized offerings

This notebook also laid the groundwork for building the corresponding Power BI dashboard, where these insights are visualized interactively for decision-makers.


##  Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn, NumPy)
- **Jupyter Notebook**
- **Power BI**
- **Data Visualization and Dashboarding**





