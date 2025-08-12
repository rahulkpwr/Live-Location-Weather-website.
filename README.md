# Live-Location-Weather-website.
## 📌 Overview
The **Live Location Weather Website** is a JavaScript-powered web application that provides **real-time weather updates** based on the user’s current location.  
It uses the **OpenWeather API** to fetch live weather data, including **temperature, humidity, wind speed, and weather conditions**, and displays it in a **user-friendly interface**.

---

## 🚀 Features
- **Live Location Detection** – Automatically detects the user’s current location using the Geolocation API.
- **Real-Time Weather Data** – Displays up-to-date weather information.
- **Search by City** – Option to view weather for any city worldwide.
- **Responsive Design** – Works on desktops, tablets, and mobiles.
- **Weather Icons & Animations** – Visual representation of weather conditions.

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **API:** OpenWeather API
- **Browser Feature:** Geolocation API
- **Styling:** CSS Flexbox/Grid

---

## 📂 Project Structure
LiveLocationWeather/
│── index.html # Main HTML file
│── style.css # Styling for the website
│── script.js # JavaScript logic and API integration
│── README.md # Project documentation


---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/LiveLocationWeather.git
   cd LiveLocationWeather
   
2. **Get OpenWeather API Key**
   Sign up at OpenWeather
   Generate your free API key.

3.**Update API Key in script.js**
   const apiKey = "YOUR_API_KEY";
   
4.**Run the Project**
 Open index.html in any browser.

🌦 API Usage Example
API Endpoint:
https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API_KEY}&units=metric
{lat} and {lon} are coordinates from the Geolocation API.
{API_KEY} is your OpenWeather API key.

📈 Future Enhancements
Show hourly & weekly forecasts.

Add background images based on weather conditions.
Include air quality index (AQI).
Add dark mode for better UX.


