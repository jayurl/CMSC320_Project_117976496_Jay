Navigating the Nasdaq: A Data-Driven Exploration of Tech Sector Dynamics and Investment Opportunities

Overview:
In an era where technology profoundly influences every aspect of society, understanding the dynamics of tech companies within the stock market is more crucial than ever. This project focuses on analyzing the Nasdaq, a stock ETF renowned for its emphasis on technology-oriented stocks, and contrasting it with broader market indices like the S&P 500. Through this analysis, the project aims to identify patterns and trends within the top 50 tech companies and leverage these insights to assess the broader Nasdaq stock exchange, pinpointing similar, yet lesser-known firms with strong growth potential.

Features:
Data Curation: The project uses datasets comprising information on the top 50 technology companies listed on the Nasdaq and a broader list of over 3000 Nasdaq-listed companies. The data includes metrics such as sub-sector classification, founding year, revenue, market cap, and employee size.

Research Questions:
Historical Revenue Trends: Are companies founded before 2000 more financially successful than those founded afterward?
Sector Performance: Does the sub-sector classification influence a company's financial success?
Revenue and Market Cap Correlation: Is there a correlation between a company’s revenue and its market capitalization?

Machine Learning Models:
Classification Model: Categorizes companies into high-growth and low-growth based on financial metrics.
Regression Model: Forecasts the financial performance of companies to identify promising investment opportunities.

Data Sources:
Top 50 Tech Companies Dataset: Kaggle: Top 50 US Tech Companies 2022-2023
Nasdaq Stocks Dataset: StockAnalysis.com Screener

Project Structure:
Data Preparation: Cleaned and preprocessed the datasets to align them for analysis, including normalizing revenue and market cap values.
Exploratory Data Analysis (EDA): Conducted statistical tests (T-test, ANOVA, Chi-Squared) to investigate the research questions, identifying key trends and outliers.

Modeling:
Built and evaluated machine learning models, including logistic regression for classification and linear regression for predicting future growth.
Applied models to the Nasdaq dataset to discover potential high-growth stocks.
Results Analysis: Evaluated model performance using metrics such as precision, recall, F1-score, and mean squared error. Visualized the results with confusion matrices and regression plots.
