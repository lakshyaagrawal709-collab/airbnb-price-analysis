# Airbnb Dynamic Pricing Analysis
**Submitted by:** Lakshay Agrawal

## 1. Title & Description
**What and Why:** An analytics project designed to help Airbnb hosts in Singapore set the right prices. Setting competitive prices prevents lost bookings and maximizes revenue.

## 2. Problem Statement
**Business Context:** Most new Airbnb hosts do not have pricing expertise. The goal of this project is to find out how local factors (like region and room type) impact listing prices so hosts can optimize their rates.

## 3. Data Source
**Where data came from:** The dataset is an open-source Singapore Airbnb dataset downloaded from Kaggle, containing location details, room types, and pricing for over 7,900 listings.

## 4. Methodology
**Approach and Tools:** 
* **Tools Used:** Python, Pandas (Data Cleaning), Seaborn (Visualization), Scikit-Learn (Modeling).
* **Process:** Cleaned missing review values and dropped duplicate records. Performed EDA to compare regions, and built a baseline Random Forest machine learning model to forecast prices.

## 5. Key Findings
**Main Insights:**
* The Central Region is the most expensive market.
* Entire homes/apartments command a massive premium compared to private or shared rooms.

## 6. Results
**Metrics & Visualizations:**
* Generated a correlation heatmap and regional bar charts.
* The predictive model achieved a baseline Root Mean Squared Error (RMSE) metric, giving us a starting point for pricing accuracy.

## 7. Conclusions
**What I learned:** I learned that while machine learning is powerful, raw data is often messy. In the future, I would improve this project by removing extreme pricing outliers (like $10,000/night luxury homes) to make the core model even more accurate.
