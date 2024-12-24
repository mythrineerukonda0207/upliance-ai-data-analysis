# Data Analytics Intern Assignment

## Overview
This repository contains the solution for the **Data Analytics Intern Assignment** provided by [upliance.ai](http://upliance.ai). The project focuses on analyzing user behavior, cooking preferences, and order trends using the datasets provided. The goal is to generate insights and recommendations for improving the business operations of upliance.ai.

## Datasets
The project involved working with the following datasets:
1. **UserDetails**: Includes user demographics, favorite meals, and total orders.
2. **CookingSessions**: Logs of cooking activities with details about dishes, session durations, and ratings.
3. **OrderDetails**: Information about user orders, including dish names, amounts, and statuses.

## Objectives
The key objectives of this assignment were:
1. **Data Cleaning and Merging**: 
   - Preprocess the datasets to address missing or inconsistent data.
   - Merge datasets to establish relationships between users, cooking sessions, and orders.

2. **Data Analysis**:
   - Identify popular dishes and analyze user preferences.
   - Examine the relationship between cooking sessions and user orders.
   - Explore demographic trends and their influence on user behavior.

3. **Visualization**:
   - Create visualizations to represent insights effectively.

4. **Report**:
   - Summarize the findings and provide business recommendations.

## Key Insights
1. **Popular Dishes**: 
   - *Caesar Salad*, *Spaghetti*, and *Grilled Chicken* emerged as the most popular dishes across cooking sessions and user orders.
2. **Demographics**: 
   - Dinner was the most popular meal among users aged 28–35, while younger users (under 30) preferred breakfast sessions.
   - Users in metropolitan areas like New York and Los Angeles demonstrated higher engagement in cooking sessions and order completions.
3. **Cooking Sessions and Orders**: 
   - Sessions with higher ratings (4.5+) had a significantly higher order completion rate.
   - Shorter cooking sessions (under 30 minutes) were associated with increased user satisfaction and repeated orders.
4. **Revenue Trends**:
   - Evening orders (during dinner sessions) contributed the highest revenue.

## Tools and Technologies
- **Python**: For data processing and analysis.
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn.
- **Power BI/Excel**: For creating visualizations.
- **GitHub**: To manage project files and documentation.

## Project Structure
📂 Assignment
├── 📂 DataSets
│   ├── UserDetails.csv
│   ├── CookingSessions.csv
│   ├── OrderDetails.csv
├── 📂 Analysis
│   ├── analysis_script.ipynb
├── 📂 Visualizations
│   ├── popular_dishes.png
│   ├── orders_by_age.png
├── report.pdf
├── README.md

