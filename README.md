# Airbnb Listings Dashboard – 2016 Dataset (Tableau)

## 📌 Project Overview

This project explores Airbnb listing data from 2016 to analyse pricing, availability, and geographic distribution across neighbourhoods.  
The interactive Tableau dashboard enables users to examine how property characteristics, location, and seasonality influence listing performance.

🔗 **Live interactive dashboard on Tableau Public:**  
https://public.tableau.com/app/profile/michelle.ezeudo/viz/AirBnBFullProject_17650678715310/Dashboard1

---

## 🧾 Data

- **Source:** Kaggle — *Airbnb Listings 2016 Dataset* (Alexander Freberg)  
- **Dataset size:** ~48,000 listings  
- **Key fields used:**  
  - Location attributes (city, neighbourhood, ZIP code)  
  - Property characteristics (room type, bedrooms, minimum nights)  
  - Pricing and availability metrics  
  - Review-related fields (number of reviews, reviews per month)

A small sample of the dataset is included in the `data/` folder for reference.

---

## 🛠 Tools Used

- **Tableau Public** — interactive dashboard design and visual analysis  
- **Excel / CSV** — light data inspection and preparation prior to visualisation

---

## 📊 Dashboard Structure

The dashboard is organised into the following analytical views:

1. **Overview Dashboard**  
   - High-level summary of listing volume, average price, and availability  
   - Filters for neighbourhood, room type, price range, and minimum nights  

2. **Price & Distribution Analysis**  
   - Distribution of nightly prices across listings  
   - Comparison of average prices by room type and neighbourhood  
   - Identification of pricing outliers  

3. **Geographical Analysis**  
   - Map-based view of listing locations by ZIP code  
   - Spatial comparison of average price and listing density  

4. **Availability & Review Patterns**  
   - Distribution of availability across the year  
   - Relationship between reviews, availability, and listing type  

---

## 🔍 Key Insights & Findings

Analysis of the 2016 Airbnb listings dashboard reveals several clear patterns:

### 1. Nightly price rises sharply with bedroom count  
Average price increases non-linearly as bedroom count rises. One-bedroom listings average under $100 per night, while five- and six-bedroom properties command a much higher premium (approximately $450–$585), indicating strong demand for larger listings.

### 2. Listing supply is concentrated at the lower end  
The majority of listings are one-bedroom properties, with supply dropping sharply as bedroom count increases. Larger homes are comparatively scarce, which helps explain their higher average prices.

### 3. Location strongly influences pricing  
Average nightly prices vary significantly by ZIP code. Certain areas consistently command higher prices, while others cluster at lower ranges, highlighting the role of neighbourhood desirability in pricing dynamics.

### 4. Revenue shows seasonal growth patterns  
Weekly revenue increases early in the year, stabilises mid-year, and rises again toward year-end. This pattern suggests seasonal demand effects rather than random fluctuations, with steady booking activity throughout the year.

These findings illustrate how property size, location, and seasonality interact to shape pricing and revenue patterns in the Airbnb market.
---
