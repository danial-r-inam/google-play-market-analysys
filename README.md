# Google Play Store Apps and Reviews Analysis Project

## Overview

This project entails a comprehensive analysis of the Android app market by examining over ten thousand apps on Google Play across various categories. The objective is to gain insights into the data to develop strategies for app growth and retention. 

## Data Description

The analysis is based on two data files:
- `apps.csv`: Contains details of applications on Google Play, including 13 descriptive features.
- `user_reviews.csv`: Includes 100 reviews for each app, with pre-processed text and new features like Sentiment, Sentiment Polarity, and Sentiment Subjectivity.

## Project Tasks

### 1. Data Cleaning
- Addressed issues in `apps.csv` such as special characters in `Installs` and `Price` columns.
- Performed data cleaning to remove unwanted characters and ensure data consistency.

### 2. Correcting Data Types
- Converted the `Installs` and `Price` columns from object to numeric data types.
- Ensured `Size`, `Rating`, `Installs`, and `Price` are in appropriate formats for analysis.

### 3. Exploring App Categories
- Analyzed the distribution of apps across different categories in Google Play.
- Identified which categories have the highest and lowest share of apps.

### 4. Distribution of App Ratings
- Investigated the average rating across all app categories.
- Visualized the distribution of app ratings to understand general app performance.

### 5. Size and Price Analysis
- Explored the relationship between an app's size and its rating.
- Examined how the price of an app affects its rating and user preference towards free or paid apps.

### 6. Relation Between App Category and Price
- Analyzed how app pricing strategies vary across different categories.
- Identified trends in pricing for specific types of apps, like Medical, Family, and Games.

### 7. Filtering Out "Junk" Apps
- Identified and removed non-functional or joke apps with unreasonable prices.
- Redid visualizations post-cleanup for accurate analysis.

### 8. Popularity of Paid Apps vs Free Apps
- Compared the install rates of paid and free apps.
- Assessed the market performance of different pricing strategies.

### 9. Sentiment Analysis of User Reviews
- Conducted sentiment analysis on user reviews to gauge public opinion on paid vs free apps.
- Utilized sentiment polarity to understand user satisfaction and quality perception of apps.

### 10. Conclusion and Insights
- Derived actionable insights for app development and market strategy.
- Summarized findings to guide future app creators in decision-making.

## Technologies Used
- Data cleaning and manipulation: `pandas`
- Data visualization: `matplotlib`, `seaborn`

## Contributors
- Danial Rashid Inam

---

*Through this analysis, we provide a deep dive into the Android app ecosystem, offering valuable insights for developers and companies in the mobile app industry.*
