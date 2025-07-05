# PRODIGY_DS_05
# Task 05 – US Traffic Accident Data Analysis

## 🎯 Objective
Analyze US traffic accident data to identify patterns related to weather conditions, road surface, time of day, and geography. Visualize accident hotspots and contributing factors to derive actionable insights.

## 📎 Dataset
- Source: [US Traffic Accidents Dataset (via Kaggle)](https://www.kaggle.com/us-accident)
- Contains 4.2 million records of accidents in the US, with information on:
  - Time, location, severity
  - Weather and road conditions
  - Visibility, humidity, wind speed, etc.

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly (optional for interactive visuals)
- Folium (optional for geospatial maps)

## ⚙️ Task Workflow

1. **Data Loading**
   - Loaded a large dataset using `pandas.read_csv()` with optimizations.

2. **Data Cleaning**
   - Handled missing values and irrelevant columns.
   - Filtered accidents by severity and relevant time frames.

3. **Feature Exploration**
   - Analyzed:
     - Accidents by **time of day**, **day of week**, **month**
     - Influence of **weather conditions** and **visibility**
     - Distribution by **state**, **city**, and **severity**

4. **Visualization**
   - Created bar plots and line charts to show:
     - Hourly accident frequency
     - Severity distribution by weather
     - State-wise and city-wise accident counts
   - (Optional) Generated **interactive maps** using Folium to show accident hotspots.

## 📊 Output

- Found that most accidents occur during peak traffic hours (7–9 AM, 4–6 PM).
- Rain, fog, and poor visibility increase accident severity.
- States like **California, Texas, and Florida** showed the highest number of accidents.
- Identified dangerous weather and time zones for travel safety planning.

## 📷 Sample Visuals
*(Optional: Include `accidents_by_hour.png`, `severity_by_weather.png`, `heatmap_us_accidents.png`, etc.)*

## ✅ Learnings

- Learned how to handle and process large-scale datasets.
- Understood the value of EDA in identifying time-based and environmental trends.
- Used various visualization techniques to effectively communicate data-driven insights.
- Gained exposure to geospatial analysis using maps and severity heatmaps.

## 📂 Folder Structure

