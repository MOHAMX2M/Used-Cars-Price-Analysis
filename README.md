🚗 Used Cars Price Analysis
📌 Project Overview

This project focuses on analyzing the used car market in India, using data scraped from Cars24 across four major cities: Delhi-NCR, Bangalore, Hyderabad, and Mumbai. The goal was to understand pricing patterns, affordability, brand performance, fuel trends, and cost efficiency to help buyers and sellers make informed decisions.

🛠 Tools & Technologies

Web Scraping: Selenium (dynamic scrolling), BeautifulSoup (HTML parsing)

Data Processing & Cleaning: Python (Pandas, NumPy)

Visualization & Analysis: Power BI (DAX, dashboards)

📂 Data Pipeline

Web Scraping (Selenium + BeautifulSoup):

Extracted car details (title, price, KM driven, fuel type, EMI, transmission, etc.).

Handled infinite scrolling and dynamic content loading.

Saved results into CSVs per city.

Data Cleaning & Transformation (Pandas):

Standardized price (₹ Lakh → numeric, Crore → numeric).

Converted KM driven (63.02k → 63,020; 1.1L → 110,000).

Cleaned EMI values (₹13,998/m → 13998).

Extracted brand names from car titles.

Created new feature: Price per KM.

Visualization & Insights (Power BI):

Car count by brand & city

Average price by brand & city

Fuel type distribution

Price vs. KM driven (scatter)

Price vs. EMI (scatter by city)

Cost efficiency (₹ per KM) by brand

📊 Key Findings

Brands: Maruti, Hyundai, and Tata dominate in volume; luxury brands (BMW, Jaguar, Land Rover) lead in pricing.

Fuel Types: Petrol cars dominate, followed by Diesel; EV/Hybrid adoption remains low.

Depreciation: Higher kilometers reduce price, but luxury brands retain value longer.

Cities: Bangalore has the highest listings; Hyderabad shows the highest average price; Mumbai has the most budget-friendly options.

Financing: EMI is directly proportional to price; premium cars carry high monthly EMIs.

Cost Efficiency: Maruti, Tata, and Hyundai provide best value per km, while luxury brands are least cost-efficient.

✅ Conclusion

This project demonstrates how web scraping, Python-based cleaning, and Power BI dashboards can uncover valuable market insights. The analysis highlights how brand, fuel type, location, and mileage affect used car prices — helping consumers and businesses optimize purchase and sales strategies.
