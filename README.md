# New York Airbnb Listings Analysis 

An exploratory data analysis project on New York City Airbnb listings to understand pricing, demand, and availability patterns across boroughs, neighborhoods, and room types.

## What this project does
- Cleans and explores the dataset (missing values, duplicates, basic distributions)
- Removes extreme outliers using the IQR method
- Visualizes key relationships (price vs location, room type, availability, reviews)
- Summarizes insights that can help hosts decide where and what to list

## Dataset
File: `Airbnb NYC 2019.csv`
- 48,895 listings and 16 columns
- Includes: neighbourhood_group, neighbourhood, room_type, price, minimum_nights, number_of_reviews, last_review, availability_365

## Files in this repo
- `Airbnb_Analysis.ipynb` - notebook with full cleaning, EDA, and visualizations
- `Airbnb NYC 2019.csv` - source dataset

## Key insights (high level)
- Manhattan and Brooklyn show the highest demand and listing concentration
- Prices are generally higher in central areas (especially Manhattan)
- Entire home or apartment and private room listings dominate the market
- Most listings are structured for short-term stays (low minimum nights)

## How to run
1. Open `Airbnb_Analysis.ipynb` in Jupyter Notebook or Google Colab
2. Ensure `Airbnb NYC 2019.csv` is in the same folder (or update the path in the notebook)
3. Run all cells

## Tools used
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn (for preprocessing steps)
