🏠 Luxury Housing in Bangalore Analysis

This project performs exploratory data analysis (EDA), data cleaning, feature engineering, and interactive dashboard development using Power BI on a dataset of luxury housing properties in Bangalore, India.
The goal is to uncover trends in pricing, demand, and buyer behavior, and present insights through a professional BI dashboard.

🧰 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly Express

Power BI

📌 Project Overview

This project demonstrates an end-to-end data analytics workflow:

Data cleaning and preprocessing using Python

Exploratory Data Analysis (EDA)

Feature engineering for business insights

Interactive visualization using Power BI

The cleaned dataset is used to build a Power BI dashboard that enables stakeholders to explore trends across micro-markets, configurations, ticket prices, and buyer types.

📂 Dataset

The analysis is based on the Luxury_Housing_Bangalore.csv dataset, which includes:

Property ID

Micro Market

Project Name

Developer Name

Unit Size (Sqft)

Configuration (3BHK, 4BHK, etc.)

Ticket Price (Cr)

Transaction Type

Buyer Type

Purchase Quarter

Connectivity Score

Amenity Score

Possession Status

Sales Channel

NRI Buyer (Yes/No)

Locality Infrastructure Score

Average Traffic Time (Min)

Buyer Comments

⚙️ Features and Steps
1. Data Loading

Loads Luxury_Housing_Bangalore.csv into a Pandas DataFrame.

2. Data Preprocessing

Duplicate Removal

Data Type Conversion

Column Name Normalization

Text Standardization

Negative Value Handling

Missing Value Imputation

Ticket Price Conversion to Numeric Format

3. Feature Engineering

Price per Sqft

Year & Quarter Extraction

Booking Flag (Primary Transaction Indicator)

4. Exploratory Data Analysis (EDA)

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Visualizations using Matplotlib & Seaborn

5. Saving Cleaned Data
6. Final cleaned dataset saved as:

luxury_housing_cleaned.csv

📊 Power BI Dashboard

The cleaned dataset is imported into Power BI to create an interactive dashboard.

🔹 Dashboard Features

Market-wise booking trends (Line Chart)

Ticket price vs unit size analysis (Scatter Plot)

Configuration demand (Bar Chart)

Developer performance comparison

Quarter-wise sales trends

Interactive slicers for:

Micro Market

Configuration

Year

Buyer Typedashboard

📈 Output

Cleaned and structured dataset

Statistical and visual insights

Interactive Power BI dashboard

Final cleaned dataset saved as:

luxury_housing_cleaned.csv
