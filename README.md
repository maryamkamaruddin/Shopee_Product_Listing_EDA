Shopee Listing Exploratory Data Analysis

This project performs Exploratory Data Analysis (EDA) on Shopee product listings crawled between 24 April and 13 May 2023.
The goal is to understand product distribution, seller locations, category trends, price ranges, and estimated revenue across different product categories.

Objectives
- Analyze the number of products crawled per day
- Identify seller locations (Malaysia vs Oversea)
- Explore product category distribution
- Examine price ranges across categories
- Estimate revenue by category

Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

Key Steps
- Data Cleaning
  - Convert date formats
  - Handle missing values
  - Remove duplicate listings
- Feature Engineering
  - Extract seller location from specification
  - Split category hierarchy into main and subcategories
- Exploratory Analysis
  - Product distribution by location and category
  - Price range analysis
  - Revenue estimation
- Visualization
  - Trends in crawling activity
  - Category comparisons
  - Price distributions
 
Key Insights
- Most listings come from Malaysian sellers, especially Selangor and Kuala Lumpur
- Health & Beauty and clothing categories dominate product listings
- Home Appliances generates the highest estimated revenue due to higher unit prices
- Revenue can be driven by high price or high sales volume
