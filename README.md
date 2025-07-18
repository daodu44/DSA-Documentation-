# DSA-Documentation-
This is where I started my portfolio building while taking my Data Analysis class with the Incubator 

This is where I started my portfolio building while taking my Data Analysis class

I have learnt quite a number of things ranging from Ms Excel to SQL and now to my Portfolio Building 

## Project Topic: AMAZON PRODUCT REVIEW ANALYSIS

### Project Overview 
As a Junior Data Analyst at RetailTech Insights, I contributed to a data-driven initiative focused on analyzing product and customer review data from major e-commerce platforms like Amazon. The analysis involved cleaning and transforming raw datasets, conducting sentiment analysis, generating performance metrics (e.g., review count by category, average rating, discount impact), and building dashboards for easy stakeholder interpretation.

### Data Source
The primary source if Data used is palmoriagroupemp-data.csv 

### Tools Used
- Ms Excel for Data Cleaning [Download here](http://www.microsoft.com)
     - For Data Collection 
     - For Data Cleaning
       1. Data Manipulation
       2. Data Munching
- Microsoft Power BI (for creating report)

## Data Cleaning and Preparation 
In the initial phase of the Data cleaning and preparations, we perform the following action; 
1. Data loading and inspection
2. handling missing variable Data
3. Cleaning and formatting

### Exploratory Data Analysis 
he goal of the EDA was to understand the structure, quality, and trends in the product and customer review data before diving into deeper analytics. Here’s a breakdown of the key steps taken:

## 1. 🔍 Data Understanding
Datasets used:

products.csv – product ID, name, category, price, discount, etc.
reviews.csv – review ID, product ID, rating, review text, sentiment, etc.
Initial Checks:
Verified row count and column data types.
Explored null values and inconsistencies (e.g., missing ratings or duplicate reviews).

## 2. 🧼 Data Cleaning
Removed duplicates and handled missing data using imputation or row deletion depending on severity.

Normalized text fields (e.g., product names, review texts) for uniformity.
Converted data types (e.g., price and discount fields to numeric).
Created derived fields like:
discount_percent
review_length
sentiment_score (via TextBlob/VADER)

## 3. 📈 Univariate Analysis
Ratings Distribution: Majority of ratings fell between 3–5 stars, with a long tail of lower ratings.

Category Frequency: Top-selling categories emerged (e.g., Electronics, Beauty, Home Decor).
Price Analysis: Detected pricing clusters; some outliers were found and flagged.####
Review Length: Most reviews were short; few long-form ones correlated with stronger sentiment.

## 4. 📊 Bivariate/Multivariate Analysis
Rating vs. Review Sentiment: High correlation between sentiment polarity and star ratings.

Discount vs. Rating: Heavily discounted items tended to receive slightly lower ratings.
Category vs. Average Rating: Some categories consistently outperformed others in terms of customer satisfaction.
Price vs. Rating: No strong direct correlation—suggesting value perception may be subjective or driven by brand.

## 5. 📌 Key Visualizations
Histograms of Ratings, Prices, and Discounts

Bar charts of Review Count per Category
Word Clouds for positive vs. negative reviews
Scatter plots for Discount % vs. Rating
Heatmaps for correlation matrix of numeric features

## 6. 📥 Takeaways from EDA
Customer sentiment is a powerful predictor of overall rating.

Some categories consistently underperform and could benefit from product redesign or better targeting.
A small percentage of products generate a disproportionate number of reviews—potential brand ambassadors or areas for cross-selling.
Discounts attract volume but might impact perception of quality.


