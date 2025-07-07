
# Airbnb NYC 2019 - Exploratory Data Analysis

## 📁 Project Overview

This project performs an exploratory data analysis (EDA) on the Airbnb NYC 2019 dataset. The main goal is to discover patterns in pricing, room types, availability, and host behaviors across New York City boroughs.

---

## 📊 Dataset Information

- **Source**: Inside Airbnb
- **Records**: Over 48,000 listings
- **Features**: ID, host details, neighbourhood, latitude/longitude, room type, price, minimum nights, number of reviews, availability, etc.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – for data manipulation
- **Matplotlib** and **Seaborn** – for data visualization
- **Jupyter Notebook** – for code development and analysis

---

## 🧹 Data Cleaning Steps

1. Removed duplicate entries
2. Filled missing values in `reviews_per_month` and `last_review`
3. Converted `last_review` to datetime format
4. Removed listings with 0 price or 0 minimum nights

---

## 📈 Key Analyses and Visualizations

- Room type distribution
- Price distribution (overall and by borough)
- Reviews vs Price scatter plot
- Listings concentration by neighbourhood
- Availability patterns
- Top hosts and their listing counts
- Correlation heatmap and density plots

---

## 📌 Key Insights

- **Entire home/apt** is the most popular and expensive room type
- **Manhattan** has the highest number of listings and average prices
- Most listings are priced between **$50–$200**
- A few hosts manage multiple listings, indicating commercial usage
- Listings with low prices and high availability tend to receive more reviews

---

## ✅ Conclusion

The analysis shows that affordability, availability, and location are crucial factors influencing guest behavior on Airbnb. Insights from this dataset can guide hosts and businesses in optimizing their pricing and listing strategies.

---

## 🚀 Future Scope

- Predict listing prices using machine learning
- Analyze temporal trends with time series data
- Perform sentiment analysis on reviews or titles

