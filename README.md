# Analysing the Impact of Weather Conditions on Traffic Collisions  
A Data-Driven Study Using OpenWeather API (2024)  

**Author:** Anushka Katiyar  
**Affiliation:** Ming Hsieh Department of Electrical & Computer Engineering | University of Southern California  
**Collaborators:** Northeast Big Data Innovation Hub, National Student Data Corps  

---

## Abstract  
This project investigates the correlation between weather conditions and traffic collisions using real-world crash data enriched with weather information from the OpenWeather API. The analysis explores how different weather types (rain, clear, cloudy) and temperature variations influence crash frequency, timing, and severity. The study aims to provide actionable insights to improve transportation safety and guide data-driven policy recommendations.  

---

## Methodology  
1. **Crash Data Processing**  
   - Extracted crash records from 2024  
   - Filtered data by latitude, longitude, and date-time  

2. **Weather Data Integration**  
   - Queried OpenWeather API for weather condition and temperature at each crash location and timestamp  
   - Categorized conditions into clear, rainy, cloudy, etc.  

3. **Time-Weather-Crash Analysis**  
   - Merged crash and weather datasets  
   - Conducted statistical and temporal analysis to identify trends  

---

## Results  
- **Crash Volume vs Weather:** Clear weather has the highest crash frequency, followed by rainy and cloudy conditions  
- **Geospatial Distribution:** Hotspots identified across metropolitan areas  
- **Hourly Trends:** Collisions peak during commuting hours (7–9 AM, 4–7 PM)  
- **Weather-Dependent Patterns:** Rain increases nighttime crashes, while clear weather correlates with higher daytime crashes  

---

## Conclusion  
Weather plays a significant role in crash dynamics, but most collisions still occur in clear conditions, likely due to higher traffic volume. Rain and poor visibility increase crash likelihood, especially during off-peak hours. Understanding these interactions helps in improving road safety strategies.  

---

## Recommendations to the Department of Transportation  
- **Dynamic Speed Regulations:** Adjust speed limits based on real-time weather conditions  
- **Weather-Aware Traffic Alerts:** Integrate weather-based crash risk alerts into navigation apps  
- **Infrastructure Enhancements:** Improve lighting and drainage in high-risk crash hotspots  
- **Policy Support:** Encourage use of weather-linked crash forecasting models for proactive planning  

---

## References  
- OpenWeather API Documentation  
- NYC Open Data: Motor Vehicle Collisions  
- Related traffic safety and weather impact studies  

---

## Repository Structure  
├── data/ # Crash datasets and processed files
├── notebooks/ # Jupyter notebooks for analysis
├── scripts/ # Python scripts for API calls and preprocessing
├── results/ # Graphs, plots, and heatmaps
├── README.md # Project documentation

---

## Tech Stack  
- Python (Pandas, Matplotlib, Seaborn, Folium)  
- OpenWeather API  
- Geospatial Analysis Tools (Folium/GeoPandas)  

---

## How to Run  
1. Clone the repository  
   ```bash
   git clone <repo-link>
   cd weather-traffic-collisions
2. Install dependencies
 ```bash
 pip install -r requirements.txt
3. Run the analysis notebooks in notebooks/
4. Generated plots and results are stored in results/
