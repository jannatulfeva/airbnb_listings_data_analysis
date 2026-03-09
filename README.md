# airbnb_listings_data_analysis

Analyzing Airbnb listings to uncover pricing trends, host behaviors, and neighborhood dynamics using Python.

# Overview
This project analyzes an Airbnb "Open Data" dataset for New York City to identify patterns in rental prices and neighborhood popularity. The goal is to clean messy real-world data and use exploratory data analysis (EDA) to generate insights into the short-term rental market.

# Business Objective
The main objectives of this project are:

- Perform comprehensive data cleaning on a large-scale rental dataset.

- Analyze average listing prices across different NYC boroughs.

- Identify trends in the number of reviews over time.

- Compare host verification status against property ratings.

- Evaluate how property types and construction years impact pricing.

# Dataset
The project uses the Airbnb_Open_Data.csv dataset, which contains over 100,000 transactional records.

Key columns include:

- neighbourhood group

- room type

- construction year

- price and service fee

- number of reviews and review rate number

- host_identity_verified

# Tools & Technologies
The analysis was performed using:

- Python

- Pandas & NumPy

- Matplotlib & Seaborn 

- Jupyter Notebook

# Data Cleaning & Preparation

Before performing analysis, several preprocessing steps were completed:

- Transformed price and service fee from currency strings to numeric values.

- Handled null values in critical columns like last review and reviews per month.

- Dropped unnecessary columns like license and house_rules due to insufficient data.

- Converted last review to datetime format for time-series analysis.

# Key Findings

- Regional Pricing: Average prices vary significantly across the five NYC boroughs.

- Seasonal Trends: A line chart of reviews over time shows specific periods of high booking activity.

- Host Trust: Analysis compares whether verified hosts receive higher review ratings than unverified ones.

- Property Age: Investigation into how the year of construction relates to the listing price

# Visualizations

<img width="1128" height="681" alt="Screenshot 2026-03-09 151130" src="https://github.com/user-attachments/assets/b8a4a4b8-5cde-4da3-910c-932fb758e77c" />

<img width="975" height="643" alt="Screenshot 2026-03-09 151150" src="https://github.com/user-attachments/assets/1b672556-2232-4549-ba7a-b8a75a95d1b4" />

<img width="1385" height="860" alt="Screenshot 2026-03-09 151317" src="https://github.com/user-attachments/assets/e4293673-0778-4b3b-9dcc-2ee6aaacac1e" />

<img width="1087" height="704" alt="Screenshot 2026-03-09 151337" src="https://github.com/user-attachments/assets/93b96bde-8e68-44db-80a2-8f57b07c6096" />

<img width="1334" height="683" alt="Screenshot 2026-03-09 151426" src="https://github.com/user-attachments/assets/4d741531-a93a-4cb7-8b0f-131300651676" />

# How to Run This Project
Clone the repository
git clone https://github.com/jannatulfeva/airbnb_listings_data_analysis.git

Install required libraries
pip install pandas numpy matplotlib seaborn

Open and run the notebook
Run the notebook: airbnb_listings_data_analysis.ipynb












