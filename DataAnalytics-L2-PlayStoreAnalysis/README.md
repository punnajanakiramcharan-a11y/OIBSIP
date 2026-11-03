# Unveiling the Android App Market - Google Play Store Analysis

## Objective
Perform a comprehensive data analysis of the Google Play Store ecosystem, cleaning messy real-world data, exploring app categories, analysing ratings and pricing trends, and conducting sentiment analysis on user reviews.

## Dataset
Google Play Store Apps dataset, sourced from Kaggle (by Lavanya Gupta). Includes two files: app details and user reviews.

## Analysis Performed
1. Data cleaning: fixed Installs, Price, and Reviews columns (stored as text with special characters), removed a corrupted row and duplicates
2. Handled remaining missing values across Rating, Type, Content Rating, Current Ver, Android Ver
3. Category analysis: distribution of apps across categories
4. Ratings analysis: distribution and average rating by category
5. Size vs Installs correlation analysis
6. Pricing analysis: free vs paid split, price distribution for paid apps
7. Sentiment analysis on user reviews (overall and by category)
8. Written observations after each chart
9. Conclusion with 3 actionable insights for app developers

## Key Findings
- Family, Game, and Tools are the most saturated categories
- Events, Education, and Art and Design have the highest average ratings
- The vast majority of paid apps are priced under 10 dollars
- Comics and Auto and Vehicles categories show the highest positive sentiment

## Tools Used
Python, pandas, numpy, matplotlib, seaborn, Google Colab

## Files in this folder
- `play_store_analysis.ipynb` - the Jupyter notebook with all code and analysis
- `README.md` - this file
