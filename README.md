<div align="center">
  # 🌤️ Weather Forecasting Website
  *Developed by Vinayak Sharma for EDEMS Pvt. Ltd.*
  
  <p align="center">
    <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
    <img src="https://img.shields.io/badge/OpenWeatherMap-API-blue?style=for-the-badge" alt="OpenWeatherMap" />
  </p>
  
  <p align="center">
    <a href="https://github.com/TechBastards/Weather-Forecasting-Website">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=TechBastards&repo=Weather-Forecasting-Website&theme=tokyonight&hide_border=true" alt="Weather App Repo Stats" />
    </a>
  </p>
</div>

A **dynamic weather forecasting web application** built using **HTML, CSS, and JavaScript** that provides real-time weather data for any location in the world.

The application integrates with the **OpenWeatherMap API** to fetch and display weather conditions, allowing users to search for a city or automatically detect their current location to view weather information.

---

#  Project Overview

The Weather Forecasting Website enables users to quickly check weather conditions for any city, state, or country.

Users can:

* Search weather data for a specific location
* View weather forecasts for multiple days
* Detect and display weather for their **current location**
* Handle invalid inputs gracefully
* Interact with a clean and responsive interface

The goal of this project is to demonstrate:

* **API integration using JavaScript**
* **Dynamic DOM manipulation**
* **Handling asynchronous requests**
* **Geolocation API usage**
* **User-friendly UI design**

---

#  Problem Statement

Weather applications are commonly used tools that rely on **external APIs and real-time data processing**.

Many beginner projects focus only on static interfaces and do not integrate live data sources.

This project solves that by building a **dynamic weather application** that:

* Fetches real-time weather information
* Allows location-based queries
* Handles user input validation
* Uses browser geolocation services

---

#  Solution Approach

The application uses the **OpenWeatherMap API** to fetch weather information based on user input or the user’s current location.

The workflow involves:

1. Capturing user input (city/state/country)
2. Sending an API request to OpenWeatherMap
3. Processing the JSON response
4. Dynamically updating the UI with weather information

Additionally, the **Geolocation API** is used to detect the user's current coordinates and fetch weather data for that location.

---

#  Key Features

###  Location-Based Search

Users can enter a **city, state, or country name** to retrieve weather data.

###  Current Location Weather

Users can click **Use Current Location** to automatically fetch weather data based on their device location.

###  Multi-Day Weather Forecast

Displays weather conditions for the **current day and the previous 5 days**.

###  Error Handling

If the user enters an invalid location:

* An alert message appears
* The system notifies that coordinates are not available

###  Geolocation Permission Handling

When using current location:

* Browser asks for location permission
* If allowed → weather data is displayed
* If blocked → alert appears explaining that geolocation access is required

###  Responsive Interface

Built with CSS to ensure the UI remains clean and readable across devices.

---

#  Tech Stack

| Technology             | Purpose                 |
| ---------------------- | ----------------------- |
| **HTML5**              | Page structure          |
| **CSS3**               | Layout and styling      |
| **JavaScript (ES6)**   | Application logic       |
| **OpenWeatherMap API** | Weather data source     |
| **Geolocation API**    | User location detection |

---

#  Project Architecture

```
User Input / Location Detection
             │
             ▼
      JavaScript Logic
             │
             ▼
     OpenWeatherMap API
             │
             ▼
       JSON Response
             │
             ▼
   Dynamic DOM Rendering
             │
             ▼
     Weather Information UI
```

---

#  Folder Structure

```
weather-forecasting-website
│
├── index.html        # Main website structure
├── style.css         # Styling and layout
├── script.js         # Weather API & application logic
└── README.md         # Project documentation
```

---

# Project Demo

https://github.com/TechBastards/Weather-Forecasting-Website/raw/main/demo.mp4

#  Usage

1️⃣ Enter a **city, state, or country name** in the search field

2️⃣ Click the **Search** button

3️⃣ View weather data for the selected location

OR

1️⃣ Click **Use Current Location**

2️⃣ Allow location access when prompted

3️⃣ View weather data for your current location

---

#  Example Output

The application displays:

* Temperature
* Weather conditions
* Location name
* Multi-day forecast

Example:

```
Location: London
Temperature: 18°C
Condition: Cloudy
Humidity: 72%
Wind Speed: 10 km/h
```

---

#  Challenges & Learnings

### API Integration

Fetching and handling data from the **OpenWeatherMap API** required understanding asynchronous JavaScript and API response handling.

### Geolocation Permissions

Handling cases where users allow or deny location access was important for ensuring smooth user experience.

### Error Handling

Validating user input and managing incorrect location queries helped improve application reliability.

---

#  Future Improvements

Potential enhancements for the project:

* Add **7-day weather forecast**
* Implement **search history**
* Display **weather icons and animations**
* Add **temperature unit toggle (°C / °F)**
* Deploy the project using **GitHub Pages**
* Implement **mobile-first responsive design**

---

# 👨‍💻 Author

**Vinayak Sharma**

* [GitHub](https://github.com/TechBastards)
* [LinkedIn](https://www.linkedin.com/in/vinayak-sharma-24a8aa384/)

---

