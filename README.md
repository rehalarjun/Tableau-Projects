# 🍔 Tableau Projects

This repository contains the Tableau Projects that showcase my skills to create different charts, graphs, maps, dashboards, and stories for visualizing and analyzing data, to help in making business decisions. 

## 📚 Table of Contents
- [Maven Unicorn Challenge](#-maven-unicorn-challenge)
- [Covid-19 and Impact on Malaysia stock market](#covid-19-and-impact-on-malaysia-stock-market)


# 🦄 Maven Unicorn Challenge

## 📚 About Data

Private companies with a valuation over $1 billion as of March 2022, including each company's current valuation, funding, country of origin, industry, select investors, and the years they were founded and became unicorns.

This dataset contains a csv table with 1,074 records, one for each company.

#mavenunicornchallenge

## 💡 Highlights

- Valuations in year 2021 makes up one-third of total valuations since the beginning of time.
- Unicorns in United States and China outperformed the rest of the world with 72% overall valuations.
- Bytedance, SpaceX, SHEIN and Stripe are the most successful unicorns which performed better than an average unicorn at $71 billion.
- Unicorns in AI, E-Commerce, Fintech and Edtech industries are valued higher than the average unicorn at $3.5 billion. 
- A unicorn takes an average of 7 years to attain valuation of $1billion and become a unicorn.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis

📍 Jupyter script: [Notebook](https://github.com/rehalarjun/Tableau-Projects/blob/main/Maven%20Unicorn%20Challenge/Maven%20Unicorn%20Companies%20-%20Data%20Wrangling.ipynb)

📍 Clean Data: [unicorn_companies_clean.csv](https://github.com/rehalarjun/Tableau-Projects/blob/main/Maven%20Unicorn%20Challenge/unicorn_companies_clean.csv)

## 📊 Visualization

Produced a 1-pager dashboard using Tableau.

Tableau: 

![Unicorns-2](https://user-images.githubusercontent.com/81607668/164443885-986bf154-9884-4312-b7cd-a1e128ee24b2.png)


# Covid-19 and Impact on Malaysia stock market

### Business Task
Analyse Covid-19 data and its impact on Malaysia stock market, specifically the KLCI Index Price.

### Data Set
- Covid-19 data from 1 Jan 2020 to 5 Jul 2021 from [Our World in Data](https://ourworldindata.org/covid-deaths).
- Bursa Malaysia KLSE Index Prices from 1 Jan 2020 to 2 Jul 2021 from [Yahoo! Finance](https://finance.yahoo.com/quote/%5EKLSE?p=%5EKLSE).

### Tools
- Microsoft SQL Server 2019 for data analysis - View [SQL scripts](https://github.com/rehalarjun/Tableau-Projects/blob/main/Covid-19%20and%20Impact%20on%20Malaysia%20stock%20market/SQLQuery3.sql)
- Tableau for data visualisation - View

### Dashboard

<kbd><img width="1425" alt="Screenshot 2022-05-18 at 2 54 25 PM" src="https://user-images.githubusercontent.com/81607668/168976440-2a4ceb9f-2459-4b44-91eb-c31e6c526393.png"></kbd>


