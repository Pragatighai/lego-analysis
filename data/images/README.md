LEGO Amazon Sales Analysis Project

A Data-Driven Strategy to Increase LEGO’s Profitability on Amazon1. Description

This project analyzes LEGO’s product performance, pricing patterns, customer behaviour, and online trends to create a data-driven plan for increasing profits on Amazon.
The work includes data exploration, visualizations, competitor comparisons, search trend analysis, and recommendations supported by the CRISP-DM framework.

Our final goal:
Provide LEGO executives with a clear strategy to increase revenue, strengthen customer engagement, and optimize product listings and pricing on Amazon.

2. Motivation

LEGO asked our analytics team to investigate why certain products perform better than others on Amazon and how the company can boost online sales.

This project matters because:

Amazon is one of LEGO’s largest digital sales channels

Consumer behaviour is shifting toward online shopping and digital entertainment

Competitive toy brands often price lower and move faster

Loyal LEGO collectors behave differently than new or casual buyers

Data can uncover patterns that lead to smarter decisions

By understanding pricing, popularity, trends, and seasonal patterns, LEGO can make better business decisions supported by evidence.

3. Mini-Disclaimer

This project is for academic purposes only.
Some data is fictional, publicly sourced, or incomplete.
We do not represent LEGO, Amazon, or any toy manufacturer.

All analysis is exploratory and should not be used for real-world financial decision-making.

4. Installation

To run the Jupyter Notebook, install the following:

pip install pandas numpy matplotlib seaborn scikit-learn notebook


Or install Anaconda, which includes everything needed:
https://www.anaconda.com/products/distribution

To open the notebook:

jupyter notebook


Then open:

lego-analysis.ipynb

5. Sources

Sample data used in this project came from:

Kaggle – Toy Products on Amazon

Kaggle – LEGO Database 2020

Kaggle – LEGO Collector Dataset

Google Trends – “LEGO” 5-year analysis

LEGO Annual Reports

Lionbridge AI Retail & eCommerce Datasets

These sources help analyze pricing, search popularity, product catalog details, and customer preferences.

6. Project Structure

Your GitHub repository should look like this:

lego-analysis/
│
├── data/
│   ├── amazon_toys.csv
│   ├── lego_database.csv
│   ├── lego_collector.csv
│   └── trends_data.csv
│
├── images/
│   └── charts or visualizations
│
├── lego-analysis.ipynb
│
├── README.md
│
└── .gitignore


Folders:

data/ — raw datasets from Kaggle or other sources

images/ — charts exported from the notebook

lego-analysis.ipynb — main notebook with all analysis

README.md — project documentation

.gitignore — hides unnecessary files

7. CRISP-DM Process

We followed the standard CRISP-DM framework for data science projects:

1. Business Understanding

LEGO wants to grow profits on Amazon by improving pricing, product presentation, inventory decisions, and marketing timing.

2. Data Understanding

We explored several datasets covering product names, prices, ratings, categories, release years, and popularity.

3. Data Preparation

Steps include:

cleaning missing values

formatting columns

merging datasets

selecting key variables

generating trend data

4. Modeling

Possible prototypes include:

price prediction model

sales trend forecasting

clustering LEGO sets by buyer type

dashboard for Amazon performance

5. Evaluation

Models were evaluated based on interpretability, usefulness, and predictive power.

6. Deployment

Recommendations include:

using dashboards for monitoring

creating automated pricing tools

integrating search trend alerts
