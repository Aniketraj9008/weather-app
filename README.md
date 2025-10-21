Weather App
A sleek, responsive weather application allowing users to check real-time weather information for any city worldwide. Built with HTML, CSS, and JavaScript, it uses the OpenWeatherMap API for accurate weather data and utilizes Font Awesome for rich iconography.

🌟 Features
City Search: Enter any city name to get up-to-date weather conditions.

Weather Info: Displays temperature (°C), city, humidity, wind speed, and weather status icon.

Live Icons: Weather icon dynamically changes based on current weather (Clear, Clouds, Rain, etc.).

Error Handling: Shows a friendly error message for invalid city names.

Animated, Modern UI: Stylish card design, responsive layout, and animated components for all devices.

🚀 Getting Started
Clone or Download the repository.

Open index.html in any modern web browser.

Enter a city name and click the search button or press "Enter" to view the weather.

🧑‍💻 How It Works
Uses OpenWeatherMap API to fetch current weather data in metric units.

Dynamically updates HTML elements with temperature, humidity, wind, and suitable animated weather icons.

Handles invalid input with an error message and hides weather details if the query fails.

🗂️ Project Structure
text
weather-app/
│
├── index.html   # Main structure and search functionality
├── style.css    # Styling: layout, search, card, error, and animation
├── script.js    # API calls, DOM updates, and icon logic
🛠️ Customization
Change color schemes or gradients in style.css for a unique look.

Expand weather icon logic in script.js to cover more weather types or add custom icons.

Use your own OpenWeatherMap API key.

🔑 API Info
Replace const apiKey = "YOUR_API_KEY"; in script.js with your OpenWeatherMap API key.
