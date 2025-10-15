# Air Quality Prediction & Visualization

## Project Overview
Predicted air quality levels across major Indian cities using Python. Visualized insights using a variety of graphs — including AQI trends over time, city-wise comparisons, temperature vs AQI, humidity vs AQI, and correlation heatmaps — for actionable insights similar to a Power BI dashboard.

## Dataset
- 1200+ records across 10 major Indian cities.
- Weather features: Temperature, Humidity, Wind Speed, Month, Day of Week.
- Target: AQI (Air Quality Index).

## Methodology
1. **Data Preprocessing**: Cleaned data, converted date column to datetime, created month and day_of_week features.
2. **Exploratory Data Analysis (EDA)**: Visualized AQI trends, city comparisons, and relationships with weather features.
3. **Model Training**: Random Forest Regression to predict AQI based on weather factors.
4. **Prediction**: Generated predicted AQI levels for all cities and analyzed trends.

## Visualizations
- **Line Charts**: AQI trends over time for selected cities.
- **Bar Charts**: Average AQI per city.
- **Scatter Plots**: Temperature vs AQI, Humidity vs AQI.
- **Correlation Heatmap**: Relationships between weather variables and AQI.

## Tools & Technologies
- Python, Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest Regressor)
- Dashboard-style visualizations for actionable insights

## Outcome
- Identified cities with higher air pollution levels.
- Showed how weather factors affect AQI.
- Created a dashboard-like summary suitable for stakeholders or decision-making.
