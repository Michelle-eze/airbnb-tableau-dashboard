# Airbnb Listings Dashboard – 2016 Dataset (Tableau)

## 📌 Project Overview

This project visualises and analyses Airbnb listing data from 2016 to explore pricing, availability, and geographic distribution of listings.  
The interactive dashboard lives on Tableau Public and allows filtering by neighbourhood, room type, price range and other listing attributes.

🔗 **Live interactive dashboard on Tableau Public:**  
https://public.tableau.com/app/profile/michelle.ezeudo/viz/AirBnBFullProject_17650678715310/Dashboard1

---

## 🧾 Data

- **Source:** Kaggle — “Airbnb Listings 2016 Dataset” by Alexander Freberg   
- **Number of listings:** APPROXIMATE NUMBER OF ROWS (e.g. 48,000+)  
- **Key fields used:**  
  - `id`  
  - `name` / `description`  
  - `neighbourhood` / `city` / `zipcode`  
  - `room_type`  
  - `price` (nightly)  
  - `availability_365`  
  - `number_of_reviews`  
  - Other relevant fields (e.g. `minimum_nights`, `reviews_per_month`, etc.)

> If you include the dataset here, you’ll find it under `data/airbnb_listings_2016_sample.csv`.

---

## 🛠 Tools Used

- Tableau Public — for data visualisation and dashboard building  
- (Optionally) Excel or CSV — for data inspection or light cleaning before import into Tableau

---

## 📊 Dashboard Views / Structure

The dashboard includes several key views (tabs/sheets) and filters which enable dynamic exploration:

1. **Overview Dashboard**  
   - Summary of total number of listings, average price, availability metrics  
   - Filters for neighbourhood, room type, price range, minimum nights  

2. **Price & Distribution Analysis**  
   - Distribution of nightly prices across listings  
   - Comparison of average price by neighbourhood and room type  
   - Identification of outliers or overpriced/underpriced listings  

3. **Geographical / Map View**  
   - Map of listings locations — clustered by area or neighbourhood  
   - Visual encoding of price or availability for spatial insight  

4. **Availability / Occupancy & Review Patterns**  
   - Distribution of availability over 365 days  
   - Correlation between number of reviews, availability and listing types  

--! Feel free to rename or reorganise based on your actual dashboard structure -->

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

## 📷 Dashboard Preview (Static Screenshots)

[![Airbnb Dashboard Overview](images/overview-dashboard.png)](https://public.tableau.com/app/profile/michelle.ezeudo/viz/AirBnBFullProject_17650678715310/Dashboard1)


Click the image to open the live dashboard.
