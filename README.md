🌦️ Weather & Environmental Analytics Platform (Power BI + API + DAX)

A production-grade multi-dashboard Business Intelligence solution built using Power BI, live Weather API, Power Query, and DAX, designed to deliver real-time and forecast-based environmental insights across major cities of Nepal.

This project demonstrates end-to-end BI development, including API integration, data modeling (star schema), cross-page interactivity, DAX-driven insights, and dashboard design for decision support.

📌 Project Overview

This solution is designed as a two-layer analytics system:

🔹 1. Main Dashboard (Overview Layer)
High-level monitoring of weather and AQI
City selection using interactive slicers
Summary KPIs and trends
🔹 2. Detail Dashboard (Drill-Down Layer)
Dynamic city-level analysis
Fully synced with main dashboard using slicer synchronization
Deep insights into forecast, AQI, and environmental metrics

👉 Users can select a city in the main dashboard and seamlessly analyze detailed insights in the secondary dashboard.

⭐ Key Features
🌍 Multi-Dashboard Architecture
Designed a two-page interactive BI system
Implemented cross-page slicer synchronization
Enabled seamless drill-down from summary to detailed insights
⚡ Real-Time Weather Monitoring

Tracks current conditions across cities:

Temperature
Humidity
Wind Speed
Visibility
Pressure
UV Index
Precipitation
Weather Condition
📈 7-Day Forecast Analysis
Daily temperature trends
Rain probability visualization
Forecast comparison across cities
Trend-based decision support
🌫️ Air Quality Intelligence (AQI)

Monitors key pollutants:

PM2.5, PM10
CO, NO2, O3, SO2

Includes:

AQI categorization logic
Dynamic color indicators
Health recommendation insights
🧠 Smart Insight Engine (DAX-Based)
City scoring algorithm (weather + AQI + rain)
Best city recommendation
Dynamic text insights for decision support
🔄 Dynamic Filtering & Interactivity
Synced slicers across dashboards
Real-time filter propagation using optimized relationships
Interactive visual responses across all components
🛠️ Tech Stack
Power BI
DAX (Advanced Measures)
Power Query (M Language)
REST API Integration
JSON Transformation
Data Modeling (Star Schema Design)
🌐 Data Source

Live weather data was fetched using a REST API via Power BI Web connector.

API Configuration:
Forecast: 7 Days
AQI: Enabled
Alerts: Disabled

Multiple city endpoints were dynamically combined into a unified dataset.

🏙️ Cities Included
Kathmandu
Pokhara
Biratnagar
Birgunj
Janakpur
Dharan
Lumbini
Bhaktapur
Lalitpur
🔄 Data Engineering Workflow
Connected Power BI to REST API using Web connector
Extracted JSON data for multiple cities
Transformed nested JSON using Power Query
Created structured tables:
Current
Forecast_Day
Forecast_Hour
Location (dimension table)
Designed relationships using Location as central dimension
Removed redundant columns and optimized dataset
Built reusable DAX measures for KPIs and insights
Implemented cross-page slicer synchronization
🧩 Data Model (Star Schema)

The model follows a dimension-driven design:

🔹 Dimension Table:
Location
🔹 Fact Tables:
Current
Forecast_Day
Forecast_Hour
Key Design Highlights:
One-to-many relationships from Location
Optimized filter propagation
Improved performance and scalability
Supports cross-dashboard interactivity
📊 DAX Highlights
🔹 KPI Measures
Current temperature
Forecast averages
Humidity, pressure, visibility
Wind speed, precipitation, UV index
🔹 AQI Intelligence
Pollutant-based scoring
Status classification (Good, Moderate, Hazardous)
Dynamic color logic
🔹 Insight Measures
City ranking algorithm
Best city recommendation
Dynamic text-based insights
💼 Business Value

This project simulates a real-world analytics product that supports:

Environmental monitoring
Smart city insights
Data-driven decision making
Comparative city analysis
Real-time reporting

It demonstrates how external API data can be transformed into a scalable BI solution.

🚀 Why This Project Stands Out

This project goes beyond dashboarding and demonstrates:

End-to-end BI pipeline (API → Model → Dashboard)
Multi-dashboard architecture with drill-down capability
Cross-page filter synchronization
Dimensional data modeling (star schema)
Advanced DAX for insights and business logic
Real-time analytics integration
Strong focus on user experience and decision support
👨‍💻 Author

Sanjeeb Sapkota
Business Analytics | SAP B1 HANA | SQL | Power BI

GitHub: https://github.com/sanjeebsapkota
LinkedIn: https://www.linkedin.com/in/sanjeeb-sapkota-07b625226/
📜 License

This project is intended for portfolio and educational purposes.
