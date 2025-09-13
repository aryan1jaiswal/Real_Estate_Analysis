# Real Estate Analysis using Python

## Project Overview
This project focuses on analyzing and modeling residential property prices across Bangalore, Chennai, and Hyderabad. 
It explores key pricing factors, machine learning models for price prediction, and clustering techniques for market segmentation.

## Objective
- To use EDA and determine the key factors affecting housing prices in Bangalore, Chennai, and Hyderabad.
- To derive insights to support real estate investment, buyer decisions and pricing strategies.
- To build predictive ML models that estimate property prices with high accuracy.
- To segment the real estate market using KMeans clustering technique

## Steps and Workflow
### 1. Data Cleaning and Preprocessing
- Removed extreme outliers using price and area filters. 
- Renamed column names for consistency.
- Handled nulls and duplicated entries.

### 2. Feature Engineering
- Created price_per_sqft to normalize pricing patterns.
- One-hot encoded location.

### 3. Exploratory Data Analysis (EDA)
- Visualized price distributions across cities.
- Analyzed median pricing, variability, and number of bedrooms.
- Identified key patterns in price_per_sqft and location.

### 4. Modeling and Evaluation
- Applied Linear Regression to establish a baseline.
- Trained Random Forest Regressor to significantly improve prediction accuracy.
- Evaluated models using MAE, RMSE, and R² Score.

### 5. Market Segmentation using Clustering
- Used KMeans Clustering to visualize clusters.
- Determined optimal k using the Elbow Method.

## Key Findings and Insights

### 1. Median Housing Prices
- Bangalore has the highest median property price among the three cities, affirming its status as a premium real estate hub.
- Chennai displays moderately high median prices, indicating a stable and mature market with relatively lower variability than Bangalore.
- Hyderabad remains the most affordable, with lower median prices, suitable for first-time buyers seeking appreciation potential.

### 2. Price Variability & Market Diversity
- Bangalore has the widest range of property prices, suggesting the presence of both luxury properties and budget-friendly options. This makes it appealing to diverse buyer segments.
- Chennai shows moderate variability, pointing to a consistent mid-tier market. It reflects stable pricing with fewer outliers.
- Hyderabad exhibits least variability, highlighting a more uniform market structure.

### 3. Outliers and High-Value Properties
- Bangalore had the highest number of outlier transactions, with several properties exceeding ₹10 Crores.
- Chennai and Hyderabad had fewer such high-end outliers, suggesting relatively lower luxury density.

### 4. Price Trends by Area and Bedrooms
- There is a non-linear relationship between area and price. Larger properties do not always command proportionally higher prices, especially in outskirts.
- Price per Sqft emerged as a more reliable indicator of value, improving prediction accuracy.
- Properties with 2 and 3 bedrooms dominate across all cities. However, Bangalore had a notable volume of 4+ BHK homes, indicating a higher luxury demand.

### 5. Resale vs. New Properties
- New properties had higher prices per sqft, especially in tech-driven zones.
- Resale properties were more price competitive and could offer better deals, particularly in Chennai and Hyderabad.

### 6. Investment Potential by City

#### Bangalore:
- Strong demand, high appreciation potential.
- Excellent for luxury segment investment or long-term capital gain.

#### Chennai:
- Moderate growth with consistent returns.
- Best suited for middle-income housing and stable rental yields.

#### Hyderabad:
- High model accuracy (R² > 0.95) shows price predictability.
- Still relatively affordable with rapid infrastructure growth, making it ideal for early-stage investors.

