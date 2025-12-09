# British Airways Customer Review Analysis Dashboard  

### Overview
This project analyzes customer reviews of British Airways to uncover trends in passenger satisfaction, focusing on cabin staff service, overall ratings, and aircraft-specific performance. The interactive Tableau dashboard allows filtering by traveler type, seat class, continent, rating category, and time period.

### Data Set
- 2016–2023 British Airways passenger review data
- Metrics include cabin staff service, seat comfort, entertainment, food/beverages, ground service, and overall rating
- Traveler type, seat class, country of reviewer, and aircraft model
- Source: British Airways Reviews Dataset (CSV included in repository)

### Key Documents
- **Insights:** `docs/insights.md`  
- **Methodology:** `docs/methodology.md`  
- **KPIs:** `docs/kpis.md`
 
### Tools 
- **Tableau** for dashboard design and analytics
- **Excel/CSV** for data exploration and preparation
- **Mapbox** for geospatial visualizations
- **Data Analysis** (KPI creation, segmentation, trend analysis)

### Dashboard
<img width="1215" height="708" alt="Screenshot 2025-12-05 at 3 44 47 PM" src="https://github.com/user-attachments/assets/989aa096-8592-41f0-9823-2a24e1cb7b22" />

### Interactive Features
The dashboard allows users to explore British Airways ratings by adjusting several filters:
- **Metric Selector**: Choose which rating to analyze, including Overall Rating, Cabin Staff, Food, Entertainment, Food, Ground Service and Seat Comfort
- **Date Range Filter**: Use the slider to view ratings across and period between March 2016 and October 2023
- **Traveller Type Filter**: Compare experiences across different passenger categories such as Business, Couple Leisure, Family Leisure, and Solo Leisure.
- **Seat Type Filter**: Analyze how ratings vary across Economy, Premium Economy, Business Class, and First Class.
- **Continent Filter**: Focus the analysis on reviews from specific geographic regions.
- **Aircraft Group Filter**: Analyze the performance of different Airbus and Boeing aircraft models.
- **Interactive World Map**: Click on any country to filter the dashboard and analyze average ratings, aircraft preferences, and review patterns specific to that location.

### Scenarios
**Scenario 1 — United Kingdom**: 
<img width="1323" height="703" alt="Screenshot 2025-12-08 at 4 51 39 PM" src="https://github.com/user-attachments/assets/fad92f53-5c6d-4822-b54c-078c8fd22588" />
- Represents a high review volume with 849 total reviews, providing strong data reliability.
- Shows an average overall rating of 4.2, closely aligned with the global average.
- Long haul Boeing aircraft received the highest satisfaction scores (e.g., Boeing 747-400: 5.2, Boeing 747: 4.9).
- Smaller Airbus models trend lower, indicating higher traveler satisfaction on long haul aircraft commonly used on international routes.



**Scenario 2 — COVID Period (March 2020–March 2021)**: 
<img width="1219" height="702" alt="Screenshot 2025-12-08 at 5 30 23 PM" src="https://github.com/user-attachments/assets/17d8473c-1618-4196-acb3-76b6f37ea6fd" />
- Review volume is extremely low, which is consistent with reduced operations and limited passenger traffic during COVID.
- The filtered period shows an elevated average overall rating of 5.1, higher than the long term average for British Airways.
- Boeing 747-400 and A320 achieve exceptionally high ratings (8.0), indicating very positive long-haul or limited-service flight experiences during this period.

**Scenario 3 — Customer Ratings Across 2022**:
<img width="1224" height="710" alt="Screenshot 2025-12-09 at 11 24 50 AM" src="https://github.com/user-attachments/assets/79d27d36-19a8-47d0-81fb-b1244f129e39" />
- Monthly ratings decline steadily through the first half of 2022, reaching their lowest point in August, before recovering into the fall.
- Aircraft performance varies widely: the A320 (4.4) and Boeing 777-200 (4.0) lead the year, while smaller aircraft such as the A319, A321, and Boeing 787 (1.3–2.0) show notably lower satisfaction.
- Entertainment (1.3) and food (2.7) remain the weakest-rated service areas, consistently trailing the overall rating.
