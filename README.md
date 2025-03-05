# Statistics and A/B Testing
 This repository contains an A/B testing analysis on bank deposit campaigns using the bank-full.csv dataset. The analysis evaluates whether the number of campaigns (campaign) influences a user's decision to open a deposit account (y).

# Bank Marketing Dataset  

## Overview  
This dataset contains information on direct marketing campaigns conducted by a Portuguese banking institution. The campaigns were based on phone calls, with multiple contacts sometimes required to determine whether a client would subscribe to a term deposit. The classification goal is to predict whether a client will subscribe (`y` variable: "yes" or "no").  

## Dataset Information  
- Source: Downloaded from [Kaggle](https://www.kaggle.com/code/muhammedsal98/classification-in-bank-marketing/input?select=bank-full.xlsx).  
- Original Paper:  
  - Moro et al., 2011 - *Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology*. *Proceedings of the European Simulation and Modelling Conference - ESM'2011*, pp. 117-121. [EUROSIS](https://www.eurosis.org).  
- Number of Instances:  
  - `bank-full.csv`: 45,211 instances (full dataset, ordered by date from May 2008 to November 2010).  
  - `bank.csv`: 4,521 instances (10% of `bank-full.csv`, randomly selected for computational efficiency).  
- Number of Attributes: 16 input features + 1 output variable.  

## Features  
### **Bank Client Data**  
1. **age** (numeric) – Client's age.  
2. **job** (categorical) – Type of job (*admin, technician, management, etc.*).  
3. **marital** (categorical) – Marital status (*married, single, divorced*).  
4. **education** (categorical) – Level of education (*primary, secondary, tertiary*).  
5. **default** (binary) – Has credit in default? (*yes, no*).  
6. **balance** (numeric) – Average yearly balance (in euros).  
7. **housing** (binary) – Has a housing loan? (*yes, no*).  
8. **loan** (binary) – Has a personal loan? (*yes, no*).  

### **Last Contact Information**  
9. **contact** (categorical) – Communication type (*telephone, cellular, unknown*).  
10. **day** (numeric) – Last contact day of the month.  
11. **month** (categorical) – Last contact month (*jan, feb, mar, ..., nov, dec*).  
12. **duration** (numeric) – Last contact duration (in seconds).  

### **Campaign-Related Attributes**  
13. **campaign** (numeric) – Number of contacts performed during this campaign (including last contact).  
14. **pdays** (numeric) – Days since the client was last contacted from a previous campaign (-1 means never contacted before).  
15. **previous** (numeric) – Number of contacts performed before this campaign.  
16. **poutcome** (categorical) – Outcome of the previous campaign (*success, failure, other, unknown*).  

### **Target Variable**  
17. **y** (binary) – Has the client subscribed to a term deposit? (*yes, no*). 

# Files
| Process | File+Link |
|--------------------------|------------|
| Basic Statistics | [Link](https://github.com/astynabilah/Statistics-and-A-B-Testing/blob/main/ basic-statistics.ipynb) |
| A/B testing using Logistic Regression | [Link](https://github.com/astynabilah/Statistics-and-A-B-Testing/blob/main/AB%20Testing%20using%20Logistic%20Regression.ipynb) |