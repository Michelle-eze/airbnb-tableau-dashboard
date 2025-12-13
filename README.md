# airbnb-tableau-dashboard
Airbnb listings tableau project
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

Feel free to rename or reorganise based on your actual dashboard structure.

---

## 🔍 Key Insights & Observations  

Here are a few observations based on the 2016 dataset (update with your actual findings):

- Listings in central / high-demand neighbourhoods tend to have **higher average nightly price** and **higher review counts**, indicating high demand and turnover.  
- Entire home/apartment listings are generally priced higher than private rooms.  
- Some areas show **high availability but low reviews**, suggesting oversupply or lower demand.  
- A subset of listings combine **low price + high availability + high reviews** — potential sweet spots for travellers or budget-conscious renters.

*(Replace or expand with real insights derived from your dashboard.)*

---

## 📷 Dashboard Preview (Static Screenshots)

[![Airbnb Dashboard Overview](images/overview-dashboard.png)](https://public.tableau.com/app/profile/michelle.ezeudo/viz/AirBnBFullProject_17650678715310/Dashboard1)

*Additional views:*  
- `images/price-distribution.png` — Price distribution and comparison  
- `images/map-view.png` — Geographic heatmap of listings  

Click the image to open the live dashboard.
