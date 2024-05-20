# Executive-Dashboard

## Overview
Plot the correlations for each marketing channel compared to Sales

<img src="https://github.com/wylee3/marketing-linear-regressions/blob/main/Facebook_feed_Impr.png" width="500" />

## Code Used:
* Python: python 3.11.8
* Packages: numpy, pandas, seaborn, matplotlib, sklearn, os
* Anaconda 2.6.0
* Jupyter 7.0.8

## Data Sources
* Saleforce
* Google Analytics
* Facebook Ads Manager

*Data privacy through one or many of the following steps applied to original data: random functions, deletion/addition, other math functions*

## Data Cleaning
* SQL
* Excel

Data was imported into SQL Server Management Studio where specific columns were taken from multiple tables, and then joined into a master table. 
Exported as a csv file. This master file was initially created for another project but served well for these correlations. To work with this data for 
this project, it was hand-edited in Excel to delete columns for individual channel-only csv files.

[SQL file](https://github.com/wylee3/marketing-linear-regressions/blob/9a1fc2df0952b384e930bc9e68a45cb49eb52003/SQL-CorrelationPrep_v3-portfolio.sql)

## Exploratory Data Analysis (EDA)
This gave insight into the best correlating channel which went against marketing's pre-determined gut feelings.

## Model Building
