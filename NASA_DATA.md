
## 🛰️ NASA Data Usage

WhiskerCast uses NASA’s Earth observation datasets to calculate the likelihood of adverse weather conditions for any location and day of the year.

### Datasets Used
- **NASA POWER API**: Daily historical data for temperature, precipitation, windspeed, and humidity
- **MERRA-2**: Climate extremes and seasonal trends

### How We Use It
- Query location + date → retrieve historical values
- Compare against thresholds (e.g., >90°F for heat)
- Calculate probability of discomfort
- Display results with visual and emotional summaries

These datasets allow WhiskerCast to offer long-range planning insights beyond traditional forecasts.
