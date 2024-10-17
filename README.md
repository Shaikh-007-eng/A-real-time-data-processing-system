**Real-Time Weather Monitoring System**

Description

This project retrieves real-time weather data from the OpenWeatherMap API for selected cities in India (like Delhi, Mumbai, Bangalore, etc.) and processes it to provide insights such as:

Average, maximum, and minimum temperature.

Dominant weather condition for each day.

Alerts when temperature thresholds are exceeded (e.g., temperature above 35°C).


Features

Fetches weather data at regular intervals (e.g., every 5 minutes).

Tracks weather data and alerts when thresholds are breached.

Calculates daily summaries including average, max, and min temperatures, as well as dominant weather conditions.


Requirements

Python 3.x

Requests Library: Install using pip install requests

OpenWeatherMap API Key: You need an API key from OpenWeatherMap.


Setup and Usage

1. Clone this repository:

git clone https://github.com/your-username/your-repo-name.git


2. Install the required libraries:

pip install requests


3. Get your OpenWeatherMap API Key from OpenWeatherMap, and replace the placeholder 'YOUR_API_KEY' in the code.


4. Run the script:

python weather_monitoring.py



Sample Output

City: Delhi
Weather: Clear Sky
Temperature: 30°C

Alert! The temperature in Delhi is above 35°C!

License

This project is licensed under the MIT License.
