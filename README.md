![Banner](banner.png)

# 🌦️ Weather Forecast Dashboard


An interactive Power BI dashboard that provides real-time weather insights and forecasts for six major capital cities across Europe and North Africa.

![Dashboard Preview](dashboard_overview_2.png)


## 🌍 Featured Cities

| City | Country |
|------|---------|
| **London** | United Kingdom |
| **Berlin** | Germany |
| **Paris** | France |
| **Madrid** | Spain |
| **Rome** | Italy |
| **Rabat** | Morocco |

## ✨ Key Features

### 🌡️ Temperature Insights
- Current temperature with weather conditions
- 7-day temperature trend visualization
- Daily high and low forecasts
- Hourly breakdown with line charts

### 🌧️ Precipitation Analysis
- Probability of rain vs. no-rain by day
- Visual percentage breakdown
- Week-at-a-glance rain forecast

### 🌅 Astronomical Data
- Precise sunrise times
- Sunset times by location
- Daily variation tracking

### 🌬️ Atmospheric Conditions
Complete weather metrics dashboard including:
- **Humidity** 
- **Wind Speed**
- **Visibility** 
- **Atmospheric Pressure** 
- **UV Index** 
- **Precipitation** 

### 🗺️ Interactive Elements
- City selector with navigation buttons
- Dynamic map view showing selected location
- Quick-switch between capitals
- Responsive visual updates

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Power BI Desktop** | Data visualization and dashboard design |
| **DAX** | Custom calculations and KPIs |
| **Power Query** | Data transformation and API integration |
| **WeatherAPI** | Real-time weather data source |
| **M Language** | ETL processes and data shaping |

### 📡 Data Source
Weather data powered by [WeatherAPI.com](https://www.weatherapi.com/api-explorer.aspx#forecast)

## 📊 Visual Components

| Visual Type | Description |
|-------------|-------------|
| **KPI Cards** | Current conditions and key metrics |
| **Line Chart** | Temperature trends over time |
| **Bar Chart** | Rain probability comparison |
| **Map Visual** | Geographic location display |
| **Icon Sets** | Weather condition indicators |
| **Slicers** | City navigation and filtering |

## 🎯 Dashboard Objectives

This dashboard was designed to provide actionable weather intelligence for:

✅ **Travel Planning** - Make informed decisions about upcoming trips  
✅ **Event Management** - Schedule outdoor activities confidently  
✅ **Daily Routine** - Plan your day based on weather conditions  
✅ **Business Operations** - Weather-dependent business planning  
✅ **Comparative Analysis** - Compare conditions across multiple cities

## 📂 Repository Structure
```
PowerBI-Weather-Dashboard/
│
├── README.md                    
├── Weather_Dashboard.pbix       
├── dashboard_overview_1.png
├── dashboard_overview_2.png
└── banner.png
```

## 🚀 Getting Started

### Prerequisites
- **Power BI Desktop** (latest version)
- **WeatherAPI** account (free tier available)
- Internet connection for API calls

### Installation

1. **Clone this repository**

2. **Open the dashboard**
   - Launch Power BI Desktop
   - Open `Weather_Dashboard.pbix`

3. **Configure API (if needed)**
   - Go to Home → Transform Data
   - Update API credentials in Power Query
   - Refresh data

## 🔄 Data Refresh

The dashboard can be configured to:
- Refresh manually on-demand
- Schedule automatic refreshes (with Power BI Service)
- Update data via API calls in real-time

## 📸 Dashboard Preview

### Main View - Berlin
![Berlin Weather](dashboard_overview_1.png)

*Features: Current conditions, 7-day forecast, rain probability, sunrise/sunset times, and comprehensive atmospheric data*

## 🎨 Design Principles

- **Modern UI/UX** - Clean, intuitive interface with smooth navigation
- **Data-First** - Focus on actionable insights over decoration
- **Responsive Layout** - Optimized for different screen sizes
- **Consistent Theme** - Cohesive color scheme matching weather conditions
- **Accessibility** - High contrast and readable typography


## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Weather data provided by **WeatherAPI.com**
- Icons and visual elements created using Power BI native features
- Dashboard design inspired by modern weather applications

---

**By Hamza Hibbah Falaki** | Power BI Weather Analytics Dashboard
