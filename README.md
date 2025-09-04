# Apple App Store Apps Exploratory Data Analysis

## Introduction
This project explores the Apple App Store dataset to uncover insights about app ratings, reviews, pricing, and categories. The goal of the analysis is to better understand the characteristics of iOS applications, discover patterns in user engagement, and evaluate how features like price, size, and category affect app performance.

## Dataset
The dataset includes key information about iOS apps such as:
- App name  
- Category  
- Size in bytes  
- Price  
- User ratings (overall and by version)  
- Number of reviews (overall and by version)  
- Free or paid indicator  

## Data Cleaning
Several preprocessing steps were applied:
- Capped app sizes to 3 GB to remove unrealistic outliers.  
- Limited app prices to a maximum of 100 USD for meaningful comparisons.  
- Applied log transformation to skewed features such as number of reviews.  
- Separated free and paid apps for better insights.  
- Removed duplicate entries when creating top lists.  

## Analysis
The analysis included:

### 1. Univariate Analysis
- Distribution of app sizes, prices, ratings, and reviews.  
- Log transformations to handle heavy skewness.  

### 2. Bivariate Analysis
- Relationships between price, size, reviews, and ratings.  
- Impact of pricing on user satisfaction.  

### 3. Multivariate Analysis
- Ratings by category and app type (free vs paid).  
- Scatter plots of price, reviews, and user ratings.  

### 4. Correlation Analysis
- Explored relationships between numeric features.  
- Found weak correlations overall, with only slight positive correlation between app size and price.  

## Key Insights
- Over half of apps had a rating of 0, meaning they were unrated.  
- Free apps dominated in popularity, especially among the most reviewed apps.  
- Pricing had very little correlation with user ratings.  
- Games, Entertainment, and Social Networking categories were the most dominant in top apps.  
- Apps with millions of reviews maintained high ratings between 4.6 and 4.9.  

## Final Thoughts
This project highlights patterns in app store data and demonstrates how pricing, size, and categories affect user engagement. The insights can be useful for developers and businesses to understand user preferences and market trends.
