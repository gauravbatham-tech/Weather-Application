🌦️ Weather Now

A simple and elegant Weather Application built using HTML, CSS, and JavaScript that allows users to check the current weather conditions of any city in the world. The app uses the OpenWeatherMap API to fetch live weather data and dynamically updates the UI with weather icons, temperature, and other details.


---

🚀 Features

🌍 Search for current weather by city name

🌡️ Displays temperature, humidity, pressure, and wind speed

🕒 Shows current date and time

🎨 Dynamic background changes based on weather conditions

💡 Interactive and responsive design

⚠️ Error alerts for empty or invalid city inputs using SweetAlert

⛅ Weather-specific Font Awesome icons



---

🧩 Technologies Used

HTML5 – structure and layout

CSS3 – styling and responsiveness

JavaScript (ES6) – logic and API handling

OpenWeatherMap API – weather data source

SweetAlert – for user-friendly alerts

Font Awesome – for icons

Google Fonts (Poppins) – for typography



---

🔑 API Setup

This app uses the OpenWeatherMap API.
To use it, follow these steps:

1. Go to OpenWeatherMap


2. Sign up and get your API key


3. Replace the placeholder key in script.js:

const weatherApi = {
    key: 'YOUR_API_KEY_HERE',
    baseUrl: 'https://api.openweathermap.org/data/2.5/weather'
}




---

🖥️ How to Use

1. Clone or download this repository.


2. Open the project folder and locate the index.html file.


3. Open index.html in your browser.


4. Enter any city name in the input box and press Enter or click the search button.


5. View the weather details and enjoy the dynamic visuals!

📁 Project Structure

📦 Weather-App
 ┣ 📂 img
 ┃ ┣ bg.jpg
 ┃ ┣ clear.jpg
 ┃ ┣ clouds.jpg
 ┃ ┣ drizzle.jpg
 ┃ ┣ mist.jpg
 ┃ ┣ rainy.jpg
 ┃ ┣ snow.jpg
 ┃ ┗ thunderstorm.jpg
 ┣ 📜 index.html
 ┣ 📜 style.css
 ┗ 📜 script.js


---

🎨 UI Highlights

Smooth fade-in animations

Glassmorphism-inspired card design

Neon glow effects around search and temperature sections

Fully responsive for mobile screens
