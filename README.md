# Supermarket Customers Analysis

## Overview
This project focuses on analyzing customer data from a supermarket to improve marketing and sales strategies. The goal is to understand customer preferences and purchasing behaviors, and to develop more effective marketing strategies tailored to different demographic groups. The analysis includes identifying high-revenue products, understanding customer demographics, and optimizing product bundling strategies.

## Project Structure
The project is structured into several key sections:

1. **Background**: Understanding the need for better marketing strategies and the potential for growth in the supermarket's sales and marketing campaigns.
2. **Problem Statement**: Identifying key issues such as low-revenue products, ineffective marketing strategies, and the need for optimal product bundling.
3. **Data Understanding**: Exploring the dataset, which includes customer demographics, product purchases, and promotional responses.
4. **Data Cleaning and Preprocessing**: Handling missing values, correcting data types, and creating new features such as age and generation categories.
5. **Exploratory Data Analysis (EDA)**: Visualizing data distributions, identifying outliers, and understanding relationships between variables.
6. **Insights and Recommendations**: Drawing conclusions from the analysis and providing actionable recommendations for the supermarket.

## Key Features
- **Data Cleaning**: Handling missing values, correcting data types, and creating new features.
- **Exploratory Data Analysis**: Visualizing data distributions and identifying outliers.
- **Customer Segmentation**: Segmenting customers based on demographics such as age, income, and education.
- **Product Analysis**: Identifying high-revenue and low-revenue products.
- **Marketing Strategy Optimization**: Developing strategies to target different customer segments effectively.

## Data Description
The dataset includes the following key columns:

- **Customer Demographics**: ID, Year of Birth, Education, Marital Status, Income, Number of Children, Number of Teenagers, Enrollment Date, Recency (days since last purchase), Complain.
- **Product Purchases**: Amount spent on wines, fruits, meat products, fish products, sweet products, and gold products.
- **Promotional Responses**: Number of purchases made with a discount, acceptance of various campaign offers, and response to the last campaign.
- **Place of Purchase**: Number of web purchases, catalog purchases, store purchases, and web visits in the last month.
- **Z-Scores**: Z_CostContact and Z_Revenue, indicating the cost and revenue in terms of Z-scores.

## Data Cleaning and Preprocessing
- **Handling Missing Values**: Imputing missing income values based on education levels.
- **Creating New Features**: Adding age and generation categories based on the year of birth.
- **Outlier Detection**: Identifying and handling outliers in income and age using the IQR method.

## Exploratory Data Analysis
- **Income Distribution**: Visualizing the distribution of customer income and identifying outliers.
- **Age Distribution**: Analyzing the age distribution of customers and identifying outliers.
- **Customer Segmentation**: Segmenting customers based on age, income, and education to understand different customer groups.

## Insights and Recommendations
- **High-Revenue Products**: Identifying products that generate the most revenue and focusing on strategies to increase their sales.
- **Low-Revenue Products**: Developing strategies to improve the sales of low-revenue products.
- **Customer Segmentation**: Tailoring marketing campaigns to different customer segments based on demographics and purchasing behavior.
- **Product Bundling**: Optimizing product bundling strategies to encourage cross-category purchases and increase overall sales.

## How to Use
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Ensure you have the necessary Python libraries installed (e.g., pandas, numpy, seaborn, matplotlib).
3. **Run the Notebook**: Open the Jupyter notebook and run the cells to perform the analysis.
4. **Explore the Data**: Use the provided visualizations and insights to understand the customer data and develop marketing strategies.

## Dependencies
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scipy



