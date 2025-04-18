---
sidebar_label: "Introduction"
sidebar_position: 1
---

## 🌤️ Weather and Agronomic Indicators (Integrated with Fields and Plots)

### 🎯 Goal

Provide key weather and agronomic data to **anticipate weather events**, **plan fieldwork**, and **reduce production risks**, integrated with each registered field or plot in the app.

---

### 🔗 Integration with Fields

Each registered field will have:

- Geographic coordinates (lat/lon)
- Automatic association with a weather data source (external API or personal station)
- Display of real-time weather, forecasts, and historical data specific to that field

---

### 🔑 Key Features

#### 1. Current Weather by Field

- 🌡️ Current temperature
- 💧 Relative humidity
- 🌬️ Wind (speed and direction)
- 🌧️ Rainfall in the last 24h
- ☀️ Solar radiation (optional)

> **Suggested sources:** OpenWeather, Climatic, INTA, or personal weather stations.

---

#### 2. 5–7 Day Weather Forecast

- Daily high and low temperatures
- Rain probability
- Weather alerts (frosts, storms, heatwaves)
- Display in a calendar or task timeline

---

#### 3. Smart Alerts

- ⚠️ Spraying: notify if rain or high winds are expected
- ❄️ Frost: alert for sensitive crops or critical stages
- 🔥 Heatwave: recommendations for livestock or irrigation management

> Alerts are generated automatically based on the forecast linked to each field.

---

#### 4. Historical Weather by Field or Plot

- Accumulated rainfall (daily, weekly, monthly, seasonally)
- Number of frost events
- Comparisons between previous seasons
- Simple chart visualizations

---

#### 5. Agronomic Indicators (Extended Version)

- 🌿 **NDVI** (Vegetation Index): via satellite imagery
- 📈 **Growing Degree Days**: for tracking crop development
- 💦 **Water Index**: simple calculation combining weather + soil data

---

### 🧪 Suggested MVP for This Feature

1. Field geolocation.
2. Current weather and 7-day forecast visible within each field’s profile.
3. Timeline of key weather events.
4. Basic weather alerts (e.g., upcoming rain).
5. Visualization of rainfall accumulated over the past 7 days.

---

### 📲 Suggested UI Display

- Weather module inside each field's detail view.
- Dashboard overview with the current weather for all fields.
- Push or email notifications for relevant alerts.
