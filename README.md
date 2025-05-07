# 🌍 Module 6 Challenge: API Data Analysis

## 📖 Overview

This project focuses on analyzing global weather patterns by leveraging data from the [OpenWeatherMap API](https://openweathermap.org/api). It involves collecting, processing, and visualizing weather data for various cities worldwide to identify trends and insights.

## 📂 Project Structure

- **`WeatherPy.ipynb`**: A Jupyter Notebook that retrieves and analyzes weather data for over 500 cities, generating scatter plots to explore relationships between different weather parameters and geographic locations.

- **`VacationPy.ipynb`**: Builds upon the weather data to identify ideal vacation spots based on specific weather criteria. It utilizes the Google Places API to find hotels in these locations and visualizes the results on a map.

- **`README.md`**: This file provides an overview of the project, setup instructions, and other relevant information.

## 🔧 Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/JetJagar/Module_6_Challenge.git
   cd Module_6_Challenge
Install Dependencies:
Ensure you have the following Python libraries installed:

    pandas

    matplotlib

    requests

    citipy

    gmaps (for map visualizations)

You can install them using pip:pip install pandas matplotlib requests citipy gmaps

API Keys:

    Obtain an API key from OpenWeatherMap.

    Obtain an API key from Google Cloud Platform for the Places API.

    Store these keys in a separate Python file named api_keys.py:

        weather_api_key = "YOUR_OPENWEATHERMAP_API_KEY"
        g_key = "YOUR_GOOGLE_API_KEY"

📊 Features

    Weather Data Analysis:

        Retrieves current weather data for a randomized set of cities.

        Analyzes relationships between latitude and various weather parameters such as temperature, humidity, cloudiness, and wind speed.

        Generates scatter plots to visualize these relationships.

    Vacation Planning:

        Filters cities based on ideal weather conditions for a vacation.

        Uses the Google Places API to find hotels in the selected cities.

        Creates a heat map and marker layer map to display hotel locations and weather conditions.

📈 Visualizations

The project generates several plots, including:

    Latitude vs. Max Temperature

    Latitude vs. Humidity

    Latitude vs. Cloudiness

    Latitude vs. Wind Speed

    Heat maps of humidity

    Hotel locations on a map with weather information

Note: Visual outputs are generated within the Jupyter Notebooks.
📝 Notes

    Ensure that your API keys are kept secure and not shared publicly.

    The citipy library is used to generate a list of cities based on latitude and longitude coordinates.

    The project is designed for educational purposes and may require modifications for production use.

📄 License

This project is open-source and available under the MIT License.


Would you like me to suggest a badge (e.g., Python version, license) or add a screenshot section?
