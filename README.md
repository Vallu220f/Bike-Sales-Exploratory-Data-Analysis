# Bike-Sales-Exploratory-Data-Analysis

Bike Sales Exploratory Data Analysis (EDA)
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset of bike sales in India. The goal is to uncover market trends, customer preferences, and sales performance across different brands, categories, and regions.

Project Overview
The analysis involves data cleaning, handling missing values, identifying outliers, and visualizing key performance indicators (KPIs) like revenue, units sold, and customer ratings.

Dataset Description
The dataset contains 10,620 rows and 20 columns, including:

Identification: Order_ID, Sale_Date

Product Details: Brand, Model, Category, Color, Engine_CC, Fuel_Type, Transmission, Mileage_KMPL

Pricing & Sales: Ex_Showroom_Price_INR, Discount_INR, Units_Sold, Revenue_INR

Location: State, City

Customer Info: Sales_Channel, Customer_Segment, Payment_Method, Customer_Rating

Key Analysis Steps
Data Loading & Inspection: Initial look at the data structure using .info() and .head().

Handling Missing Data: Identified null values in critical columns like Model, Color, Mileage_KMPL, and Customer_Rating.

Duplicate Removal: Detected and handled 420 duplicate entries.

Outlier Detection: Implemented an Interquartile Range (IQR) function to identify anomalies in numeric columns like prices and discounts.

Statistical Summary: Generated descriptive statistics to understand the mean, standard deviation, and range of engine capacity, mileage, and revenue.

Technologies Used
Python

Pandas: Data manipulation and cleaning.

NumPy: Numerical computations.

Matplotlib & Seaborn: Data visualization.

How to Run
Ensure you have Python installed.

Install required libraries:

Bash
pip install pandas numpy matplotlib seaborn
Place the Bike_Sales.csv file in the project directory.

Open and run the EDA Project.ipynb notebook.

Key Insights (Sample)
Brands Analyzed: KTM, Hero, Suzuki, Royal Enfield, Bajaj, Honda, and Jawa.

Customer Segments: Includes Students, Delivery Executives, Working Professionals, and Businessmen.

Fuel Types: Analysis covers Petrol, BS6 Petrol, and Electric variants.
