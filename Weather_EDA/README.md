<h1 style="background: linear-gradient(to right, #4facfe, #ffffff);
           -webkit-background-clip: text; 
           color: transparent;">
India Weather EDA Project
</h1>

This project performs an Exploratory Data Analysis (EDA) on real-time weather data of all Indian State and Union Territory capitals. The data was fetched using the OpenWeatherMap API and analyzed using Python to understand temperature, humidity, wind speed, pressure, and overall climatic variations across India.

## 📌 Project Overview
The goal of this project is to analyze and visualize weather patterns across India using API-collected real-time data. The analysis includes temperature comparisons, humidity distribution, wind speed variations, statistical summaries, outlier detection, and multiple heatmaps to highlight regional climate differences.

## 🗂️ Dataset Information
- **Source:** OpenWeatherMap API  
- **Cities:** 34 capitals  
- **Columns:** 9 weather features  
- **Key Attributes:** temperature, feels_like, temp_min, temp_max, humidity, pressure, wind_speed, weather_description  

## 🔧 Technologies Used
Python, Pandas, Matplotlib, Seaborn (local), Requests, Jupyter Notebook  

## 📥 Data Collection
Data is collected via API using:
`https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid=YOUR_API_KEY&units=metric`

Coordinates for all Indian capitals were looped to fetch temperatures, humidity, wind speed, and weather conditions.

## 📊 Visualizations Included
- Scatter plots: Temperature vs Humidity, Temperature vs Wind Speed, Humidity vs Wind Speed  
- Histograms: Temperature distribution, Humidity distribution  
- Boxplots: Outlier detection for temperature & humidity  
- Heatmaps: Temperature, Humidity, Wind Speed, Correlation heatmap  
- Weather condition frequency & pie chart  

## 📈 Statistical Analysis
Includes mean, median, quartiles, standard deviation, ranges, and Z-score based outlier detection for temperature and humidity.

## 📝 Key Insights
- Temperature-related features show strong positive correlation.  
- Humidity and wind speed vary independently across regions.  
- Clear climatic differences exist between coastal, central, northern, and hilly regions.  
- Outlier cities show extreme heat, cold, or humidity levels.  

## 💾 Export
Final dataset saved as: `india_weather_data.csv`

## 🏁 Conclusion
The EDA highlights India’s diverse climatic behavior, showing how weather parameters change significantly across regions. Heatmaps, scatterplots, and statistical analysis reveal meaningful patterns and anomalies. This project establishes a strong foundation for future forecasting, dashboards, or machine learning models based on weather data.

## 📌 Future Scope
- Time-series weather forecasting  
- Machine learning prediction models  
- Interactive dashboards  
- Seasonal and regional climate studies  

